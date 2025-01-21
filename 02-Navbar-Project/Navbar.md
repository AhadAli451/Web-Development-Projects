
# Basically it is desgin a navbar and able multi color body only one click in this website set the global element  


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>project</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

        :root{
            --color: rgb(33, 180, 45);
            --padot: 25px;
            /* --bordot: 2px solid rgb(39, 223, 54); */
            --seccolor:rgb(188, 235, 135);
            --third: aliceblue;
        }

        body{
            background-color: var(--seccolor);
        }

        *{
            margin: 0;
            padding: 0;
        }
        ul li{
            list-style: none;
            padding: var(--padot);
            background-color: var(--color);
            font-weight: bolder;
            color: var(--third)
            
        }
        ul li a{
            color: var(--third);
            text-decoration: none;
            font-family: "Poppins", serif;;
        }

        ul{
            display: flex;
            
        }

        .nav{
            background-color: var(--color);
        }
    </style>
</head>
<body>
    <div class="nav">
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Service</a></li>
            <li><a href="/">Content us</a></li>
        </ul>
    </div>
</body>
</html>