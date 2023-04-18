# odev8sql

1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

      CREATE TABLE employee (
          id INTEGER PRIMARY KEY,
       	  name VARCHAR(50) NOT NULL,
	        birthday DATE,
	        email VARCHAR (100)
       )
           
           
2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.



 insert into employee (id, name, birthday, email) values (1, 'Cordelie Fullegar', '1983/06/07', 'cfullegar0@aol.com');
insert into employee (id, name, birthday, email) values (2, 'Edik Fann', '1981/04/27', 'efann1@apache.org');
insert into employee (id, name, birthday, email) values (3, 'Thurston Thirlwell', '1978/03/20', 'tthirlwell2@blogger.com');
insert into employee (id, name, birthday, email) values (4, 'Wallis McClounan', '1999/12/22', 'wmcclounan3@state.tx.us');
insert into employee (id, name, birthday, email) values (5, 'Hamlin Pavel', '1980/05/01', 'hpavel4@networkadvertising.org');
insert into employee (id, name, birthday, email) values (6, 'Ebony Stuchbery', '1991/09/01', 'estuchbery5@vimeo.com');
insert into employee (id, name, birthday, email) values (7, 'Harbert Pykerman', '1985/07/02', 'hpykerman6@aboutads.info');
insert into employee (id, name, birthday, email) values (8, 'Shellie Grenville', '1965/05/19', 'sgrenville7@boston.com');
insert into employee (id, name, birthday, email) values (9, 'Davine Thickett', '1990/07/06', 'dthickett8@drupal.org');
insert into employee (id, name, birthday, email) values (10, 'Amandi Melhuish', '1968/01/21', 'amelhuish9@lycos.com');
insert into employee (id, name, birthday, email) values (11, 'Jesselyn Samuels', '1987/03/10', 'jsamuelsa@cbslocal.com');
insert into employee (id, name, birthday, email) values (12, 'Tilly Gahagan', '1977/12/24', 'tgahaganb@fc2.com');
insert into employee (id, name, birthday, email) values (13, 'Claiborne Card', '1989/01/13', 'ccardc@pinterest.com');
insert into employee (id, name, birthday, email) values (14, 'Dalila Dudding', '1977/12/03', 'dduddingd@about.com');
insert into employee (id, name, birthday, email) values (15, 'Paxton McNeice', '1978/01/15', 'pmcneicee@ifeng.com');
insert into employee (id, name, birthday, email) values (16, 'Brooke Leband', '1977/12/08', 'blebandf@columbia.edu');
insert into employee (id, name, birthday, email) values (17, 'Regine Jarred', '1991/06/11', 'rjarredg@constantcontact.com');
insert into employee (id, name, birthday, email) values (18, 'Randie Riggeard', '1982/03/17', 'rriggeardh@mashable.com');
insert into employee (id, name, birthday, email) values (19, 'Noak Follin', '1973/10/04', 'nfollini@shop-pro.jp');
insert into employee (id, name, birthday, email) values (20, 'Terrie Berdale', '1997/07/12', 'tberdalej@unesco.org');
insert into employee (id, name, birthday, email) values (21, 'Tasia Allenby', '1994/10/07', 'tallenbyk@prnewswire.com');
insert into employee (id, name, birthday, email) values (22, 'Shermy Phillips', '1970/02/17', 'sphillipsl@livejournal.com');
insert into employee (id, name, birthday, email) values (23, 'Seward Billison', '1962/04/12', 'sbillisonm@go.com');
insert into employee (id, name, birthday, email) values (24, 'Kesley Bennellick', '1960/11/02', 'kbennellickn@ftc.gov');
insert into employee (id, name, birthday, email) values (25, 'Perren Spandley', '1991/12/15', 'pspandleyo@bbb.org');
insert into employee (id, name, birthday, email) values (26, 'Maritsa Perfect', '1997/06/13', 'mperfectp@sbwire.com');
insert into employee (id, name, birthday, email) values (27, 'Juliann Esler', '1984/04/21', 'jeslerq@posterous.com');
insert into employee (id, name, birthday, email) values (28, 'Hanson Waddicor', '1963/01/09', 'hwaddicorr@free.fr');
insert into employee (id, name, birthday, email) values (29, 'Phoebe Oller', '1989/12/22', 'pollers@sina.com.cn');
insert into employee (id, name, birthday, email) values (30, 'Ysabel Conachy', '1997/06/09', 'yconachyt@netscape.com');
insert into employee (id, name, birthday, email) values (31, 'Ollie Lillecrop', '1984/03/03', 'olillecropu@usa.gov');
insert into employee (id, name, birthday, email) values (32, 'Genny Hurch', '1979/12/11', 'ghurchv@spotify.com');
insert into employee (id, name, birthday, email) values (33, 'Norina Sunderland', '1996/11/07', 'nsunderlandw@privacy.gov.au');
insert into employee (id, name, birthday, email) values (34, 'Othilia Paszak', '1963/03/08', 'opaszakx@ed.gov');
insert into employee (id, name, birthday, email) values (35, 'Swen O''Hingerty', '1998/06/27', 'sohingertyy@apple.com');
insert into employee (id, name, birthday, email) values (36, 'Westley Kirtley', '1996/01/06', 'wkirtleyz@privacy.gov.au');
insert into employee (id, name, birthday, email) values (37, 'Hasheem Wogdon', '1994/02/06', 'hwogdon10@wikimedia.org');
insert into employee (id, name, birthday, email) values (38, 'Revkah Playhill', '1993/10/07', 'rplayhill11@ed.gov');
insert into employee (id, name, birthday, email) values (39, 'Vernor Lindenstrauss', '1994/02/10', 'vlindenstrauss12@noaa.gov');
insert into employee (id, name, birthday, email) values (40, 'Claribel Shrimplin', '1967/05/20', 'cshrimplin13@bizjournals.com');
insert into employee (id, name, birthday, email) values (41, 'Lucita Reasce', '1961/01/21', 'lreasce14@jiathis.com');
insert into employee (id, name, birthday, email) values (42, 'Sigmund Burgoine', '1972/03/23', 'sburgoine15@smugmug.com');
insert into employee (id, name, birthday, email) values (43, 'Torrence Eskrigge', '1990/01/20', 'teskrigge16@alexa.com');
insert into employee (id, name, birthday, email) values (44, 'Lezley Mc Coughan', '1987/10/15', 'lmc17@ow.ly');
insert into employee (id, name, birthday, email) values (45, 'Bobbie Pallent', '1988/02/04', 'bpallent18@gizmodo.com');
insert into employee (id, name, birthday, email) values (46, 'Constantina Firebrace', '1978/07/21', 'cfirebrace19@sphinn.com');
insert into employee (id, name, birthday, email) values (47, 'Silva Halleybone', '1995/09/25', 'shalleybone1a@ovh.net');
insert into employee (id, name, birthday, email) values (48, 'Wally Matthiesen', '1960/04/28', 'wmatthiesen1b@google.ca');
insert into employee (id, name, birthday, email) values (49, 'Corabelle Hughland', '1984/10/24', 'chughland1c@ucla.edu');
insert into employee (id, name, birthday, email) values (50, 'Florry Talby', '1980/01/04', 'ftalby1d@omniture.com');  



3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

		--UPDATE employee SET name='Emel Tanman' WHERE id=8 ;
		--UPDATE employee SET name='Alp Tanman' WHERE name LIKE 'O%';
		--UPDATE employee SET birthday='2000-01-12' WHERE birthday > '1990-01-25';
		--UPDATE employee SET birthday='1995-11-12' WHERE name LIKE '___%t' ;
		--UPDATE employee SET email='tanmanemel@gmail.com' WHERE name='Emel Tanman' ;




4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

                --DELETE FROM employee WHERE id=4;
		--DELETE FROM employee WHERE id<=2;
		--DELETE FROM employee WHERE name LIKE 'P%y';
		--DELETE FROM employee WHERE name LIKE 'Le%';
		--DELETE FROM employee WHERE email LIKE 'a__l%';
