# 코딩테스트 과제
안녕하십니까 김재현입니다.
코딩테스트 과제입니다.

# 셋팅법

# 테스트
  ## Table Create 쿼리문
  use employees;

create table `employees` . `ProductInfo`(
    `product_name` varchar(45) Not Null,
    `price` int,
    `register_date` date,
    `company` varchar(45),
    primary key(`Product_name`)
);

insert into productinfo values("비비드 크림 3종 세트", '20000', '2021-11-20', "(주)비비드");
select * from productinfo;

create table `employees`. `Registrar`(
	`company` varchar(45) not null,
    `ceo` varchar(45) ,
    `phone_number` varchar(45),
    primary key (`company`)
);

insert into registrar values("삼성", "이재용", "012-345-6789");
select * from registrar;

create table `employees`. `Customer`(
    `customer_name` varchar(45) NOT NULL,
    `phone_number` Varchar(30),
    primary Key (`customer_name`)
);
    
insert into Customer values('홍길동', '051-123-4**7');
select * from customer;

create table `employees`.`PurchaseInfo`(
	`productInfo` varchar(45),
    `customer_name` varchar(45),
    `price` int ,
    `date_of_purchase` date,
    `purchase_number` varchar(30)
);

insert into purchaseinfo values("비비드 크림","홍길동","30000","2020-05-26","207");
select * from purchaseinfo;
  
  

# 사용한 패키지
Ubuntu, MYSQL
