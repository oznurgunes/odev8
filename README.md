1)test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.<br><code>
  create table employee ( id  integer primary key,
					  name varchar(50) not null,
					  birthday  varchar(50),
					  email varchar(100)
					  );</code><br>
 2)Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.<br><code>
  select* from employee;
  insert into employee (id, name, birthday, email) values (1, 'Quintin Russen', '2017-05-20', 'qrussen0@booking.com');
insert into employee (id, name, birthday, email) values (2, 'Ag Troyes', '2017-06-02', 'atroyes1@ca.gov');
insert into employee (id, name, birthday, email) values (3, 'Car Netherwood', '2012-02-20', 'cnetherwood2@usatoday.com');
insert into employee (id, name, birthday, email) values (4, 'Marybelle Ivankov', '2016-04-14', 'mivankov3@newsvine.com');
insert into employee (id, name, birthday, email) values (5, 'Hannie Pawels', '1993-08-17', 'hpawels4@wix.com');
insert into employee (id, name, birthday, email) values (6, 'Bessie Wolvey', '1996-12-30', 'bwolvey5@drupal.org');
insert into employee (id, name, birthday, email) values (7, 'Hadley Pieroni', '1998-09-29', 'hpieroni6@webmd.com');
insert into employee (id, name, birthday, email) values (8, 'Francisco Clemitt', '1993-11-08', 'fclemitt7@wsj.com');
insert into employee (id, name, birthday, email) values (9, 'Bo Enderson', null, null);
insert into employee (id, name, birthday, email) values (10, 'Lilli Stanlake', '1998-12-13', 'lstanlake9@cbc.ca');
insert into employee (id, name, birthday, email) values (11, 'Mel Wheatland', '2020-04-14', 'mwheatlanda@archive.org');
insert into employee (id, name, birthday, email) values (12, 'Muriel Lonsbrough', '1999-11-07', 'mlonsbroughb@si.edu');
insert into employee (id, name, birthday, email) values (13, 'Becki Attiwill', '1997-10-18', 'battiwillc@washington.edu');
insert into employee (id, name, birthday, email) values (14, 'Mavra Janaszkiewicz', '2014-11-20', 'mjanaszkiewiczd@blogs.com');
insert into employee (id, name, birthday, email) values (15, 'Charita Eliasen', '2007-08-06', 'celiasene@bloglovin.com');
insert into employee (id, name, birthday, email) values (16, 'Ranee Freeland', '2000-10-29', 'rfreelandf@ft.com');
insert into employee (id, name, birthday, email) values (17, 'Boote Fucher', '2013-12-24', 'bfucherg@unc.edu');
insert into employee (id, name, birthday, email) values (18, 'Garner Raddenbury', '1996-09-10', 'graddenburyh@google.ru');
insert into employee (id, name, birthday, email) values (19, 'Debby Cormode', '1998-05-21', 'dcormodei@senate.gov');
insert into employee (id, name, birthday, email) values (20, 'Farand Gowen', '2019-03-09', 'fgowenj@chicagotribune.com');
insert into employee (id, name, birthday, email) values (21, 'Marie Collimore', '1990-11-08', 'mcollimorek@wufoo.com');
insert into employee (id, name, birthday, email) values (22, 'Catherine Massel', '2009-01-13', 'cmassell@businesswire.com');
insert into employee (id, name, birthday, email) values (23, 'Annora Mahon', '1998-08-22', 'amahonm@unesco.org');
insert into employee (id, name, birthday, email) values (24, 'Joelle O''Nions', '2012-01-01', 'jonionsn@whitehouse.gov');
insert into employee (id, name, birthday, email) values (25, 'Barbara-anne Brien', null, null);
insert into employee (id, name, birthday, email) values (26, 'Kipp Alan', '2019-07-19', 'kalanp@chicagotribune.com');
insert into employee (id, name, birthday, email) values (27, 'Garrett Wadeson', '2003-01-18', 'gwadesonq@csmonitor.com');
insert into employee (id, name, birthday, email) values (28, 'Sonja Nial', '1997-05-01', 'snialr@seattletimes.com');
insert into employee (id, name, birthday, email) values (29, 'Monique Spick', '2019-02-28', 'mspicks@1688.com');
insert into employee (id, name, birthday, email) values (30, 'Ahmed Billows', '2007-02-16', 'abillowst@house.gov');
insert into employee (id, name, birthday, email) values (31, 'Puff Grzeszczak', null, null);
insert into employee (id, name, birthday, email) values (32, 'Fiona Huscroft', '1991-09-10', 'fhuscroftv@smh.com.au');
insert into employee (id, name, birthday, email) values (33, 'Jobey Thirtle', '1999-04-27', 'jthirtlew@nymag.com');
insert into employee (id, name, birthday, email) values (34, 'Annaliese Duffill', '2006-03-28', 'aduffillx@yahoo.com');
insert into employee (id, name, birthday, email) values (35, 'Smitty Bewfield', '1998-03-20', 'sbewfieldy@people.com.cn');
insert into employee (id, name, birthday, email) values (36, 'Osmond Treat', null, null);
insert into employee (id, name, birthday, email) values (37, 'Dacey Peers', '2010-02-18', 'dpeers10@walmart.com');
insert into employee (id, name, birthday, email) values (38, 'Calli Bastow', '2006-10-08', 'cbastow11@storify.com');
insert into employee (id, name, birthday, email) values (39, 'Maribeth Poli', '2010-01-06', 'mpoli12@printfriendly.com');
insert into employee (id, name, birthday, email) values (40, 'Tirrell Gussie', '1993-05-31', 'tgussie13@fc2.com');
insert into employee (id, name, birthday, email) values (41, 'Frants Bellelli', '1999-11-24', 'fbellelli14@macromedia.com');
insert into employee (id, name, birthday, email) values (42, 'Jessie Mitcheson', '1998-04-06', 'jmitcheson15@macromedia.com');
insert into employee (id, name, birthday, email) values (43, 'Gustave Brookzie', '2020-07-25', 'gbrookzie16@tmall.com');
insert into employee (id, name, birthday, email) values (44, 'Antin Walak', '2003-01-30', 'awalak17@blogtalkradio.com');
insert into employee (id, name, birthday, email) values (45, 'Artair Bruggen', '2010-01-05', 'abruggen18@sciencedaily.com');
insert into employee (id, name, birthday, email) values (46, 'Burt Goold', '1997-06-23', 'bgoold19@trellian.com');
insert into employee (id, name, birthday, email) values (47, 'Bendix McLanaghan', '1993-10-26', 'bmclanaghan1a@qq.com');
insert into employee (id, name, birthday, email) values (48, 'Adrian Crips', '2010-03-23', 'acrips1b@exblog.jp');
insert into employee (id, name, birthday, email) values (49, 'Omar Brunke', '2011-09-08', 'obrunke1c@twitpic.com');
insert into employee (id, name, birthday, email) values (50, 'Kerwin Hatherley', '2004-09-20', 'khatherley1d@vkontakte.ru');</code><br>
3)Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.<br><code>
  update employee
   set name = 'Ayşe Yılmaz',
       birthday = '1999/03/07',
	   email='ayseyılmaz@gmail.com'
where id=5;</code><br>
 4)Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.<br><code>
  delete from employee
where id=3;
  delete from employee
where name ='Ag Troyes';


  
