<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <title>Data Form</title>

    <style>
        body{
            background-image:url(black2.jpg);
            background-size:cover;
            background-position:center center;
            background-attachment:fixed;
            /* box-shadow:0px 0px 10px 0px #ffff; */
        }


        #ui{
            /* background-color:slategrey; */
            padding:30px;
            margin-top:70px;
            border-radius:10px;
            opacity:1.0;
            /* align-items:center; */
            /* margin-right:30px; */

        }

        #ui label{
            color:white;
            font-size:25px;
            /* font-weight:bold; */
        }

        #ui h1{
            color:white;
            font-size:50px;
            background-color:transparent;
            border-radius:60px solid transparent;
            box-shadow:0px 0px 10px 0px #ffff;

        }

        .btn{
            border-radius:30px;
            width:140px;
            font-size:25px;
            color:red;
            font-family:Arial, Helvetica, sans-serif;
            background-color:snow;
            box-shadow:0px 0px 20px 0px #ffff;
            font-weight:bold;
        }

        .con{
            box-shadow: 0px 0px 10px 0px #ffff;
        }

    </style>
</head>
<body>
        <div class="container">
            <div class="row">
                <div class="col-3"></div>
                <div class="col-3"></div>
                <div class="col-3"></div>
                        <div id="ui">
                            <h1 class="text-center">Registration Form</h1>
                            <form class="form-group text-center">
                                    <div class="row">
                                        <div class="col-lg-6">
                                                                        <!-- First Name -->
                                            <label>First Name:</label>
                                            <input type="text" name="fname" class="form-control" placeholder="Enter  Your First Name..">
                                        </div>
                                                                        <!-- Last Name -->
                                        <div class="col-lg-6">
                                            <label>Last Name:</label>
                                            <input type="text" name="lname" class="form-control" placeholder="Enter Your Last  Name..">
                                        </div>
                                    </div>
                                                                <!-- E-mail address -->
                                    <label>E-mail</label>
                                    <input type="email" name="email" class="form-control" placeholder="Enter your e-mail address..">
                                                                <!-- Password                   -->
                                    <div class="row">
                                        <div class="col-lg-6">
                                            <label>Password</label>
                                            <input type="password" name="password" class="form-control" placeholder="Enter your password..">
                                        </div>
                                                                <!-- Confirm Password -->
                                        <div class="col-lg-6">
                                            <label>Confirm Password</label>
                                            <input type="password" name="confirm_password" class="form-control" placeholder="Confirm your password..">
                                        </div>
                                    </div>
                                                                <!-- Gender -->
                                                               
                                    <label>Gender</label>
                                    <br>
                                    <div>
                                        <select class="form-control">
                                            <option>Choose Gender..</option>
                                            <option>Male</option>
                                            <option>Female</option>
                                            <option>Others</option>
                                        </select>
                                    </div>
                                    <br>
                                    <label class="con">CHECK YOUR DATA CAREFULLY AND SUBMIT THIS</label>
                                    <br>
                                                            <!-- Submit -->
                                                            <br>
                                        <input type="submit" name="submit" value="submit" class="btn btn-primary btn-lock "> 
                                            
                            </form>
                        </div>

            </div>

        </div>






        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
