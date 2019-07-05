<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">  
    <title>Document</title>
    <style>
            /* Style the navigation bar */
            .navbar {
              width: 100%;
              background-color: #555;
              overflow: auto;
            }
            
            /* Navbar links */
            .navbar a {
              float: left;
              text-align: center;
              padding: 12px;
              color: white;
              text-decoration: none;
              font-size: 17px;
            }
            
            /* Navbar links on mouse-over */
            .navbar a:hover {
              background-color:  #4CAF50;
            }
            
            /* Current/active navbar link */
            .active {
              background-color:#000;
            }
            
            /* Add responsiveness - will automatically display the navbar vertically instead of horizontally on screens less than 500 pixels */
            @media screen and (max-width: 500px) {
              .navbar a {
                float: none;
                display: block;
              }
            }
             </style>
             <style>
   * {box-sizing: border-box}

/* Full-width input fields */
  input[type=text], input[type=password], input[type=email],input[type=number],input[type=tel] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus,input[type=email]:focus ,input[type=number]:focus input[type=tel]:focus{
  background-color: #ddd;
  outline: none;
}

hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for all buttons */
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/* Extra styles for the cancel button */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

/* Float cancel and signup buttons and add an equal width */
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

/* Add padding to container elements */
.container {
  padding: 16px;
}

/* Clear floats */
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

/* Change styles for cancel button and signup button on extra small screens */
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
    width: 100%;
  }
}

             </style>
             <style>
                 /* Bordered form */
form {
  border: 3px solid #f1f1f1;
}

/* Full-width inputs */
input[type=text], input[type=password], input[type=email], input[type=number],input[type=tel] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

/* Set a style for all buttons */
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

/* Add a hover effect for buttons */
button:hover {
  opacity: 0.8;
}

/* Extra style for the cancel button (red) */
.cancelbtn1 {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

/* Center the avatar image inside this container */
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

/* Avatar image */
img.avatar {
  width: 40%;
  border-radius: 50%;
}

/* Add padding to containers */
.container {
  padding: 16px;
}

/* The "Forgot password" text */
span.psw {
  float: right;
  padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
    display: block;
    float: none;
  }
  .cancelbtn {
    width: 100%;
  }
}
             </style>
</head>
<body>
        <div class="row">
                <div class="col-sm-12">
        
                      <!-- Load an icon library -->
        
        <div class="navbar">
          <a  href="#"><i class="fa fa-fw fa-home"></i> Home</a> 
          <a  href="#"><input type="search" name="" id=""><i class="fa fa-fw fa-search"></i> Search</a> 
          <a  href="#"><i class="fa fa-fw fa-user"></i> Login</a>
          <a  href="#"> logo</a> 
        </div>
        </div>
        <div class="row">
                    <div class="col-sm-6">
                            <form action="regester.php" style="border:1px solid #ccc" method="POST">
                                    <div class="container">
                                      <h1>Sign Up</h1>
                                      <p>Please fill in this form to create an account.</p>
                                      <hr>

                                      <label for="name"><b>name</b></label>
                                      <input type="text" placeholder="name" name="na" required>

                                      <label for="last name"><b>last name</b></label>
                                      <input type="text" placeholder="last name" name="last" required>
                                  
                                      <label for="email"><b>Email</b></label>
                                      <input type="email" placeholder="Enter Email" name="email" required>
                                  
                                      <label for="phon"><b>phon</b></label>
                                      <input type="tel" placeholder="phone" name="ph" required>

                                      <label for="centry"><b>centry</b></label>
                                      <input type="text" placeholder="centry" name="ce" required>

                                      <label for="psw"><b>Password</b></label>
                                      <input type="password" placeholder="Enter Password" name="psw" required>
                                  
                                      <label for="psw-repeat"><b>Repeat Password</b></label>
                                      <input type="password" placeholder="Repeat Password" name="psw-repeat" required>
                                  
                                      
                                  
                                  
                                      <div class="clearfix">
                                        <button type="button" class="cancelbtn">Cancel</button>
                                        <button type="submit" class="signupbtn">Sign Up</button>
                                      </div>
                                    </div>
                                  </form>
                    </div>
                                  <div class="col-sm-6">
                                        <form action="login.php">
                                                <div class="imgcontainer">
                                                  <img src="img_avatar2.png" alt="Avatar" class="avatar">
                                                </div>
                                              
                                                <div class="container">
                                                  <label for="em"><b>email</b></label>
                                                  <input type="email" placeholder="email" name="em" required>
                                              
                                                  <label for="psw"><b>Password</b></label>
                                                  <input type="password" placeholder="Enter Password" name="psw" required>
                                              
                                                  <button type="submit">Login</button>
                                                </div>
                                              
                                                <div class="container" style="background-color:#f1f1f1">
                                                  <button type="button" class="cancelbtn1">Cancel</button>
                                                  <span class="psw">Forgot <a href="#">password?</a></span>
                                                </div>
                                              </form>

                                  </div>
                           
            </div>
        </div>
    
</body>
</html>

regester.php

<?php

$db_server ='localhost';
$db_name ='root';
$db_password ='';
$db_database ='shoping123';
$db = mysqli_connect($db_server,$db_name,$db_password,$db_database) or(mysqli_error());
$con = "error cuold connecet to database.";
mysqli_select_db($db,$db_database) or(mysqli_error($con));
?>

<?php
$name = $_POST['na'];
$last = $_POST['last'];
$email = $_POST['email'];
$phone = $_POST['ph'];
$centry = $_POST['ce'];
$password = $_POST['psw'];

$sql = "INSERT INTO `acounts`( `name`, `lastname`, `email`, `phone`, `centry`, `password`)  VALUES ('".$name."', '".$last."', '".$email."', '".$phone."', '".$centry."', '".$password."')";
$query= mysqli_query($db,$sql)or die(mysqli_error($db));

if($query){
    echo "<h1>".mysqli_affected_rows($db)." Acount created succsufuly </h1>";
}
else{
    echo "The acount already in the database";
}
?>
login.php

<?php
$db_server ='localhost';
$db_name ='root';
$db_password ='';
$db_database ='shoping123';
$db = mysqli_connect($db_server,$db_name,$db_password,$db_database) or(musqli_error());
$con = "error cuold connecet to database.";
mysqli_select_db($db,$db_database) or(mysqli_error($con));

session_start();
if($_SERVER["REQUEST_METHOD"] == "POST"){
    $myusername= $_POST['em'];
    $mypassword= $_POST['psw'];
}
    $sql= "SELECT * FROM `acounts` where email ='".$myusername."' and password ='".$mypassword."'";
    $query = mysqli_query($db,$sql)or die(mysqli_error($db));
    $row=mysqli_fetch_array($query,MYSQLI_BOTH);
    $coont =mysqli_num_rows($query);
    if($coont == 1){
        $_SESSION ['login_user'] = $row ['usr type'];
        if($row['usr type'] == "admin"){
            header ("location:admin.php");
        }
        else{
            header ("location:user_Bar.PHP");
        }
       
    }
        else {
           
     echo ("you login name or password is invaild");
    }
?>
قاعده بيانات login 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">  
    <title>Document</title>
    <style>
        /* Add a black background color to the top navigation */
.topnav {
  background-color: #333;
  overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
    </style>
 
</head>
<body>
    <div class="row">
        <div class="col-sm-12">
                <div class="topnav">
                        <a class="active" href="#home">Home</a>
                        <a href="#news">News</a>
                        <a href="#contact">Contact</a>
                        <a href="#about">About</a>
                      </div>
        </div>
 
        
    </div>
    <div class="col-sm-12">
            <table class="table table-dark table-hover">
                    <thead>
                      <tr>
                        <th>id</th>
                        <th>name</th>
                        <th>last name</th>
                        <th>email</th>
                        <th>phone</th>
                        <th>centry</th>
                        <th>password</th>
                        <th>user</th>
                        
                      </tr>
                    </thead>
                    <tbody>
                      <?php
                     $db_server ='localhost';
                     $db_name ='root';
                     $db_password ='';
                     $db_database ='shoping123';
                     $db = mysqli_connect($db_server,$db_name,$db_password,$db_database) or(mysqli_error());
                     $con = "error cuold connecet to database.";
                     mysqli_select_db($db,$db_database) or(mysqli_error($con));



                     $sql=" SELECT * FROM `acounts` ORDER BY `acounts`.`id` DESC";
                     $query= mysqli_query($db,$sql);
                     $row = mysqli_fetch_array($query,MYSQLI_ASSOC);
                     do{
                  
                      echo "<tr>";
                      echo "<td>";
                      echo $row['id'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['name'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['lastname'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['email'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['phone'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['centry'];
                      echo "</td>";
                      echo "<td>";
                      echo $row['password'];
                      echo "</td>";
                      echo "<td>";
                     
                      echo $row['user'];
                      echo "</td>";
                      echo "<td>";
                      
                      echo '<button type="button" id="getEdit" class="btn btn-primary btn-xs" data-toggle="modal" data-target="#myModal" data-id=""><i class="glyphicon glyphicon-pencil">&nbsp;</i>Edit</button>
                      <a href="delet.php?delete='.$row['id'].'" onclick="return confirm(\'Are You Sure ?\')" class="btn btn-danger btn-xs"><i class="glyphicon glyphicon-trash">&nbsp;</i>Delete</a>';
                      echo "</td>";
                      echo "</tr>";
                     
                    }
                    while($row=mysqli_fetch_array($query,MYSQLI_ASSOC));
                      ?>
                    
                    </tbody>
                  </table>
    </div>
    
</body>
</html>





