<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hyperLearn_pr_1</title>
    <style>
        body {
            background-color: white;
            margin: 0;
            
        }
        #heading { 
            font-size: 30px;
            color:rgb(4, 4, 31);
            text-align: center;
            margin-left:820px;
            margin-top: 40px;
            margin-bottom: 10px;
            font-family: sans-serif;
            font-style: normal;
        }
        form {
            position: absolute;
            background-color: white;
            width: 600px;
            height: 570px;
            text-align: left;
            margin-left: 850px;
            margin-top: 20px;
            margin-bottom: 200px;
            border-radius: 10px;
            box-shadow: 0 4px 4px 0 lightgray , 0 2px 2px lightgrey;
        }    
        .ab {
            width: 550px;
            padding-top: 15px;
            border-top: none;
            border-left: none;
            border-right: none;
        }
        #bb {
            background-color: darkorchid;
            font-size: 15px;
            color: aliceblue;
            width: 555px;
            padding-top: 10px;
            padding-bottom: 10px;
            margin-top: 30px;
            margin-bottom: 30px;
            border: none;
            border-radius: 5px;
            text-align: center;
            margin-left: 25px;
        }
        #bc {
            background-color:white;
            font-weight: bold;
            color:  darkorchid;
            width: 400px;
            padding-top: 10px;
            padding-bottom: 10px;
            margin-top: 15px;
            margin-bottom: 20px;
            margin-left: 110px;
            border: none;
            border-radius: 5px;
            box-shadow: 0 2px 1px 0 darkorchid, 0 2px 1px 0 darkorchid;
            text-align: center;
        }
        #aa {
            margin-left:225px ;
        }
        #input {
              padding-top: 15px;
              margin-left: 25px;
        }
        div {
            display: block;
        }
        .img {
            position: absolute;
            width: 500px;
            height: 450px;
            margin-top: 0px;
            margin-left: 150px;
        }
        .ww {
            position: absolute;
            font-size: 30px;
            font-family: sans-serif;
            font-weight: bold;
            margin-top: 470px;
            margin-left: 280px;
        }
        .www {
            position: absolute;
            margin-top: 530px;
            margin-left: 270px;
            font-family: sans-serif;
            font-size: 15px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <img src="hyperlearn1.jpeg" class="img" alt="hyperLearn_Image">
    <p class="ww">Welcome Back !</p>
    <p class="www"> hyperLearn helps you connect<br> and Learn with the best mentors<br> out there.
    </p>
    <h1 id="heading">Create New Account</h1>
    <form>
        <div id="input">
           <label for="fullname"><b>Full Name</b></label><br>
           <input class="ab" type="text" name="fullname" required>
        </div>
        <div id="input">
            <label for="email"><b>Email Address</b></label><br>
            <input class="ab" type="email" name="email" required>
         </div>
         <div id="input">
            <label for="number"><b>Phone Number</b></label><br>
            <input class="ab" type="text" name="number" required>
         </div>
         <div id="input">
            <label for="password"><b>Password</b></label><br>
            <input class="ab" type="password" name="password" required>
         </div>
         <button id="bb" type="submit">Sign Up</button><br>
         <span id="aa">Already have an Account?</span><br>
         <button id="bc" type="submit">Sign In</button>
    </form> 
</body>
</html>
