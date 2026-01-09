<!DOCTYPE html>

<html lang="zh-HK">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>SAKURA.C - 成立於2025</title>

    <style>

        body {

            margin: 0;

            padding: 0;

            font-family: 'Arial', sans-serif;

            background-color: #ffffff;

            display: flex;

            justify-content: center;

            align-items: center;

            height: 100vh;

            flex-direction: column;

        }

        .logo-container {

            text-align: center;

        }

        .logo {

            font-size: 10vw;

            font-weight: bold;

            color: #ff0000;

            text-shadow: 0 0 10px rgba(255,0,0,0.3);

            margin-bottom: 20px;

            position: relative;

        }

        .logo::after {

            content: '';

            position: absolute;

            bottom: -20px;

            left: 50%;

            transform: translateX(-50%);

            width: 60%;

            height: 20px;

            background-color: #ff0000;

            border-radius: 50%;

            opacity: 0.5;

        }

        .estd {

            font-size: 3vw;

            color: #ff0000;

            margin-bottom: 20px;

        }

        .coming-soon {

            font-size: 4vw;

            color: #ff0000;

            opacity: 0.8;

        }

        @media (max-width: 768px) {

            .logo {

                font-size: 15vw;

            }

            .estd {

                font-size: 5vw;

            }

            .coming-soon {

                font-size: 6vw;

            }

        }

    </style>

</head>

<body>

    <div class="logo-container">

        <div class="estd">ESTD 2025</div>

        <div class="logo">SAKURA.C</div>

        <div class="coming-soon">Coming Soon...</div>

    </div>

</body>

</html>

