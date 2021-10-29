<!--LOGIN CODES-->
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Login Form</title>
    <link rel="stylesheet" href="style.css">
    <a href="home.html">home</a>
  </head>
  <body>
    <div class="center">
      <h1>Login</h1>
      <form method="post">
        <div class="txt_field">
          <input type="text" required="">
          <span></span>
          <label>Username</label>
        </div>
        <div class="txt_field">
          <input type="password" required="">
          <span></span>
          <label>Password</label>
        </div>
        <div class="pass"></div>
        <!--<input type="submit" value=login>-->
        <button type="button" class="button" onclick="location.href='home.html'">login</button>
        <div class="signup_link">
          Forgot Account? <a href="reg.html">Create an Account</a>
        </div>
      </form>
    </div>

  </body>
</html>
<!-- REGISTRATION FORM-->
<!DOCTYPE html>



  <head>
    <meta charset="UTF-8">
    
    <link rel="stylesheet" href="style.css">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   </head>
<body>
  <div class="container">
    <div class="title">Registration</div>
    <div class="content">
      <form action="#">
        <div class="user-details">
          <div class="input-box">
            <span class="details">Full Name</span>
            <input type="text" placeholder="Enter your name" required>
          </div>
          <div class="input-box">
            <span class="details">Username</span>
            <input type="text" placeholder="Enter your username" required>
          </div>
          <div class="input-box">
            <span class="details">Email</span>
            <input type="text" placeholder="Enter your email" required>
          </div>
          <div class="input-box">
            <span class="details">Phone Number</span>
            <input type="text" placeholder="Enter your number" required>
          </div>
          <div class="input-box">
            <span class="details">Password</span>
            <input type="text" placeholder="Enter your password" required>
          </div>
          <div class="input-box">
            <span class="details">Confirm Password</span>
            <input type="text" placeholder="Confirm your password" required>
          </div>
        </div>
        <div class="gender-details">
          <input type="radio" name="gender" id="dot-1">
          <input type="radio" name="gender" id="dot-2">
          <input type="radio" name="gender" id="dot-3">
          <span class="gender-title">Gender</span>
          <div class="category">
            <label for="dot-1">
            <span class="dot one"></span>
            <span class="gender">Male</span>
          </label>
          <label for="dot-2">
            <span class="dot two"></span>
            <span class="gender">Female</span>
          </label>
          <label for="dot-3">
            <span class="dot three"></span>
            <span class="gender">Prefer not to say</span>
            </label>
          </div>
        </div>
        <div class="Register">
          <input type="submit" value=Register>
        </div>
      </form>
    </div>
  </div>

</body>
</html>
<1-- HOME PAGE-->
<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Home page</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">    
</h
</body>
</html>
ead>
<body>
    <header>
    <div class="wrapper">
        <div class="logo">
            <h1>S.A.F</h1>
        </div>
<ul class="nav-area">
<li><a href="#">Home</a></li>
<li><a href="chat.html">Chat</a></li>
<li><a href="student.html">Student</a></li>
<li><a href="ict.html">ICT</a></li>
</ul>
</div>
<div class="welcome-text">
        <h1>
We are glad you<span> are Home</span></h1>
<a href="#">Contact US</a>
    </div>
</header>
</body>
</html>
<-- CHAT-->

<html>

	<head>
		<title> Chat </title>
		
		<style>
		
			* {
				font-family: sans-serif;
				margin: 0;
				padding: 0;
			}
		
			.header-area {
				height: 6%;
				background: rgb(0 127 255);
				box-shadow: 0 0.25rem 0.25rem rgba(0, 0, 0, 0.2), 0 0 1rem rgba(0, 0, 0, 0.2);
				color: white;
				padding: 4px;
			}
			
			.message-area {
				height: 80%;
				padding: 3px;
				overflow: auto;
			}
			
			.typing-area {
				margin-top: 4px;
				padding: 4px;
				height: 8%;
			}
			
			.typing-box {
				width: 90%;
				height: 100%;
				resize: none;
				padding: 3px;
			}
			
			.send-button {
				border: 0;
				width: 9%;
				background: rgb(0 127 255);
				color: white;
				padding: 8px;
				font-size: 18px;
				position: absolute;
				margin: 8px;
			}
			
			.message-box {
				margin-top: 10px;
			}
			
			.others-message-box {
			}
			
			.my-message-box {
				text-align: right;
				background: white;
			}
			
			.message {
				max-width: 70%;
				border-radius: 5%;
				padding: 5px;
				box-shadow: 0 0.25rem 0.25rem rgba(0, 0, 0, 0.2), 0 0 1rem rgba(0, 0, 0, 0.2);
			}
			
			.my-message {
				float: right;
				background: rgb(0 127 255);
				color: white;
			}
			
			.others-message {
				float: left;
				background: white;
			}
			
			.separator {
				width: 100%;
				height: 8px;
				float: left;
			}
		
		</style>
		
	</head>
	
	<body>
	
		<div class="header-area">
			<h1> S.A.F CHAT</h1>
		</div>
		
		<div class="message-area" id="message-area">
			<!-- <div class="message-box others-message-box">
				<div class="message others-message"> Hi, How are you? </div>
				<div class="separator"></div>
			</div>
			
			<div class="message-box my-message-box">
				<div class="message my-message"> I am good, how are you doing? </div>
				<div class="separator"></div>
			</div> -->
		</div>
		
		<div class="typing-area">
			<textarea class="typing-box" id="typing-box"></textarea>
			<button class="send-button" onclick="sendMessage()"> Send </button>
		</div>
		
		<script src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/2.3.0/socket.io.js" integrity="sha512-v8ng/uGxkge3d1IJuEo6dJP8JViyvms0cly9pnbfRxT6/31c3dRWxIiwGnMSWwZjHKOuY3EVmijs7k1jz/9bLA==" crossorigin="anonymous"></script>
		<script>
			
			var socket;
			window.onload = function() {
				
				socket = io.connect('http://localhost:3000');
				
				socket.on('message-from-others', function(message){
					var html = '<div class="message-box others-message-box">' +
								'<div class="message others-message"> ' + message + ' </div>' +
								'<div class="separator"></div>' +
							'</div>';
							
					document.getElementById("message-area").innerHTML += html;
				})
			}
		
			function sendMessage() {
				var message = document.getElementById("typing-box").value;
				var html = '<div class="message-box my-message-box">' +
								'<div class="message my-message"> ' + message + ' </div>' +
								'<div class="separator"></div>' +
							'</div>';
							
				document.getElementById("message-area").innerHTML += html;
				document.getElementById("typing-box").value = "";
				
				socket.emit('codeboard-message', message);
			}
		
		</script>
	
	</body>

</html>
<!--STUDENT-->
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Navbar Menu Hover Effect</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
   
   <div class="depts">
    <h1>DEPARTMENTS</h1>
    </div>
    <nav>
      <a href="ict.html">ICT</a>
      <a href="#">MATHEMATICS</a>
      <a href="#">HISTORY</a>
      <a href="#">LITERATURE</a>
      <a href="#">ZCC</a>
      <div class="animation start-home"></div>
    </nav>

  </body>
</html>
<!--ICT-->
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Navbar Menu Hover Effect</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    
    <nav>
      <a href="#">Dr. Lighton</a>
      <a href="#">Mr. Mbewe</a>
      <a href="#">Mr. Mwalimu</a>
      <a href="#">Mr. Tuesday</a>
      
      
      <div class="animation start-home"></div>
    </nav>

  </body>
</html>
<!CSSS-->
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@700&family=Poppins:wght@400;500;600&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body{
  margin: 0;
  padding: 0;
  background: linear-gradient(120deg,#2980b9, #8e44ad);
  height: 100vh;
  overflow: hidden;
}
.center{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 400px;
  background: white;
  border-radius: 10px;
  box-shadow: 10px 10px 15px rgba(0,0,0,0.05);
}
.center h1{
  text-align: center;
  padding: 20px 0;
  border-bottom: 1px solid silver;
}
.center form{
  padding: 0 40px;
  box-sizing: border-box;
}
form .txt_field{
  position: relative;
  border-bottom: 2px solid #adadad;
  margin: 30px 0;
}
.txt_field input{
  width: 100%;
  padding: 0 5px;
  height: 40px;
  font-size: 16px;
  border: none;
  background: none;
  outline: none;
}
.txt_field label{
  position: absolute;
  top: 50%;
  left: 5px;
  color: #adadad;
  transform: translateY(-50%);
  font-size: 16px;
  pointer-events: none;
  transition: .5s;
}
.txt_field span::before{
  content: '';
  position: absolute;
  top: 40px;
  left: 0;
  width: 0%;
  height: 2px;
  background: #2691d9;
  transition: .5s;
}
.txt_field input:focus ~ label,
.txt_field input:valid ~ label{
  top: -5px;
  color: #2691d9;
}
.txt_field input:focus ~ span::before,
.txt_field input:valid ~ span::before{
  width: 100%;
}
.pass{
  margin: -5px 0 20px 5px;
  color: #a6a6a6;
  cursor: pointer;
}
.pass:hover{
  text-decoration: underline;
}
.button{
  width: 100%;
  height: 50px;
  border: 1px solid;
  background: #2691d9;
  border-radius: 25px;
  font-size: 18px;
  color: #e9f4fb;
  font-weight: 700;
  cursor: pointer;
  outline: none;
}
.button:hover{
  border-color: #2691d9;
  transition: .5s;
}
.depts{
  text-align: center;
}

.signup_link{
  margin: 30px 0;
  text-align: center;
  font-size: 16px;
  color: #666666;
}
.signup_link a{
  color: #2691d9;
  text-decoration: none;
}
.signup_link a:hover{
  text-decoration: underline;
}
<!--registration css-->

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins',sans-serif;
}
body{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
  background: linear-gradient(135deg, #71b7e6, #9b59b6);
}
.container{
  max-width: 700px;
  width: 100%;
  background-color: #fff;
  padding: 25px 30px;
  border-radius: 5px;
  box-shadow: 0 5px 10px rgba(0,0,0,0.15);
}
.container .title{
  font-size: 25px;
  font-weight: 500;
  position: relative;
}
.container .title::before{
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  height: 3px;
  width: 30px;
  border-radius: 5px;
  background: linear-gradient(135deg, #71b7e6, #9b59b6);
}
.content form .user-details{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 20px 0 12px 0;
}
form .user-details .input-box{
  margin-bottom: 15px;
  width: calc(100% / 2 - 20px);
}
form .input-box span.details{
  display: block;
  font-weight: 500;
  margin-bottom: 5px;
}
.user-details .input-box input{
  height: 45px;
  width: 100%;
  outline: none;
  font-size: 16px;
  border-radius: 5px;
  padding-left: 15px;
  border: 1px solid #ccc;
  border-bottom-width: 2px;
  transition: all 0.3s ease;
}
.user-details .input-box input:focus,
.user-details .input-box input:valid{
  border-color: #9b59b6;
}
 form .gender-details .gender-title{
  font-size: 20px;
  font-weight: 500;
 }
 form .category{
   display: flex;
   width: 80%;
   margin: 14px 0 ;
   justify-content: space-between;
 }
 form .category label{
   display: flex;
   align-items: center;
   cursor: pointer;
 }
 form .category label .dot{
  height: 18px;
  width: 18px;
  border-radius: 50%;
  margin-right: 10px;
  background: #d9d9d9;
  border: 5px solid transparent;
  transition: all 0.3s ease;
}
 #dot-1:checked ~ .category label .one,
 #dot-2:checked ~ .category label .two,
 #dot-3:checked ~ .category label .three{
   background: #9b59b6;
   border-color: #d9d9d9;
 }
 form input[type="radio"]{
   display: none;
 }
 form .button{
   height: 45px;
   margin: 35px 0
 }
 form .button input{
   height: 100%;
   width: 100%;
   border-radius: 5px;
   border: none;
   color: #fff;
   font-size: 18px;
   font-weight: 500;
   letter-spacing: 1px;
   cursor: pointer;
   transition: all 0.3s ease;
   background: linear-gradient(135deg, #71b7e6, #9b59b6);
 }
 form .button input:hover{
  /* transform: scale(0.99); */
  background: linear-gradient(-135deg, #71b7e6, #9b59b6);
  }
 @media(max-width: 584px){
 .container{
  max-width: 100%;
}
form .user-details .input-box{
    margin-bottom: 15px;
    width: 100%;
  }
  form .category{
    width: 100%;
  }
  .content form .user-details{
    max-height: 300px;
    overflow-y: scroll;
  }
  .user-details::-webkit-scrollbar{
    width: 5px;
  }
  }
  @media(max-width: 459px){
  .container .content .category{
    flex-direction: column;
  }
}



<!--home css-->

* {
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Poppins', sans-serif;
}
.wrapper {
  width: 1170px;
  margin: auto;
}
header {
  
  height: 100vh;
  -webkit-background-size: cover;
  background-size: cover;
  background-position: center center;
  position: relative;
}
.nav-area {
  float: right;
  list-style: none;
  margin-top: 30px;
}
.nav-area li {
  display: inline-block;
}
.nav-area li a {
  color: #fff;
  text-decoration: none;
  padding: 5px 20px;
  font-family: poppins;
  font-size: 16px;
  text-transform: uppercase;
}
.nav-area li a:hover {
  background: #fff;
  color: #333;
}
.logo {
  float: left;
}
.logo h1 {
  width: 100%;
  padding: 15px 0;
  color: White;
}
.welcome-text {
  position: absolute;
  width: 600px;
  height: 300px;
  margin: 20% 30%;
  text-align: center;
}
.welcome-text h1 {
  text-align: center;
  color: #fff;
  text-transform: uppercase;
  font-size: 60px;
}
.welcome-text h1 span {
  color: #00fecb;
}
.welcome-text a {
  border: 1px solid #fff;
  padding: 10px 25px;
  text-decoration: none;
  text-transform: uppercase;
  font-size: 14px;
  margin-top: 20px;
  display: inline-block;
  color: #fff;
}
.welcome-text a:hover {
  background: #fff;
  color: #333;
}
/*resposive*/

@media (max-width:600px) {
  .wrapper {
    width: 100%;
  }
  .logo {
    float: none;
    width: 50%;
    text-align: center;
    margin: auto;
  }
  img {
    width: ;
  }
  .nav-area {
    float: none;
    margin-top: 0;
  }
  .nav-area li a {
    padding: 5px;
    font-size: 11px;
  }
  .nav-area {
    text-align: center;
  }
  .welcome-text {
    width: 100%;
    height: auto;
    margin: 30% 0;
  }
  .welcome-text h1 {
    font-size: 30px;
  }
}











<!--students-->

@import url('https://fonts.googleapis.com/css?family=Open+Sans&display=swap');
body {
  font-family: 'Open Sans', sans-serif;
  background: #2c3e50;
}
h1{
  
}
nav{
  position: relative;
  margin: 270px auto 0;
  width: 590px;
  height: 50px;
  background: #34495e;
  border-radius: 8px;
  font-size: 0;
  box-shadow: 0 2px 3px 0 rgba(0,0,0,.1);
}
nav a{
  font-size: 15px;
  text-transform: uppercase;
  color: white;
  text-decoration: none;
  line-height: 50px;
  position: relative;
  z-index: 1;
  display: inline-block;
  text-align: center;
}
nav .animation{
  position: absolute;
  height: 100%;
  /* height: 5px; */
  top: 0;
  /* bottom: 0; */
  z-index: 0;
  background: #1abc9c;
  border-radius: 8px;
  transition: all .5s ease 0s;
}
nav a:nth-child(1){
  width: 100px;
}
nav .start-home, a:nth-child(1):hover~.animation{
  width: 100px;
  left: 0;
}
nav a:nth-child(2){
  width: 110px;
}
nav a:nth-child(2):hover~.animation{
  width: 110px;
  left: 100px;
}
nav a:nth-child(3){
  width: 100px;
}
nav a:nth-child(3):hover~.animation{
  width: 100px;
  left: 210px;
}
nav a:nth-child(4){
  width: 160px;
}
nav a:nth-child(4):hover~.animation{
  width: 160px;
  left: 310px;
}
nav a:nth-child(5){
  width: 120px;
}
nav a:nth-child(5):hover~.animation{
  width: 120px;
  left: 470px;
}



<!--MBEWE-->
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Navbar Menu Hover Effect</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <h1></h1>
    <nav>
      <h1>ICT</h1>
      <a href="#">Admin right</a>
      <a href="#">Edit</a>
      <a href="#">Update</a>
      <a href="#">delete</a>
      <a href="#">Admin right</a>
      
      <div class="animation start-home"></div>
    </nav>

  </body>
</html>


