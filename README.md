<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>kuki project</title>
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    /* CSS Reset */
    body {
        font-family: 'Baloo Bhai', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background:2px #200;
    }

    .container{
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: auto;
        top: 80px;
    }

   .img {
   	display:;
  margin-left: 160px;
  margin-right: 60px;
  width: 90%;
  opacity: 12;
}

    .left div {
        line-height: 19px;
        font-size: 26px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 36%;
        margin: 29px auto;
        /* border: 2px solid green; */
    }

    .right {
        position: absolute;
        right: 34px;
        top: 43px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        display: flex;
    }

    .navbar li {
        display: inline-block;
        font-size: 40px;
    }

    .navbar li a {
        color: blue;
        text-decoration: none;
        padding: 34px 23px;

    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        color: grey;

    }

    .btn {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(31, 30, 30);
    }

    .container {
        border: 2px solid white;
        margin: 106px 80px;
        padding: 75px;
        width: 33%;
        border-radius: 28px;
    }

    .form-group input {
        font-family: 'Baloo Bhai', cursive;
        text-align: center;
        display: block;
        width: 508px;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }
</style>

<body>
	
	
	<div class="container">
    <header class="header">
        <!-- Left box for logo -->
        <div id="img">
            <img src="/storage/emulated/0/Download/newproject.jpg" >
            	</div>
            <div>kuki project</div>
        
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
            	
   <li><a href="#"> Home</a> 
   </li>
                
                
   <li><a href="#"> About&nbsp; Us</a>
   </li>
                
   <li><a href="#">Contact&nbsp;Us</a>
   </li>
                
     </ul>
          </div>

        <!-- Right box for buttons -->
        <div class="right">
        	
            <button class="btn">Call Us Now</button>
            
            <button class="btn">Email Us</button>
            
        </div>
    </header>
    
   
   
    <div class="container">
    	
        <h1>   Welcome&nbsp;&nbsp;to &nbsp;;my&nbsp;gamming&nbsp;comunity   </h1>
        
        <form action="noaction.php">
<div class="form-group">
	 <input type="text" name=""         placeholder="Enter your Name">
	 	
</div>
            
<div class="form-group">
	
  <input type="text" name="" placeholder="Enter your Age">
  	
</div>
<div class="form-group">
	
  <input type="text" name="" placeholder="Enter your Gender">
  	
</div>
            
<div class="form-group">
  <input type="text" name="" placeholder="Enter your Locality">
	
</div>
            <div class="form-g=roup">
                <input type="text" name="" placeholder="Enter your Email Id">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <button class="btn">Submit</button>
        </form>
    </div>
</body>

</html>
