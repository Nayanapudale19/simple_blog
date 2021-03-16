---
layout: "page"
title: "Registration"
permalink: /registration/
---



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
.container{
	display:flex;
	flex-direction:row;
	justify-content:center;
	align-items:center;
}

.box{
	  position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    width: 500px;
    border: 2px solid blue;
  }
  .box form{
    padding: 0 40px;
    box-sizing: border-box;
}

form h2{
	color:black;
  text-align: center;
}
.price-container{
  font-family: 'proximanova-semibold';
    font-size: 18px;
    justify-content: center;
    /* align-items: center; */
}
.flex-row {
  -webkit-box-orient: horizontal!important;
  -webkit-box-direction: normal!important;
  flex-direction: row!important;
}
.d-flex {
  display: flex!important;
}
::before{
  box-sizing: border-box;
}
.strike-price{
  text-decoration: line-through;
  text-decoration-color:red;

}
.final-price{
  color:black;
    margin-left: 0.3em;
    margin: 0 0 10px;
}
.price-msg{
  margin-left: 16px;
    font-size: 15px!important;
    color: #333333;
    margin-top: 3px;
    font-family: 'proximanova-regular';
}
  </style>
    <!-- Latest compiled and minified CSS -->
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
 
    <!-- jQuery library -->
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
 
   <!-- Latest compiled JavaScript -->
   <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
   <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">

</head>
<body>
    <div class="container">
  <div class="box">
  <form action="https://getform.io/f/b72ce609-2ddc-4bc1-935c-ab231cf2de0f" method="POST">
  <h2>Get me more Details</h2>
  <div class="row">
  <div class="form-group col-sm-6">
      <input type="email" class="form-control" id="mail" placeholder="Email *" name="name" required>
    </div>
	<div class="form-group col-sm-6">
      <input type="text" class="form-control" id="number" placeholder="Mobile Number *" name="number" required>
    </div>
    </div>
    <div class="row">
	<div class="form-group col-sm-6">
        <p>Select City *</p>
      <select id="" class="form-control" placeholder="select city" required></select>
   </div>
   <div class="form-group col-sm-6">
    <p>Select Language *</p>
    <select id="" class="form-control" placeholder="select city" required></select>
    </div>
    </div>
    <div class="row">
      <div class="price-container d-flex flex-row">
          <p><i class="fa fa-inr" aria-hidden="true">
            </i></p>
          <div class="strike-price">
          2999/-
          </div>
          <div class="final-price">
          999/-
          </div>
          <div class="price-msg">
          <a href="#">+Govt fess</a>
          </div>
      </div>
    </div>
    <div class="col-sm-12">
       <center> <button class="btn btn-warning btn-block">Register my company</button></center>
    </div>
  </form>
  </div>
</div>
</body>
</html>