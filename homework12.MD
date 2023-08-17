1 = film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

SELECT length
FROM film
WHERE film.length >
(
    SELECT AVG(length)
    FROM film
);
2 = film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

SELECT COUNT(*)
FROM film
WHERE rental_rate =
(
    SELECT MAX(rental_rate)
    FROM film
);
3 = film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.

SELECT *
FROM film
WHERE rental_rate = (
    SELECT MIN(rental_rate)
    FROM film
) AND replacement_cost = (
    SELECT MIN(replacement_cost)
    FROM film
);

4 = payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

SELECT customer_id, total_amount
FROM (
    SELECT customer_id, SUM(amount) as total_amount
    FROM payment
    GROUP BY customer_id
) AS payment_sums
ORDER BY total_amount DESC;
