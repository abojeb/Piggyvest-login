# Piggyvest-login
SECOND HTML TASK

<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        <!DOCTYPE html>
        <html>

        <head>
            <title>The Login Form</title>
            <style>
                * {
                    margin: 0;
                    padding: 0;
                    box-sizing: border-box;
                }
                
                html {
                    height: 100%;
                }
                
                body {
                    font-family: 'Segoe UI', sans-serif;
                    ;
                    font-size: 1rem;
                    line-height: 2.5;
                    height: 100%;
                    background-color: rgb(30, 2, 129)
                }
                
                .wrap {
                    width: 100%;
                    height: 100%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                }
                
                .login-form {
                    width: 350px;
                    margin: 0 auto;
                    border: none;
                    padding: 2rem;
                    background: #ffffff;
                    border-radius: 5% 5% 5% 0%;
                }
                
                .form-input {
                    background: rgb(234, 237, 238);
                    padding: 15px;
                    width: 100%;
                    border-radius: 5% 5% 5% 0%;
                    border: none;
                }
                
                .form-group {
                    margin-bottom: 1rem;
                    border: none;
                }
                
                .form-button {
                    background: #191cd1;
                    border: 0px solid #ddd;
                    color: #ffffff;
                    padding: 20px;
                    width: 100%;
                    border-radius: 15% 15% 15% 0%;
                    text-transform: uppercase;
                    border: none;
                }
                
                .form-button:hover {
                    background: #191cd1;
                    border: none;
                    border-radius: 15% 15% 15% 0%;
                }
                
                .form-header {
                    text-align: left;
                    margin-bottom: 2rem;
                }
                
                .form-footer {
                    position: relative;
                    top: 100px;
                    left: 0px;
                    bottom: 100px;
                    color: white;
                }
                
                h3 {
                    color: rgb(116, 20, 241);
                }
                
                .image-logo {
                    position: absolute;
                    top: 4rem;
                    width: 207px;
                    left: 30em;
                }
                
                .form-back {
                    position: fixed;
                }
                
                .blue-image {
                    position: absolute;
                    width: 207px;
                    left: -10px;
                    top: -140px;
                }
                
                .green-image {
                    position: fixed;
                    width: 270px;
                    left: 60em;
                    top: -2rem;
                }
                
                .pink-image {
                    position: absolute;
                    top: 30rem;
                    left: -5em;
                    width: 270px;
                }
                
                .purple-image {
                    position: fixed;
                    top: 28rem;
                    left: 55em;
                    weidth: 270px;
                }
            </style>
        </head>


    </title>l
</head>

<body>

    <img src="images/logo.svg.svg" alt="piggyvest logo" class="image-logo" />
    <div class="form-back">
        <img src="images/blue-img.png" alt="" class="blue-image" />
        <img src="images/green-img.png" alt="" class="green-image" />
        <img src="images/pink-img.png" alt="" class="pink-image" />
        <img src="images/purple-img.png" alt="" class="purple-image" />
    </div>

    <div class="wrap">

        <form class="login-form" action="">

            <div class="form-header">
                <h3>Login to your account</h3>
                <p>securely login to your piggyVest</p>
                <img </div>
                <!--Email Input-->
                <div class="form-group">
                    <h4>Email or phone Number</h4>
                    <input type="text" class="form-input" placeholder>
                </div>
                <!--Password Input-->
                <div class="form-group">
                    <h5>password</h5>
                    <input type="password" class="form-input" placeholder>
                </div>
                <!--Login Button-->
                <div class="form-group">
                    <button class="form-button" type="submit">LOG IN</button>
                </div>
        </form>

        <!--/.wrap-->
        <div class="form-footer">
            Don't have an account? <a href="#">Register</a>

</body>

</html>
