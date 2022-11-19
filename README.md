# basic-banking-system
As I started a new position as an intern in sparks foundation. I choosed a BASIC BANKING SYSTEM project and...here is the code of my task 
#createuser
button,input {
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  letter-spacing: 1.4px;
}
.background {
  width: 100%;
  display: flex;
}

.container {
  flex: 0 1 700px;
  width: 100%;
  margin: auto;
  padding: 10px;
}

.screen {
  position: relative;
  background: #d9d9d9;
  border-radius: 15px;
  box-shadow: 5px 10px 10px rgba(0, 0, 0, .25);
}

.screen-header {
  display: flex;
  align-items: center;
  padding: 10px 20px;
  background: #7B8788;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
}

.screen-header-right {
  display: flex;
}

.screen-header-ellipsis {
  width: 5px;
  height: 5px;
  margin-left: 3px;
  border-radius: 8px;
  background: #d9d9d9;
}

.screen-body {
  display: flex;
}

.screen-body-item {
  flex: 1;
  padding: 50px;
}
.app-form-group {
  margin-bottom: 15px;
}

.app-form-group.button {
  margin-bottom: 0;
  text-align: right;
  position: absolute;
  bottom: 30px;
  right:40px;
}

.app-form-control{
  width: 100%;
  padding: 10px 0;
  background: none;
  border: none;
  border-bottom: 1px solid #4C4B4B;
  color: #4C4B4B;
  font-size: 14px;
  outline: none;
  transition: border-color .2s;
}

.app-form-control::placeholder {
  color: #666;
}

.app-form-control:focus {
  border-bottom-color: #4C4B4B;
}

.app-form-button {
  background: none;
  border: none;
  margin-left: 20px;
  color: #666;
  font-size: 14px;
  cursor: pointer;
  outline: none;
}

.app-form-button:hover {
  color: #262626;
}

@media screen and (max-width: 520px) {
  *{
    letter-spacing:1px;
  }
  .container{
    margin-left: 20px;
    margin-right: 20px;
    margin-bottom: 40px;
  }
  .screen-body {
    flex-direction: column;
  }

  .screen-body-item.left {
    margin-bottom: 50px;
  }
  .app-form-button{
    margin-top:5px;
  }
}

@media screen and (max-width: 600px) {
  .screen-body {
    padding: 40px;
  }

  .screen-body-item {
    padding: 0;
  }
}



#navbar
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@600&display=swap');
.nav-link{
	margin-right: 15px;
background-color:red;
	color:#2F363F;
	letter-spacing: 0.5px;
	transition: 0.5s;
}
.navbar-brand{
	color: red;
	letter-spacing: 0.5px;
}
h2{
	color: #4C4B4B;
	letter-spacing: 0.5px;
	font-family: raleway;
}


#style
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}
.intro {
  background: #eaf0f1;
}
h1 {
  color: #4c4b4b;
  font-weight: bold;
  transition: 0.5s;
}
h3 {
  color: #2f363f;
}
button {
  border: none;
  padding: 10px;
  background: #7b8788;
  color: white;
  letter-spacing: 1.5px;
  font-size: 15px;
  transition: 0.5s;
}
button:hover,
h1:hover {
  transform: scale(1.1);
}
button:hover {
  background-color: #4c4b4b;
}
footer {
  color: #586776;
  background-color: #eaf0f1;
  letter-spacing: 0.5px;
}
footer p {
  margin: 0;
  font-size: 15px;
}
@media only screen and (orientation: portrait) {
  .intro {
    display: flex;
    flex-direction: column-reverse;
  }
  h1 {
    font-size: 30px;
  }
  .act {
    padding-bottom: 100px;
  }
}


#styles
body{
    margin:0px;
    padding: 0px;
    font-family: calibri;
}
*{
    box-sizing: border-box;
}
ul{
    list-style: none;
}
a{
    text-decoration: none;
}
button{
    outline: none;
    border: none;
}
input{
    outline: none;
    border: none;
}
.main{

    width:100%;
    height:768px;
    position: relative;
}
.logo img{
    height: 80px;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 0px 30px;
    background-color:skyblue;
    box-shadow: 2px 2px 20px rgba(255, 151, 103, 0.164);
    z-index: 1;
    width:100%;
    position: fixed;
    left: 0px;
    top: 0px;
}
nav ul{
    display: flex;
    margin:0px;
    padding: 0px;
}
nav ul li a{
    height:40px;
    line-height: 43px;
    margin: 8px;
    padding: 0px 10px;
    display: flex;
    font-size: 0.9rem;
    text-transform: uppercase;
    font-weight: 400;
    color:#111;
    letter-spacing: 1px;
    transition: 0.4s ease-in-out;
}
.active{
    background-color: #F14D5D;
    color: #fff;
}
nav ul li a:hover{
    border-radius: 5px;
    background-color: #F14D5D;
    color:#fff;
    box-shadow: 5px 10px 30px rgba(219, 74, 6, 0.5);
    transition: all ease 0.2s;
}
.home-content{
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: absolute;
    left: 50%;
    top:50%;
    transform: translate(-50%,-50%);
    width:90%;

}
.home-img{
    width:500px;
    height:400px;
    margin:20px;
}
.home-img img{
    width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: center;
}
.home-text{
    width:500px;
    margin: 20px;
}
.home-text h1{
    font-size: 3.5rem;
    line-height: 55px;
    color:#22252e;
    letter-spacing: 1px;
    font-weight: 700;
    margin: 0px;
}
.home-text p{
    font-size: 1rem;
    color:#777474;
}
.home-text span{
    color: #F14D5D;
    text-decoration: underline;
}
.main-login{
    width:120px;
    height:40px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #F14D5D;
    color:#fff;
    box-shadow: 5px 10px 30px rgba(219, 74, 6, 0.5);
    text-transform: uppercase;
    transition: 0.3s ease-in-out;
}
.main-login:hover{
    background-color: #F14D5D;
    transition: all ease 0.3s;
}
.arrow{
    align-self: end;
    width:50%;
    border-right: 1px solid #F14D5D;
    height: 20%;
    margin-bottom:20em ;
    position: absolute;
    bottom: 5px;
    right: 70px;
    animation: arrow-animation ease 1.5s;

}
.arrow::after{
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 11px 11px 0px 11px;
    border-color: #F14D5D transparent transparent transparent;
    right: -0.7em;
    bottom: -2px;
}
.scroll{
    position: absolute;
    bottom: 260px;
    right:55px;
    font-weight: 600;
}
@keyframes arrow-animation{
    0%{
        bottom: 70px;
        opacity: 0.2;
    }
    100%{
        bottom: 5px;
        opacity: 1;
    }
}
.services{
    background-size: 1000px;
    background-position: center;
}
.services-heading{
    margin-top: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
}
.services-heading h2{
    line-height: 55px;
    font-size: 2.2rem;
    color:#22252e;
    letter-spacing: 1px;
    font-weight: 700;
    margin: 0px;
}
.services-heading p{
    font-size: 1rem;
    color:#777474;
    width:50%;
}
.box-container{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    margin: 20px 30px;
}
.box{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width:300px;
    height: 400px;
    text-align: center;
    box-shadow: 2px 2px 20px rgba(90,118,253,0.15);
    border-radius: 10px;
    background-color: #fff;
    margin: 20px;
    flex-grow: 1;
}
.box img{
    height:50px;
    margin:10px;
}
.box font{
    font-size: 1.5rem;
    color: #22252e;
    letter-spacing: 1px;
    font-weight: 700;
}
.box p{
    font-size: 1rem;
    color: #777474;
    display: block;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 500px;
}
.box a{
    width:150px;
    height:40px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 2px solid #5a76fd;
    text-transform: uppercase;
    margin: auto;
    border-radius: 5px;
    font-weight: 600;
    font-size: 0.9rem;
    color:#5a76fd;
    margin:0px;
}
.box a:hover{
    background-color: #5a76fd;
    color:#fff;
    box-shadow: 5px 10px 30px rgba(90,118,253,0.5);
    transition: all ease 0.3s;
}

.box{
    width:200px;
    height: 400px;
    background-color: #ffffff;
    box-shadow: 2px 2px 30px rgba(0,0,0,0.05);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    border-radius: 10px;
    margin: 20px;
    position: relative;
}
.about{

    width:100%;
    height:768px;
    position: relative;
}
.about-content{
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: absolute;
    left: 50%;
    top:50%;
    transform: translate(-50%,-50%);
    width:90%;

}
.about-img{
    width:500px;
    height:400px;
    margin:20px;
}
.about-img img{
    width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: center;
}
.about-text{
    width:500px;
    margin: 20px;
}
.about-text h1{
    font-size: 3.5rem;
    line-height: 55px;
    color:#22252e;
    letter-spacing: 1px;
    font-weight: 700;
    margin: 0px;
}
.about-text p{
    font-size: 1rem;
    color:#777474;
}
.about-text span{
    color: #F14D5D;
    text-decoration: underline;
}
.about-login{
    width:120px;
    height:40px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f54417;
    color:#fff;
    box-shadow: 5px 10px 30px rgba(219, 74, 6, 0.5);
    text-transform: uppercase;
    transition: 0.3s ease-in-out;
}
.about-login:hover{
    background-color: #F14D5D;
    transition: all ease 0.3s;
}
.section-5-text{
    text-align: center;
    padding-bottom: 40px;
}
.section-5-text h1{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 2.5rem;
line-height: 47px;
color: #000000;
}
.section-5-text p{
    font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 1rem;
line-height: 21px;
color: #545454;
}
.section-5-text-btn{
    margin-top: 90px;
    margin-bottom: 60px;
}
.section-5-text-btn input{
    width: 30%;
height: 53px;
border: none;
outline: none;
font-size:20px;
background: #F3F3F3;
box-shadow: 5px 10px 30px rgba(219, 74, 6, 0.5);
padding-left: 20px;
}
.section-5-text-btn button{
    background: #fd0000;
    width: 221px;
height: 53px;
margin-left: 15px;
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 21px;
text-align: center;

color: #FFFFFF;
}
footer{
    width:100%;
    text-align: center;
    padding: 0px 5%;
    border-top: 1px solid rgba(231, 9, 9, 0.2);
}
footer a,
footer p{
    color:#000000;
}
nav .menu-btn{
    display: none;
}
@media(max-width:1100px){
    nav{
        justify-content: space-between;
        height: 65px;
    }
    .menu{
        display: none;
        position: absolute;
        top: 65px;
        left: 0px;
        background-color: #fff;
        border-bottom: 4px solid #F14D5D;
        width:100%;
    }
    .menu li{
        width:100%;
    }
    nav .menu li a{
        width:100%;
        height: 40px;
        justify-content: center;
        align-items: center;
        margin:0px;
        padding: 25px;
        border:1px solid rgba(38,38,38,0.03);
    }
    nav .menu-icon{
        cursor: pointer;
        float: right;
        padding: 28px 20px;
        position: relative;
        user-select: none;
    }
    nav .menu-icon .nav-icon{
        background-color: #333333;
        display: block;
        height: 2px;
        position: relative;
        transition: background 0.2s ease-out;
        width:18px;
    }
    nav .menu-icon .nav-icon:before,
    nav .menu-icon .nav-icon:after{
        background: #333333;
        content: '';
        display: block;
        height: 100%;
        position: absolute;
        transition: all ease-out 0.2s;
        width:100%;
    }
    nav .menu-icon .nav-icon:before{
        top: 5px;
    }
    nav .menu-icon .nav-icon:after{
        top:-5px;
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon{
        background: transparent;
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon:before{
        transform: rotate(-45deg);
        top: 0;
    }
    nav .menu-btn:checked ~ .menu-icon .nav-icon:after{
        transform: rotate(45deg);
        top: 0;
    }
    nav .menu-btn{
        display: none;
    }
    nav .menu-btn:checked ~ .menu{
        display: block;
    }
    .home-img{
        display: none;
    }
    .home-text{
        width:100%;
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        height: 45vh;
        margin: 0px;
    }
    .home-content{
        text-align: center;
        width:100%;
        margin:0px;
        position: static;
        transform: translate(0px,70px);
        box-shadow: 2px 2px 30px rgba(255, 102, 55, 0.178);
    }
    .home-text h1{
        color:rgb(0, 0, 0);
        padding: 0px 20px;
        font-size: 2.5rem;
    }
    .home-text p{
        color:rgba(32, 32, 32, 0.85);
        margin: 10px 0px 20px 0px;
        width:50%;
    }
    
    .about-img{
        display: none;
    }
    .about-text{
        width:100%;
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        height: 45vh;
        margin: 0px;
    }
    .about-content{
        text-align: center;
        width:100%;
        margin:0px;
        position: static;
        transform: translate(0px,70px);
        box-shadow: 2px 2px 30px rgba(255, 102, 55, 0.178);
    }
    .about-text h1{
        color:rgb(0, 0, 0);
        padding: 0px 20px;
        font-size: 2.5rem;
    }
    .about-text p{
        color:rgba(32, 32, 32, 0.85);
        margin: 10px 0px 20px 0px;
        width:50%;
    }
    
    .arrow{
        height: 70px;
    }
   
   .main{
  
        padding: 75px 0px 0px 0;
        background: url('images/hero-bg.png') no-repeat center center;
        background-size: cover;
        height: 900px;
   }.arrow{
       left: 2%;
       margin-bottom: 15em;
   }.scroll{
       left: 48%;
       bottom: 200px;
   }
}
@media(max-width:720px){
    .home-text p{
        width:70%;
        text-align: center;
    }
    .home-content h1{
        font-size: 1.9rem;
        padding: 10px 10px;
        line-height: 30px;
    }
    .about-text p{
        width:70%;
        text-align: center;
    }
    .about-content h1{
        font-size: 1.9rem;
        padding: 10px 10px;
        line-height: 30px;
    }
    .services{
        margin-top: -120px;
    }
    .services-heading{
        margin:20px;

    }
    .services-heading h2{
        font-size: 1.7rem;
        line-height: 40px;
    }
    .services-heading p{
        width:100%;
    }
    .box{
        width:100%;
        margin: 20px 0px !important;
        padding: 0px 20px;
        flex-grow: 1;
    }
    .box img{
        height: 100px;
        width:100%;
        object-fit: contain;
    }
    .section-5-text{
        margin-top: -250px;
    }
    .section-5-text-btn input{
        width: 80%;
    }
    .section-5-text-btn button{
        margin-top:20px;
    }
    footer p,a{
        font-size: 0.9rem;
        text-align: center;
    }
    footer{
        padding: 0px 10px;
    }
}


#table
*{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	font-family: sans-serif;
}
h2{
	font-size: 40px;
}
table{
	letter-spacing: 1.2px;
}
td{
	text-align: center;
}
button{
	border:none;
	background: #d9d9d9;
    transition: 1s;
}
@media only screen and (orientation: portrait){
	*{
		letter-spacing: 1px;
	}
}


#01projectinfo
**Log on to codeastro.com for more projects!***

**Database Name: banksysphp**

**Developed by Ayush Prajapati**

**Recommended PHP Version 5.6.3, 7.4.12**


#banksyphp
-- phpMyAdmin SQL Dump
-- version 4.6.5.2
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: May 14, 2021 at 04:35 PM
-- Server version: 5.6.21
-- PHP Version: 5.6.3

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `banksysphp`
--

-- --------------------------------------------------------

--
-- Table structure for table `transaction`
--

CREATE TABLE `transaction` (
  `sno` int(3) NOT NULL,
  `sender` text NOT NULL,
  `receiver` text NOT NULL,
  `balance` int(8) NOT NULL,
  `datetime` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `transaction`
--

INSERT INTO `transaction` (`sno`, `sender`, `receiver`, `balance`, `datetime`) VALUES
(1, 'Christine Moore', 'Evelyn Kent', 51000, '2021-05-14 14:29:15'),
(2, 'Willbert Flyn', 'Keith McKay', 25000, '2021-05-14 18:40:51'),
(3, 'Natalie Cloutier', 'Thomas Greenwood', 5000, '2021-05-14 19:16:56'),
(4, 'Thomas Greenwood', 'Natalie Cloutier', 26950, '2021-05-14 19:31:07'),
(5, 'Matthew Ingalls', 'Kelly Wilkins', 7510, '2021-05-14 20:15:14'),
(6, 'Kelly Wilkins', 'Michelle Cruz', 35100, '2021-05-14 20:15:47'),
(7, 'Thomas Greenwood', 'Keith McKay', 3150, '2021-05-14 20:16:51');

-- --------------------------------------------------------

--
-- Table structure for table `users`
--

CREATE TABLE `users` (
  `id` int(3) NOT NULL,
  `name` text NOT NULL,
  `email` varchar(30) NOT NULL,
  `gender` varchar(155) NOT NULL,
  `balance` int(8) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

--
-- Dumping data for table `users`
--

INSERT INTO `users` (`id`, `name`, `email`, `gender`, `balance`) VALUES
(1, 'Cassie Perkins', 'cassiep@gmail.com', 'Female', 62500),
(2, 'Keith McKay', 'keithmc@gmail.com', 'Male', 40650),
(3, 'Michelle Cruz', 'cruzmch@gmail.com', 'Female', 113750),
(4, 'Willbert Flyn', 'willbertfl@gmail.com', 'Male', 100005),
(5, 'Natalie Cloutier', 'natcloutier@gmail.com', 'Female', 127350),
(6, 'Evelyn Kent', 'evelynkent@gmail.com', 'Female', 81000),
(7, 'John Russel', 'russelj@gmail.com', 'Male', 69005),
(8, 'Virginia Hopkins', 'virginhop@gmail.com', 'Female', 210300),
(9, 'Christine Moore', 'christine@gmail.com', 'Female', 99000),
(10, 'Thomas Greenwood', 'thomasgr@gmail.com', 'Male', 40000),
(19, 'Matthew Ingalls', 'matthewlls@gmail.com', 'Male', 40000),
(20, 'Kelly Wilkins', 'wilkelly@gmail.com', 'Female', 29610);

--
-- Indexes for dumped tables
--

--
-- Indexes for table `transaction`
--
ALTER TABLE `transaction`
  ADD PRIMARY KEY (`sno`);

--
-- Indexes for table `users`
--
ALTER TABLE `users`
  ADD PRIMARY KEY (`id`);

--
-- AUTO_INCREMENT for dumped tables
--

--
-- AUTO_INCREMENT for table `transaction`
--
ALTER TABLE `transaction`
  MODIFY `sno` int(3) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=8;
--
-- AUTO_INCREMENT for table `users`
--
ALTER TABLE `users`
  MODIFY `id` int(3) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=22;
/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;


#01 project info
**Log on to codeastro.com for more projects!***

**Database Name: banksysphp**

**Developed by Ayush Prajapati**

**Recommended PHP Version 5.6.3, 7.4.12**


#config.php
<?php

	$servername = "localhost";
	$username = "root";
	$password = "";
	$dbname = "banksysphp";

	$conn = mysqli_connect($servername, $username, $password, $dbname);

	if(!$conn){
		die("Could not connect to the database due to the following error --> ".mysqli_connect_error());
	}
  
  
  
  #createuser.php
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create User</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">
    <link rel="stylesheet" type="text/css" href="css/createuser.css">
</head>

<body style="background-color : #ececec;">
<?php
    include 'config.php';
    if(isset($_POST['submit'])){
    $name=$_POST['name'];
    $email=$_POST['email'];
    $gender=$_POST['gender'];
    $balance=$_POST['balance'];
    $sql="insert into users(name,email,gender,balance) values('{$name}','{$email}','{$gender}','{$balance}')";
    $result=mysqli_query($conn,$sql);
    if($result){
               echo "<script> alert('User has been created!');
                               window.location='transfermoney.php';
                     </script>";
                    
    }
  }
?>

<?php
  include 'navbar.php';
?>

        <h2 class="text-center pt-4" style="color : #6c757d;">Create a User</h2>
        <br>

  <div class="background">
  <div class="container">
    <div class="screen">
      <div class="screen-header">
        <div class="screen-header-right">
          <div class="screen-header-ellipsis"></div>
          <div class="screen-header-ellipsis"></div>
          <div class="screen-header-ellipsis"></div>
        </div>
      </div>
      <div class="screen-body">
        <div class="screen-body-item left">
          <img class="img-fluid" src="img/user3.jpg" style="border: none; border-radius: 10%;">
        </div>
        <div class="screen-body-item">
          <form class="app-form" method="post">
            <div class="app-form-group">
              <input class="app-form-control" placeholder="FULLNAME" type="text" name="name" required>
            </div>
            <div class="app-form-group">
              <input class="app-form-control" placeholder="EMAIL" type="email" name="email" required>
            </div>
            <div class="app-form-group">
              <select name="gender" class="app-form-control" type="text" required>
                <option selected>GENDER</option>
                <option value="Male">Male</option>
                <option value="Female">Female</option>
                <option value="Others">Others</option>
              </select>
            </div>
            <div class="app-form-group">
              <input class="app-form-control" placeholder="INITIAL BALANCE" type="number" name="balance" required>
            </div>
            <br>
            <div class="app-form-group button">
              <input class="app-form-button" style="color:#2e8b57;" type="submit" value="CREATE USER" name="submit"></input>
              <input class="app-form-button" style="color:#dc3545;" type="reset" value="RESET" name="reset"></input>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>
<footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
</footer>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
</body>
</html>


#createuser.php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create User</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">
    <link rel="stylesheet" type="text/css" href="css/createuser.css">
</head>

<body style="background-color : #ececec;">
<?php
    include 'config.php';
    if(isset($_POST['submit'])){
    $name=$_POST['name'];
    $email=$_POST['email'];
    $gender=$_POST['gender'];
    $balance=$_POST['balance'];
    $sql="insert into users(name,email,gender,balance) values('{$name}','{$email}','{$gender}','{$balance}')";
    $result=mysqli_query($conn,$sql);
    if($result){
               echo "<script> alert('User has been created!');
                               window.location='transfermoney.php';
                     </script>";
                    
    }
  }
?>

<?php
  include 'navbar.php';
?>

        <h2 class="text-center pt-4" style="color : #6c757d;">Create a User</h2>
        <br>

  <div class="background">
  <div class="container">
    <div class="screen">
      <div class="screen-header">
        <div class="screen-header-right">
          <div class="screen-header-ellipsis"></div>
          <div class="screen-header-ellipsis"></div>
          <div class="screen-header-ellipsis"></div>
        </div>
      </div>
      <div class="screen-body">
        <div class="screen-body-item left">
          <img class="img-fluid" src="img/user3.jpg" style="border: none; border-radius: 10%;">
        </div>
        <div class="screen-body-item">
          <form class="app-form" method="post">
            <div class="app-form-group">
              <input class="app-form-control" placeholder="FULLNAME" type="text" name="name" required>
            </div>
            <div class="app-form-group">
              <input class="app-form-control" placeholder="EMAIL" type="email" name="email" required>
            </div>
            <div class="app-form-group">
              <select name="gender" class="app-form-control" type="text" required>
                <option selected>GENDER</option>
                <option value="Male">Male</option>
                <option value="Female">Female</option>
                <option value="Others">Others</option>
              </select>
            </div>
            <div class="app-form-group">
              <input class="app-form-control" placeholder="INITIAL BALANCE" type="number" name="balance" required>
            </div>
            <br>
            <div class="app-form-group button">
              <input class="app-form-button" style="color:#2e8b57;" type="submit" value="CREATE USER" name="submit"></input>
              <input class="app-form-button" style="color:#dc3545;" type="reset" value="RESET" name="reset"></input>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</div>
<footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>P.BHOOMIKA SARVANI</b></p>
</footer>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
</body>
</html>


#index.php
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">


    <title>Basic Banking System</title>
  </head>

  <body >

 
 <?php
  include 'navbar.php';
  ?>


  
      <div class="container-fluid">
      <!-- Introduction section -->
            <div class="row intro py-4">
              
              <div class="col-sm-12 col-md img text-center">
                <img src="img/manasa.jpg" class="img-fluid pt-3" style="height:650px; width:1350px">
              </div>
            </div>

      <!-- Activity section -->
            <div class="row activity text-center" style="background-color: #faebd7;">
                  <div class="col-md act">

                    <img src="img/OIP (3).jpg" class="img-fluid" style="height:250px;">
                    <br>
                    <a href="transfermoney.php"><button style="background-color : #008080;">Transaction</button></a>
                  </div>
                  <div class="col-md act">
                    <img src="img/OIP (4).jpg" class="img-fluid" style="height:250px;">
                    <br>
                    <a href="transactionhistory.php"><button style="background-color : #008080;">History</button></a>
                  </div>   
            </div>
      </div>
      <footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
      </footer>
	  
      <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
  </body>
</html>


#index.php
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">


    <title>Basic Banking System</title>
  </head>

  <body >

 
 <?php
  include 'navbar.php';
  ?>


  
      <div class="container-fluid">
      <!-- Introduction section -->
            <div class="row intro py-4">
              
              <div class="col-sm-12 col-md img text-center">
                <img src="img/manasa.jpg" class="img-fluid pt-3" style="height:700px; width:1350px">
              </div>
            </div>

      <!-- Activity section -->
            <div class="row activity text-center" style="background-color: #faebd7;">
                  <div class="col-md act">

                    <img src="img/OIP (3).jpg" class="img-fluid" style="height:250px;">
                    <br>
                    <a href="transfermoney.php"><button style="background-color : #008080;">Transaction</button></a>
                  </div>
                  <div class="col-md act">
                    <img src="img/OIP (4).jpg" class="img-fluid" style="height:250px;">
                    <br>
                    <a href="transactionhistory.php"><button style="background-color : #008080;">History</button></a>
                  </div>   
            </div>
      </div>
      <footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
      </footer>
	  
      <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
  </body>
</html>


#navbar.php
<!-- navbar --> 
      <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a class="navbar-brand" href="index.php" style="color : #495057;"><img src="img/logo_small.png" alt="Logo" width="26" style="margin-bottom:4px;"> <b>SPARK FOUNDATION BANK</b></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapsibleNavbar">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item">
                <a class="nav-link" href="index.php" style="color : #495057;"><b>Home</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="removeuser.php" style="color : #495057;"><b>List User</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="transfermoney.php" style="color : #495057;"><b>Transfer Money</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="transactionhistory.php" style="color : #495057;"><b>Transaction History</b></a>
              </li>
          </div>
       </nav>


#removeuser.php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List User</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">
	

    <style type="text/css">
      button{
        transition: 1.5s;
      }
      button:hover{
        background-color:#616C6F;
        color: white;
      }
    </style>
</head>

<body style="background-color : #ececec;">

  <?php
  include 'navbar.php';
  ?>
  
<?php
    include 'config.php';
    $sql = "SELECT * FROM users";
    $result = mysqli_query($conn,$sql);
?>




<div class="container">
        <h2 class="text-center pt-4" style="color : #6c757d;">List Users</h2>
        <br>
            <div class="row">
                <div class="col">
                    <div class="table-responsive-sm">
                    <table class="table table-hover table-sm table-striped table-condensed table-bordered table-light" style="border-color:white;">
                        <thead>
                            <tr>
                            <th scope="col" class="text-center py-2">#</th>
                            <th scope="col" class="text-center py-2">Name</th>
                            <th scope="col" class="text-center py-2">Gender</th>
                            <th scope="col" class="text-center py-2">Total Balance</th>
                            </tr>
                        </thead>
                        <tbody>
                <?php 
                    $cnt=1;
                    while($rows=mysqli_fetch_assoc($result)){
                ?>
                    <tr>
                        <td class="py-2"><?php echo $cnt;; ?></td>
                        <td class="py-2"><?php echo $rows['name']?></td>
                        <td class="py-2"><?php echo $rows['gender']?></td>
                        <td class="py-2">Rs. <?php echo $rows['balance']?> /-</td>
                    </tr>
                <?php
                        $cnt=$cnt+1;
                    }
                ?>
            
                        </tbody>
                    </table>
                    </div>
                </div>
            </div> 
         </div>
         <footer class="text-center mt-5 py-2">
            <p>&copy  Made by <b>Bana manasa</b></p>
        </footer>
         <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script> 
</body>
</html>


#removeuserrq.php
<?php

include 'config.php';

$id = $_GET['id'];

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
  }


  // sql to delete a record
$sql = "DELETE FROM users WHERE id=$id";

if ($conn->query($sql) === TRUE) {
    header('Location: removeuser.php');
} else {
  echo "Error deleting record: " . $conn->error;
}

$conn->close();

?>



#selecteduserdetail.php
<?php
include 'config.php';

if(isset($_POST['submit']))
{
    $from = $_GET['id'];
    $to = $_POST['to'];
    $amount = $_POST['amount'];

    $sql = "SELECT * from users where id=$from";
    $query = mysqli_query($conn,$sql);
    $sql1 = mysqli_fetch_array($query); // returns array or output of user from which the amount is to be transferred.

    $sql = "SELECT * from users where id=$to";
    $query = mysqli_query($conn,$sql);
    $sql2 = mysqli_fetch_array($query);



    // constraint to check input of negative value by user
    if (($amount)<0)
   {
        echo '<script type="text/javascript">';
        echo ' alert("Oops! Negative values cannot be transferred")';  // showing an alert box.
        echo '</script>';
    }


  
    // constraint to check insufficient balance.
    else if($amount > $sql1['balance']) 
    {
        
        echo '<script type="text/javascript">';
        echo ' alert("Sorry, Insufficient Balance")';  // showing an alert box.
        echo '</script>';
    }
    


    // constraint to check zero values
    else if($amount == 0){

         echo "<script type='text/javascript'>";
         echo "alert('Oops! Zero value cannot be transferred')";
         echo "</script>";
     }


    else {
        
                // deducting amount from sender's account
                $newbalance = $sql1['balance'] - $amount;
                $sql = "UPDATE users set balance=$newbalance where id=$from";
                mysqli_query($conn,$sql);
             

                // adding amount to reciever's account
                $newbalance = $sql2['balance'] + $amount;
                $sql = "UPDATE users set balance=$newbalance where id=$to";
                mysqli_query($conn,$sql);
                
                $sender = $sql1['name'];
                $receiver = $sql2['name'];
                $sql = "INSERT INTO transaction(`sender`, `receiver`, `balance`) VALUES ('$sender','$receiver','$amount')";
                $query=mysqli_query($conn,$sql);

                if($query){
                     echo "<script> alert('Transaction Completed');
                                     window.location='transactionhistory.php';
                           </script>";
                    
                }

                $newbalance= 0;
                $amount =0;
        }
    
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transaction</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">

    <style type="text/css">
    	
		button{
			border:none;
			background: #d9d9d9;
		}
	    button:hover{
			background-color:#777E8B;
			transform: scale(1.1);
			color:white;
		}

    </style>
</head>

<body style="background-color : #ececec;">
 
<?php
  include 'navbar.php';
?>

	<div class="container">
        <h2 class="text-center pt-4" style="color : #6c757d;">Transaction</h2>
            <?php
                include 'config.php';
                $sid=$_GET['id'];
                $sql = "SELECT * FROM  users where id=$sid";
                $result=mysqli_query($conn,$sql);
                if(!$result)
                {
                    echo "Error : ".$sql."<br>".mysqli_error($conn);
                }
                $rows=mysqli_fetch_assoc($result);
            ?>
            <form method="post" name="tcredit" class="tabletext" ><br>
        <div>
            <table class="table table-striped table-condensed table-bordered table-dark">
                <tr style="color : white;">
                    <th class="text-center">Id</th>
                    <th class="text-center">Name</th>
                    <th class="text-center">Email</th>
                    <th class="text-center">Total Balance</th>
                </tr>
                <tr style="color : white;">
                    <td class="py-2"><?php echo $rows['id'] ?></td>
                    <td class="py-2"><?php echo $rows['name'] ?></td>
                    <td class="py-2"><?php echo $rows['email'] ?></td>
                    <td class="py-2">Rs. <?php echo $rows['balance'] ?></td>
                </tr>
            </table>
        </div>
        <hr><br>
        
        <div class="row">
        
            <div class="col-6">
        <label style="color : #6c757d;"><b>Transfer To:</b></label>
        <select name="to" class="form-control" required>
            <option value="" disabled selected>Select Account</option>
            <?php
                include 'config.php';
                $sid=$_GET['id'];
                $sql = "SELECT * FROM users where id!=$sid";
                $result=mysqli_query($conn,$sql);
                if(!$result)
                {
                    echo "Error ".$sql."<br>".mysqli_error($conn);
                }
                while($rows = mysqli_fetch_assoc($result)) {
            ?>
                <option class="table" value="<?php echo $rows['id'];?>" >
                
                    <?php echo $rows['name'] ;?> (Balance: 
                    <?php echo $rows['balance'] ;?> ) 
               
                </option>
            <?php 
                } 
            ?>
            <div>
        </select>
        </div>


        <div class="col-6">
            <label style="color : #6c757d;"><b>Amount:</b></label>
            <input type="number" class="form-control" name="amount" required> 
        </div>
        
        </div>
              
            <br><br>
                <div class="text-center" >
            <button class="btn" name="submit" type="submit" id="myBtn" style="background:#b0e0e6;">Transfer Amount</button>
            </div>
        </form>
    </div>
    <footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
    </footer>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
</body>
</html>



#transactionhistory.php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transaction History</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">
</head>

<body style="background-color : #ececec;">

<?php
  include 'navbar.php';
?>

	<div class="container">
        <h2 class="text-center pt-4" style="color :#6c757d;">Transaction History</h2>
        
       <br>
       <div class="table-responsive-sm">
    <table class="table table-hover table-striped table-condensed table-light table-bordered">
        <thead>
            <tr>
                <th class="text-center">S.No.</th>
                <th class="text-center">Sender</th>
                <th class="text-center">Receiver</th>
                <th class="text-center">Amount</th>
                <th class="text-center">Date & Time</th>
            </tr>
        </thead>
        <tbody>
        <?php

            include 'config.php';

            $sql ="SELECT * FROM transaction";

            $query =mysqli_query($conn, $sql);

            while($rows = mysqli_fetch_assoc($query))
            {
        ?>

            <tr>
            <td class="py-2"><?php echo $rows['sno']; ?></td>
            <td class="py-2"><?php echo $rows['sender']; ?></td>
            <td class="py-2"><?php echo $rows['receiver']; ?></td>
            <td class="py-2">Rs. <?php echo $rows['balance']; ?> /-</td>
            <td class="py-2"><?php echo $rows['datetime']; ?> </td>
                
        <?php
            }

        ?>
        </tbody>
    </table>

    </div>
</div>
<footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
</footer>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
</body>
</html>

#transfermoney.php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transfer Money</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/table.css">
    <link rel="stylesheet" type="text/css" href="css/navbar.css">

    <style type="text/css">
      button{
        transition: 1.5s;
      }
      button:hover{
        background-color:#616C6F;
        color: white;
      }
    </style>
</head>

<body style="background-color : #ececec;">
<?php
    include 'config.php';
    $sql = "SELECT * FROM users";
    $result = mysqli_query($conn,$sql);
?>

<?php
  include 'navbar.php';
?>

<div class="container">
        <h2 class="text-center pt-4" style="color : #6c757d;">Transfer Money</h2>
        <br>
            <div class="row">
                <div class="col">
                    <div class="table-responsive-sm">
                    <table class="table table-hover table-sm table-striped table-condensed table-bordered table-light" style="border-color:white;">
                        <thead >
                            <tr>
                            <th scope="col" class="text-center py-2">#</th>
                            <th scope="col" class="text-center py-2">Name</th>
                            <th scope="col" class="text-center py-2">E-Mail</th>
                            <th scope="col" class="text-center py-2">Balance</th>
                            <th scope="col" class="text-center py-2">Action</th>
                            </tr>
                        </thead>
                        <tbody>
                <?php 
                    $cnt=1;
                    while($rows=mysqli_fetch_assoc($result)){
                ?>
                    <tr>
                        <td class="py-2"><?php echo $cnt;; ?></td>
                        <td class="py-2"><?php echo $rows['name']?></td>
                        <td class="py-2"><?php echo $rows['email']?></td>
                        <td class="py-2">Rs. <?php echo $rows['balance']?> /-</td>
                        <td><a href="selecteduserdetail.php?id= <?php echo $rows['id'] ;?>"> <button type="button" class="btn btn-info" style="border-radius:0%;">Proceed</button></a></td> 
                    </tr>
                <?php
                $cnt=$cnt+1;
                    }
                ?>
            
                        </tbody>
                    </table>
                    </div>
                </div>
            </div> 
         </div>
         <footer class="text-center mt-5 py-2">
            <p>&copy Made by <b>Bana manasa</b></p>
        </footer>
         <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script> 
</body>
</html>


