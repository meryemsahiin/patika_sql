1 = test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
    id SERIAL PRIMARY KEY,
    name VARCHAR(50),
    birthday DATE,
    email VARCHAR(100)
);

2 = Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (name, birthday, email) values ('Laurence', '1980-02-01', 'lflaxman0@businessweek.com');
insert into employee (name, birthday, email) values ('Trumaine', '1979-08-21', 'twandtke1@acquirethisname.com');
insert into employee (name, birthday, email) values ('Leshia', '1964-01-07', 'lhonacker2@cisco.com');
insert into employee (name, birthday, email) values ('Afton', '1983-09-17', 'amonkton3@walmart.com');
insert into employee (name, birthday, email) values ('Cynthy', '1997-02-18', 'cdeminico4@prlog.org');
insert into employee (name, birthday, email) values ('Alvinia', '1994-04-07', 'agreenrod5@google.com');
insert into employee (name, birthday, email) values ('Harlan', '1970-12-28', 'hfairbard6@china.com.cn');
insert into employee (name, birthday, email) values ('Bendick', '1966-04-30', 'bforseith7@columbia.edu');
insert into employee (name, birthday, email) values ('Rickey', null, 'rclutram8@comcast.net');
insert into employee (name, birthday, email) values ('Godard', '1965-08-08', 'gtertre9@dell.com');
insert into employee (name, birthday, email) values ('Emmalyn', '1990-06-18', 'efarlanda@freewebs.com');
insert into employee (name, birthday, email) values ('Marco', '1961-11-22', 'mmarhamb@yahoo.com');
insert into employee (name, birthday, email) values ('Yasmin', '1982-03-22', 'yventumc@delicious.com');
insert into employee (name, birthday, email) values ('Cassey', '1972-05-23', 'cattersolld@alibaba.com');
insert into employee (name, birthday, email) values ('Fran', '1999-01-26', 'fmaughane@prnewswire.com');
insert into employee (name, birthday, email) values ('Ruddy', '1991-12-07', 'rchalkef@house.gov');
insert into employee (name, birthday, email) values ('Edithe', '1986-06-29', 'eenticknapg@123-reg.co.uk');
insert into employee (name, birthday, email) values ('Lauren', '1963-12-16', 'lwellbelovedh@xrea.com');
insert into employee (name, birthday, email) values ('Gweneth', '1984-09-23', 'gendrighii@berkeley.edu');
insert into employee (name, birthday, email) values ('Kizzee', '1990-10-02', 'kwebbej@gizmodo.com');
insert into employee (name, birthday, email) values ('Andre', '1965-02-06', 'amcfeatek@opensource.org');
insert into employee (name, birthday, email) values ('Holt', '1969-12-10', 'hhazardl@hatena.ne.jp');
insert into employee (name, birthday, email) values ('Laverne', null, 'lhassurm@gizmodo.com');
insert into employee (name, birthday, email) values ('Wilie', '1981-10-01', 'wdigiorgion@boston.com');
insert into employee (name, birthday, email) values ('Udell', '1961-02-03', 'udriverso@soundcloud.com');
insert into employee (name, birthday, email) values ('Arlinda', '1973-04-25', 'amacaskiep@domainmarket.com');
insert into employee (name, birthday, email) values ('Deonne', '1990-03-23', 'detchesq@pagesperso-orange.fr');
insert into employee (name, birthday, email) values ('Leela', '1973-01-09', 'ldukelowr@themeforest.net');
insert into employee (name, birthday, email) values ('Fields', null, 'fbaccuss@networksolutions.com');
insert into employee (name, birthday, email) values ('Caz', '1977-04-20', 'cturest@cmu.edu');
insert into employee (name, birthday, email) values ('Esteban', '1998-04-15', 'esellarsu@trellian.com');
insert into employee (name, birthday, email) values ('Evangelia', '1993-04-25', 'ecollopyv@phpbb.com');
insert into employee (name, birthday, email) values ('Jo ann', '1983-10-12', 'jtrevallionw@ezinearticles.com');
insert into employee (name, birthday, email) values ('Odessa', '1986-08-09', 'oabsalomx@behance.net');
insert into employee (name, birthday, email) values ('Elisabetta', '1997-12-22', 'ewagerfieldy@networkadvertising.org');
insert into employee (name, birthday, email) values ('Annie', '1988-01-07', 'adomaschkez@nbcnews.com');
insert into employee (name, birthday, email) values ('Inesita', '1976-02-24', 'ipetow10@un.org');
insert into employee (name, birthday, email) values ('Stanton', '1982-02-10', 'sganders11@businessweek.com');
insert into employee (name, birthday, email) values ('Ashbey', '1997-01-18', 'ajenken12@comcast.net');
insert into employee (name, birthday, email) values ('Pierette', '1985-10-03', 'pbraunds13@desdev.cn');
insert into employee (name, birthday, email) values ('Conrado', null, 'csanten14@mlb.com');
insert into employee (name, birthday, email) values ('Willard', '1990-12-15', 'wmckennan15@yale.edu');
insert into employee (name, birthday, email) values ('Easter', '1994-07-18', 'ehayhurst16@fc2.com');
insert into employee (name, birthday, email) values ('Jerome', '1994-12-09', 'jlannen17@tuttocitta.it');
insert into employee (name, birthday, email) values ('Morton', '1975-02-18', 'mswancock18@blogs.com');
insert into employee (name, birthday, email) values ('Damaris', '1980-10-22', 'dungerecht19@whitehouse.gov');
insert into employee (name, birthday, email) values ('Rafe', null, 'rclubley1a@latimes.com');
insert into employee (name, birthday, email) values ('Hadrian', '1960-11-28', 'hjuszkiewicz1b@linkedin.com');
insert into employee (name, birthday, email) values ('Merrile', '1987-02-19', 'mcantle1c@paginegialle.it');
insert into employee (name, birthday, email) values ('Selig', '1973-09-10', 'smcilory1d@gizmodo.com');
insert into employee (name, birthday, email) values ('Jessalin', '1969-09-02', 'jfowells1e@wix.com');
insert into employee (name, birthday, email) values ('Reinaldos', '1983-08-10', 'rhaddow1f@independent.co.uk');
insert into employee (name, birthday, email) values ('Ginny', '1974-12-13', 'gduckering1g@mayoclinic.com');
insert into employee (name, birthday, email) values ('Suzie', '1981-01-08', 'sduce1h@who.int');
insert into employee (name, birthday, email) values ('Hermy', '1980-11-22', 'homannion1i@forbes.com');
insert into employee (name, birthday, email) values ('Hervey', '1972-01-17', 'hfrancescozzi1j@apple.com');
insert into employee (name, birthday, email) values ('Susi', '1997-03-18', 'sstigell1k@alexa.com');
insert into employee (name, birthday, email) values ('Fionna', '1999-11-03', 'fcoppeard1l@goo.gl');
insert into employee (name, birthday, email) values ('Nellie', '1983-03-13', 'nblandford1m@independent.co.uk');
insert into employee (name, birthday, email) values ('Rosabel', '1994-07-13', 'rboog1n@devhub.com');
insert into employee (name, birthday, email) values ('Nobie', '1967-05-31', 'nmaciejewski1o@auda.org.au');
insert into employee (name, birthday, email) values ('Derry', '1970-08-06', 'dhardware1p@weebly.com');
insert into employee (name, birthday, email) values ('Florri', '1992-07-22', 'foades1q@uol.com.br');
insert into employee (name, birthday, email) values ('Valina', '1961-06-03', 'vswaite1r@behance.net');
insert into employee (name, birthday, email) values ('Shana', '1981-04-10', 'srawne1s@zimbio.com');
insert into employee (name, birthday, email) values ('Euphemia', '1966-01-05', 'ematterson1t@live.com');
insert into employee (name, birthday, email) values ('Dudley', '1969-12-19', 'dabelson1u@blogger.com');
insert into employee (name, birthday, email) values ('Malena', '1963-01-10', 'mgrigorio1v@yellowbook.com');
insert into employee (name, birthday, email) values ('Gorden', null, 'gswinburn1w@hugedomains.com');
insert into employee (name, birthday, email) values ('Grace', '1963-03-08', 'ggonnely1x@woothemes.com');
insert into employee (name, birthday, email) values ('Sarajane', '1971-06-15', 'sgabel1y@nhs.uk');
insert into employee (name, birthday, email) values ('Euphemia', '1990-08-25', 'estockill1z@auda.org.au');
insert into employee (name, birthday, email) values ('Winny', '1989-03-16', 'wcorgenvin20@wordpress.com');
insert into employee (name, birthday, email) values ('Ella', '1969-07-07', 'eglassopp21@nasa.gov');
insert into employee (name, birthday, email) values ('Dilan', '1985-10-16', 'ddamiral22@nytimes.com');
insert into employee (name, birthday, email) values ('Freemon', '1976-02-16', 'fwanstall23@booking.com');
insert into employee (name, birthday, email) values ('Peri', '1961-12-15', 'pfries24@domainmarket.com');
insert into employee (name, birthday, email) values ('Kirsti', '1975-10-07', 'ktuffley25@barnesandnoble.com');
insert into employee (name, birthday, email) values ('Judi', '1999-05-20', 'jlefley26@ow.ly');
insert into employee (name, birthday, email) values ('Freida', '1986-01-22', 'fferroli27@histats.com');
insert into employee (name, birthday, email) values ('Francine', '1999-11-03', 'fpinnegar28@networkadvertising.org');
insert into employee (name, birthday, email) values ('Phylis', '1974-08-09', 'psherbourne29@google.ca');
insert into employee (name, birthday, email) values ('Carleton', '1966-11-15', 'cveillard2a@mapy.cz');
insert into employee (name, birthday, email) values ('Nap', '1995-02-16', 'nmckall2b@reddit.com');
insert into employee (name, birthday, email) values ('Margot', '1983-02-15', 'mlisciandri2c@mozilla.com');
insert into employee (name, birthday, email) values ('Taddeo', '1961-04-22', 'tceschini2d@123-reg.co.uk');
insert into employee (name, birthday, email) values ('Edith', null, 'etofanini2e@wired.com');
insert into employee (name, birthday, email) values ('Kendricks', null, 'kczyz2f@phoca.cz');
insert into employee (name, birthday, email) values ('Alasdair', '1968-01-17', 'atasseler2g@cyberchimps.com');
insert into employee (name, birthday, email) values ('Marietta', '1996-08-28', 'mshoebrook2h@house.gov');
insert into employee (name, birthday, email) values ('Dallon', null, 'dsink2i@google.nl');
insert into employee (name, birthday, email) values ('Roselia', '1987-11-21', 'rtrodd2j@sakura.ne.jp');
insert into employee (name, birthday, email) values ('Jacklin', '1966-12-07', 'jstuehmeyer2k@behance.net');
insert into employee (name, birthday, email) values ('Shalne', '1998-04-02', 'sskiplorne2l@msu.edu');
insert into employee (name, birthday, email) values ('Tamarah', '1994-11-16', 'tsayton2m@usda.gov');
insert into employee (name, birthday, email) values ('Tove', '1966-02-28', 'tdenziloe2n@psu.edu');
insert into employee (name, birthday, email) values ('Eve', '1977-06-16', 'egumm2o@usnews.com');
insert into employee (name, birthday, email) values ('Allegra', '1989-01-11', 'adigregorio2p@php.net');
insert into employee (name, birthday, email) values ('Consuela', null, 'ckingswood2q@mac.com');
insert into employee (name, birthday, email) values ('Jami', '1982-01-07', 'jcaras2r@uol.com.br');


3 = Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'Esin'
WHERE birthday = '1977-06-16';


UPDATE employee
SET name = 'Meryem',
	birthday = '1999-08-09',
	email = 'meryem@xmail.com'
WHERE id = 45;


UPDATE employee
SET email = 'barbie4@xmail.com'
WHERE id = 20;


UPDATE employee
SET email = 'consuela13@mail.com'
WHERE name = 'Consuela'


UPDATE employee
SET name = 'Anastasia'
WHERE email = 'rtrodd2j@sakura.ne.jp'


4 = Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE id = 47;

DELETE FROM employee
WHERE name = Kendricks;

DELETE FROM employee
WHERE email = 'tceschini2d@123-reg.co.uk';

DELETE FROM employee
WHERE birthday = '1987-11-21';

DELETE FROM employee
WHERE email = consuela13@mail.com
