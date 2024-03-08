# SQL-Assignment-8

1.	CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

2.	
insert into employee (name, birthday, email) values ('Babbette', '1985-09-17', 'brogeon0@cargocollective.com');
insert into employee (name, birthday, email) values ('Seth', '1993-11-11', 'sjarmaine1@squidoo.com');
insert into employee (name, birthday, email) values ('Beatrix', '1984-03-03', 'bcisson2@disqus.com');
insert into employee (name, birthday, email) values ('Hobey', '1987-08-18', 'hsedgwick3@google.com');
insert into employee (name, birthday, email) values ('Linzy', '1989-12-01', 'lweld4@fda.gov');
insert into employee (name, birthday, email) values ('Yelena', '2008-10-22', 'yhaselhurst5@seesaa.net');
insert into employee (name, birthday, email) values ('Merrili', '1959-12-12', 'mcalyton6@hatena.ne.jp');
insert into employee (name, birthday, email) values ('Emmie', '1950-06-08', 'egarron7@netvibes.com');
insert into employee (name, birthday, email) values ('Milissent', '1972-10-15', 'mmurdie8@washington.edu');
insert into employee (name, birthday, email) values ('Reagen', '1975-06-21', 'rdundon9@themeforest.net');
insert into employee (name, birthday, email) values ('Paulita', '1996-09-29', 'pvanyukova@unc.edu');
insert into employee (name, birthday, email) values ('Rafaelita', '1986-07-05', 'rbuchamb@infoseek.co.jp');
insert into employee (name, birthday, email) values ('Wendell', '1967-02-27', 'wheikkinenc@blogger.com');
insert into employee (name, birthday, email) values ('Lemar', '1958-07-07', 'llelandd@fc2.com');
insert into employee (name, birthday, email) values ('Deina', '1998-01-11', 'dbroadwelle@bloglovin.com');
insert into employee (name, birthday, email) values ('Shani', '2002-06-08', 'sroggerf@cbslocal.com');
insert into employee (name, birthday, email) values ('Kyla', '1992-11-24', 'kjoselovitchg@baidu.com');
insert into employee (name, birthday, email) values ('Zandra', '1960-05-30', 'zlongstreethh@mozilla.org');
insert into employee (name, birthday, email) values ('Aloin', '2017-06-25', 'acopozioi@bbc.co.uk');
insert into employee (name, birthday, email) values ('Jakie', '2010-11-06', 'jvanhaultj@sourceforge.net');
insert into employee (name, birthday, email) values ('Elfrieda', '1989-05-26', 'epitkeathleyk@mashable.com');
insert into employee (name, birthday, email) values ('Gunar', '1951-09-11', 'gfitchewl@cnn.com');
insert into employee (name, birthday, email) values ('Garrek', '2022-09-16', 'gbriancem@addthis.com');
insert into employee (name, birthday, email) values ('Husain', '1955-01-23', 'hinfantinon@reddit.com');
insert into employee (name, birthday, email) values ('Gilbertina', '1972-07-25', 'gantonognolio@businessinsider.com');
insert into employee (name, birthday, email) values ('Chucho', '1964-08-08', 'cdeehanp@virginia.edu');
insert into employee (name, birthday, email) values ('Howard', '1993-03-19', 'hsortonq@themeforest.net');
insert into employee (name, birthday, email) values ('Warde', '1985-08-04', 'wwallettr@github.io');
insert into employee (name, birthday, email) values ('Consolata', '1952-04-01', 'crushmers@google.com.br');
insert into employee (name, birthday, email) values ('Mata', '1970-01-18', 'mdarwint@apple.com');
insert into employee (name, birthday, email) values ('Burnard', '1990-12-29', 'bklimashevichu@cbc.ca');
insert into employee (name, birthday, email) values ('Bil', '2016-05-20', 'bfranzettiv@admin.ch');
insert into employee (name, birthday, email) values ('Nilson', '1968-06-08', 'nhumesw@merriam-webster.com');
insert into employee (name, birthday, email) values ('Zacharie', '1955-11-08', 'zpedelx@webs.com');
insert into employee (name, birthday, email) values ('Ilene', '1970-12-30', 'ibucknery@ebay.com');
insert into employee (name, birthday, email) values ('Grange', '1997-12-15', 'gargonttz@hao123.com');
insert into employee (name, birthday, email) values ('Farly', '2002-02-14', 'fcostall10@macromedia.com');
insert into employee (name, birthday, email) values ('Gui', '1964-12-31', 'gshevlane11@slideshare.net');
insert into employee (name, birthday, email) values ('Jyoti', '1998-11-05', 'jnoke12@google.it');
insert into employee (name, birthday, email) values ('Bradan', '1974-06-13', 'bkewzick13@free.fr');
insert into employee (name, birthday, email) values ('Sibella', '1989-12-03', 'ssyder14@amazonaws.com');
insert into employee (name, birthday, email) values ('Tiffy', '1994-01-30', 'tleades15@exblog.jp');
insert into employee (name, birthday, email) values ('Ansell', '1987-07-16', 'aitzkowicz16@fda.gov');
insert into employee (name, birthday, email) values ('Vevay', '1957-05-17', 'vtomankiewicz17@topsy.com');
insert into employee (name, birthday, email) values ('Wallis', '2020-10-25', 'wgiocannoni18@dailymotion.com');
insert into employee (name, birthday, email) values ('Tim', '1990-03-30', 'tmeenehan19@boston.com');
insert into employee (name, birthday, email) values ('Bettina', '1965-01-09', 'bbalharry1a@ask.com');
insert into employee (name, birthday, email) values ('Minerva', '1960-08-17', 'mfloodgate1b@newyorker.com');
insert into employee (name, birthday, email) values ('Padraig', '1980-10-04', 'ptallach1c@merriam-webster.com');
insert into employee (name, birthday, email) values ('Marlane', '1980-12-11', 'mlugton1d@shop-pro.jp');

3.	UPDATE employee
SET name = 'Buket',
	birthday = '2001-11-11',
	email = 'buket.celik@gmail.com'
WHERE id IN (10,20,30,40,50);

4.	DELETE FROM employee
WHERE id = 15;
DELETE FROM employee
WHERE id IN (20,12);
DELETE FROM employee
WHERE id = 11;
DELETE FROM employee
WHERE id = 18;
DELETE FROM employee
WHERE id = 19;
