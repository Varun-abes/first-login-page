# first-login-page
a login page using HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LOGIN FORM DESIGN</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
            min-height: 100vh;
            background-color: #eee;
            display: flex;
            font-family: "Helvetica Neue",Helvetica;
        }
        .container{
            margin: 20%;
            width: 500%;
            max-width: 90%;
        }
        .container form{
            width: 100%;
            height: 100%;
            padding: 10px;
            background: #white;
            border radius: 4px;
            box-shadow: 0 8px 16px rgba(0,0,0,.3);
        }
        .container form h1{
            text-align: center;
            margin-bottom: 24px;
            color: #222;
        }
        .container form .form-control{
            width: 100%;
            height: 40%;
            background-color: #white;
            border-radius: 4px;
            border: 1px solid #silver;
            margin: 10px 0 18px 0;
            padding: 0 10px;
        }
        .container form .btn{
            margin-left: 50%;
            transform: translateX(-50%);
            width: 120px;
            height: 34px;
            border: none;
            outline: none;
            background: #27a327;
            cursor: pointer;
            font-size: 16px;
            text-transform: uppercase;
            color: #white;
            border-radius: 4px;
            transition: .3s;
        }
        .container form .btn:hover{
            opacity: .7;
        }
    </style>
</head>
<body>
    <div class = "container">
        <form action="">
            <h1><b><i>LOGIN FORM</i></b></h1>
            <div class = "form-group">
                <label for="">Email id</label>
                <input type="text" class="form-control" required>
            </div>
            <div class = "form-group">
                <label for="">Password</label>
                <input type="password" class="form-control" required>
            </div>
            <input type="submit" class="btn" value="login">
        </form>
    </div>
</body>
</html>
