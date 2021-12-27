<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Email Template</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            text-decoration: none;
            font-family: Arial, Helvetica, sans-serif;
            transition: all .2s linear;
        }

        .box-container {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #ccc;
        }

        .box-container .box {
            width: 700px;
            background-color: #2c3e50;
            border-radius: 10px;
            box-shadow: 0 5px 10px #0007;
            display: flex;
            align-items: center;
            margin: 20px;
        }

        .box-container .box .image {
            align-items: center;
            padding: 60px 0 60px 55px;
            width: 260px;
            background: #0005;
            clip-path: polygon(0 0, 80% 0, 100% 15%, 100% 85%, 76% 100%, 0 100%);
        }

        .box-container .box .image img {
            display: flex;
            align-items: center;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            box-shadow: 0 0 0 10px coral;
            object-fit: cover;
        }

        .box-container .box .containt {
            display: flex;
            padding: 0 10px;
        }

        .box-container .box .containt .icons {
            background-color: #fff;
            margin: 0 10px;
        }

        .box-container .box .containt .icons i {
            font-size: 20px;
            margin: 10px 13px;
            color: coral;
            display: block;
        }

        .box-container .box .containt .icons i:first-child {
            margin-bottom: 70px;
        }


        .box-container .box .containt .info .title {
            font-size: 29px;
            color: #fff;
            padding: 5px 0;
            text-transform: capitalize;
        }

        .box-container .box .containt .info .title .span {
            color: coral;
        }

        .box-container .box .containt .info .post {
            display: block;
            font-size: 18px;
            color: #ccc;
            padding-bottom: 32px;
        }

        .box-container .box .containt .info a {
            display: block;
            color: #aaa;
            padding: 6px 0;
        }

        .box-container .box .containt .info a:hover {
            color: #fff;
        }

        .box-container .box .share {
            height: 274px;
            background-color: #fff;
            padding: 0 7px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-flow: column;
            margin-left: auto;
        }

        .box-container .box .share a {
            margin: 10px;
            font-size: 23px;
            color: #666;
        }

        .box-container .box .share a:hover {
            color: coral;
        }

        @media(max-width:650px) {
            .box-container .box {
                flex-flow: column;
                width: 340px;
            }

            .box-container .box .image {
                height: 200px;
                width: 100%;
                padding: 40px 0;
                clip-path: polygon(0 0, 100% 0, 100% 70%, 80% 100%, 20% 100%, 0 70%);
            }

            .box-container .box .image img {
                width: 120px;
                height: 120px;
            }

            .box-container .box .containt {
                padding: 30px 5px;
            }

            .box-container .box .share {
                flex-flow: row;
                height: auto;
                width: 100%;
                padding: 5px 0;
            }
        }
    </style>
</head>

<body>
    <div class="box-container">
        <div class="box">
            <div class="image">
                <img src="img/prof.jpg" alt="">
            </div>

            <div class="containt">
                <div class="icons">
                    <i class="fas fa-user"></i>
                    <i class="fas fa-phone"></i>
                    <i class="fas fa-globe"></i>
                    <i class="fas fa-envelope"></i>
                </div>
                <div class="info">
                    <h3 class="title"><span>Ali </span><span class="span">Haydar</span></h3>
                    <span class="post">Full Stack Web Developer</span>
                    <a href="#">+8801854046599</a>
                    <a href="https://alihaydar.netlify.app/" target="='_blank'">https://alihaydar.netlify.app/</a>
                    <a href="#">alihaydar6599@gmail.com</a>
                </div>
            </div>
            <div class="share">
                <a href="https://www.facebook.com/alihaydararman/" class="fab fa-facebook-f" target="_blank"></a>
                <a href="https://twitter.com/alihaydararman" class="fab fa-twitter" target="_blank"></a>
                <a href="https://www.linkedin.com/in/alihaydararman/" class="fab fa-linkedin" target="_blank"></a>
                <a href="https://github.com/alihaydararman" class="fab fa-github" target="_blank"></a>

            </div>
        </div>
    </div>
</body>

</html>
