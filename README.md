create database bankSystem;
use bankSystem;
create table signup(form_no varchar(40),name varchar(40),father_name varchar(30), DBO varchar(30),gender varchar(30), email varchar(60), martial_status varchar(30),address varchar(100),city varchar(30),pincode varchar(30), state varchar(50))
select* from signup;
drop table signup;



create table signuptwo(form_no varchar(40), religion varchar(40),category varchar(30), income varchar(30),eduction varchar(30), occupation varchar(60), pan varchar(30),adhar varchar(100),seniorcitizon varchar(30),existing_account varchar(30))
select* from signuptwo;

create table signupthree(form_no varchar(40), accoutntTtype varchar(40),card_no varchar(40), pin varchar(40),facility varchar(300))
select* from signupthree;

create table login(form_no varchar(40), card_no varchar(40), pin varchar(40));
select* from login
