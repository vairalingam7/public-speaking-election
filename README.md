<!DOCTYPE html>
<html>
<head>
    <title>Responsive Page</title>

    <!-- Mobile screen support -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: auto;
            padding: 10px;
        }

        img {
            width: 100%;
            height: auto;
        }

        h1 {
            font-size: 5vw;
        }

        p {
            font-size: 2vw;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 30px;
            }
            p {
                font-size: 16px;
            }
        }
    </style>
</head>

<body>

<div class="container">
    <h1>My Responsive Website</h1>
    <p>This adjusts automatically to screen size!</p>

    <!-- ✅ IMAGE LINK GOES HERE -->
    <img src="https://raw.githubusercontent.com/username/repo/main/photo.png" 
         alt="My Image">

</div>

</body>
</html>
