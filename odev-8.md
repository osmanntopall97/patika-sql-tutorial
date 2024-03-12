1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

    create table test (
	    id INT,
	    first_name VARCHAR(50),
	    last_name VARCHAR(50),
	    Birthday DATE,
	    email VARCHAR(100)
    );

2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

    insert into test (id, first_name, last_name, Birthday, email) values (1, 'Lambert', 'Lethbrig', '1972-06-17', 'llethbrig0@umich.edu');
    insert into test (id, first_name, last_name, Birthday, email) values (2, 'Wendie', 'Brightwell', '1976-11-07', 'wbrightwell1@craigslist.org');
    insert into test (id, first_name, last_name, Birthday, email) values (3, 'Morissa', 'Chettle', '1975-01-30', 'mchettle2@friendfeed.com');
    insert into test (id, first_name, last_name, Birthday, email) values (4, 'Robena', 'Lemar', '1979-04-27', 'rlemar3@myspace.com');
    insert into test (id, first_name, last_name, Birthday, email) values (5, 'Karyl', 'Brendish', '1984-03-27', 'kbrendish4@webs.com');
    insert into test (id, first_name, last_name, Birthday, email) values (6, 'Sheffie', 'Fawckner', '1983-07-22', 'sfawckner5@imdb.com');
    insert into test (id, first_name, last_name, Birthday, email) values (7, 'Grange', 'Braithwait', '1985-08-26', 'gbraithwait6@istockphoto.com');
    insert into test (id, first_name, last_name, Birthday, email) values (8, 'Inesita', 'Jack', '1979-12-08', 'ijack7@narod.ru');
    insert into test (id, first_name, last_name, Birthday, email) values (9, 'Glennie', 'Vogeler', '1973-02-02', 'gvogeler8@trellian.com');
    insert into test (id, first_name, last_name, Birthday, email) values (10, 'Alf', 'Yurov', '1998-10-01', 'ayurov9@4shared.com');
    insert into test (id, first_name, last_name, Birthday, email) values (11, 'Basilio', 'Coulston', '1987-11-09', 'bcoulstona@webs.com');
    insert into test (id, first_name, last_name, Birthday, email) values (12, 'Hector', 'O''Carmody', '1992-03-27', 'hocarmodyb@people.com.cn');
    insert into test (id, first_name, last_name, Birthday, email) values (13, 'Aleta', 'Ferrie', '1984-09-05', 'aferriec@google.it');
    insert into test (id, first_name, last_name, Birthday, email) values (14, 'Ynes', 'Foulcher', '1973-06-01', 'yfoulcherd@indiegogo.com');
    insert into test (id, first_name, last_name, Birthday, email) values (15, 'Marietta', 'Coale', '1989-01-10', 'mcoalee@tiny.cc');
    insert into test (id, first_name, last_name, Birthday, email) values (16, 'Frazier', 'Bigg', '1979-07-14', 'fbiggf@twitter.com');
    insert into test (id, first_name, last_name, Birthday, email) values (17, 'Dodi', 'Vittery', '1971-06-12', 'dvitteryg@wunderground.com');
    insert into test (id, first_name, last_name, Birthday, email) values (18, 'Hewie', 'Taks', '1979-06-29', 'htaksh@bravesites.com');
    insert into test (id, first_name, last_name, Birthday, email) values (19, 'Madeline', 'Del Checolo', '1976-07-23', 'mdelchecoloi@com.com');
    insert into test (id, first_name, last_name, Birthday, email) values (20, 'Packston', 'Bownde', '1973-04-10', 'pbowndej@newyorker.com');
    insert into test (id, first_name, last_name, Birthday, email) values (21, 'Terencio', 'Scollick', '1996-09-11', 'tscollickk@purevolume.com');
    insert into test (id, first_name, last_name, Birthday, email) values (22, 'Georgianne', 'Rodger', '1975-10-27', 'grodgerl@phoca.cz');
    insert into test (id, first_name, last_name, Birthday, email) values (23, 'Maribeth', 'Sarle', '1974-04-17', 'msarlem@google.com.br');
    insert into test (id, first_name, last_name, Birthday, email) values (24, 'Carlo', 'Pariso', '1986-05-19', 'cparison@mlb.com');
    insert into test (id, first_name, last_name, Birthday, email) values (25, 'Filip', 'Gregolin', '1979-08-02', 'fgregolino@topsy.com');
    insert into test (id, first_name, last_name, Birthday, email) values (26, 'Margaux', 'Rosenfelder', '1978-03-29', 'mrosenfelderp@washington.edu');
    insert into test (id, first_name, last_name, Birthday, email) values (27, 'Debby', 'Huyhton', '1979-05-12', 'dhuyhtonq@scribd.com');
    insert into test (id, first_name, last_name, Birthday, email) values (28, 'Cris', 'Chater', '1989-05-08', 'cchaterr@wiley.com');
    insert into test (id, first_name, last_name, Birthday, email) values (29, 'Rickey', 'Tindall', '1991-10-26', 'rtindalls@merriam-webster.com');
    insert into test (id, first_name, last_name, Birthday, email) values (30, 'Ennis', 'Pidduck', '1983-07-03', 'epidduckt@vk.com');
    insert into test (id, first_name, last_name, Birthday, email) values (31, 'Engelbert', 'Ordidge', '1978-03-15', 'eordidgeu@google.com');
    insert into test (id, first_name, last_name, Birthday, email) values (32, 'Padget', 'Reedshaw', '1989-10-31', 'preedshawv@epa.gov');
    insert into test (id, first_name, last_name, Birthday, email) values (33, 'Kipp', 'Mochan', '1973-11-24', 'kmochanw@storify.com');
    insert into test (id, first_name, last_name, Birthday, email) values (34, 'Ingrid', 'Houldey', '1973-09-28', 'ihouldeyx@fastcompany.com');
    insert into test (id, first_name, last_name, Birthday, email) values (35, 'Obidiah', 'Coxhead', '1988-09-29', 'ocoxheady@elegantthemes.com');
    insert into test (id, first_name, last_name, Birthday, email) values (36, 'Benson', 'De Filippo', '1985-11-29', 'bdefilippoz@dailymail.co.uk');
    insert into test (id, first_name, last_name, Birthday, email) values (37, 'Edan', 'Salzberg', '1970-07-27', 'esalzberg10@cbsnews.com');
    insert into test (id, first_name, last_name, Birthday, email) values (38, 'Dottie', 'Shrawley', '1976-11-08', 'dshrawley11@last.fm');
    insert into test (id, first_name, last_name, Birthday, email) values (39, 'Valida', 'Pellingar', '1986-08-06', 'vpellingar12@washington.edu');
    insert into test (id, first_name, last_name, Birthday, email) values (40, 'Natassia', 'Karsh', '1992-06-04', 'nkarsh13@pcworld.com');
    insert into test (id, first_name, last_name, Birthday, email) values (41, 'Lorens', 'Leadstone', '1972-09-28', 'lleadstone14@elegantthemes.com');
    insert into test (id, first_name, last_name, Birthday, email) values (42, 'Mohandas', 'Van Hove', '1978-01-24', 'mvanhove15@ca.gov');
    insert into test (id, first_name, last_name, Birthday, email) values (43, 'Gae', 'Caton', '1972-02-26', 'gcaton16@mapquest.com');
    insert into test (id, first_name, last_name, Birthday, email) values (44, 'Zacharias', 'Courtese', '1988-10-21', 'zcourtese17@weibo.com');
    insert into test (id, first_name, last_name, Birthday, email) values (45, 'Ingrid', 'Orridge', '1978-02-27', 'iorridge18@sohu.com');
    insert into test (id, first_name, last_name, Birthday, email) values (46, 'Emili', 'Swarbrick', '1978-10-20', 'eswarbrick19@unc.edu');
    insert into test (id, first_name, last_name, Birthday, email) values (47, 'Donelle', 'Haddeston', '1988-05-31', 'dhaddeston1a@ted.com');
    insert into test (id, first_name, last_name, Birthday, email) values (48, 'Hadlee', 'Kirkland', '1997-08-23', 'hkirkland1b@dot.gov');
    insert into test (id, first_name, last_name, Birthday, email) values (49, 'Celesta', 'Pikhno', '1972-02-02', 'cpikhno1c@japanpost.jp');
    insert into test (id, first_name, last_name, Birthday, email) values (50, 'Bink', 'Vigus', '1994-12-03', 'bvigus1d@noaa.gov');

3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

    UPDATE test
    SET first_name = 'Halil',
        last_name = 'Dervis',
        birthday = '1990-10-24',
        email = 'halil@dervis.com'
    WHERE id = 1;

    UPDATE test
    SET id = 8,
        last_name = 'Jackie',
        birthday = '1994-10-24',
        email = 'Inesita@jackie.com'
    WHERE first_name = 'Inesita';

    UPDATE test
    SET id = 12,
        first_name = 'Hercules',
        birthday = '1994-10-24',
        email = 'Hercules@yurov.com'
    WHERE last_name = 'Yurov';

    UPDATE test
    SET id = 28,
        first_name = 'Cristian',
        last_name = 'Bale',
        email = 'Cristian@bale.com'
    WHERE birthday = '1989-05-08';

    UPDATE test
    SET id = 37,
        first_name = 'Osman',
        last_name = 'Topal',
        birthday = '1997-10-14'
    WHERE email = 'esalzberg10@cbsnews.com';

4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

    DELETE FROM test
    WHERE id = 1;

    DELETE FROM test
    WHERE first_name = 'Osman';

    DELETE FROM test
    WHERE last_name = 'Houlday';

    DELETE FROM test
    WHERE birthday = '1997-08-23';

    DELETE FROM test
    WHERE email = 'iorridge18@sohu.com';