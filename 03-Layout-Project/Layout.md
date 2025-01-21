
# It is a layout 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
        header{
            position: sticky;
            top: 0;  
        }

        *{
            margin: 0;
            padding: 0;
        }
        ul li{
            background-color: aqua;
            list-style: none;
            padding: 23px;
            font-family: "Poppins", serif;
            font-size: 20px;
            
        
        }

        ul li:hover{
            color: blue;
        }
        ul{
            display: flex;
            justify-content: center;

        }
        nav{
            background-color: aqua;
            position: sticky;
            top: 0;
        
        }

        .container{
            width: 1330px;
            height: 700px;
            background-color: rgba(230, 175, 73, 0.788);
            margin: 10px;
            display: flex;
            justify-content: center;
        }

        .box{
            width: 466px;
            height: 480px;
            background-color:blueviolet;
            display: flex;
        }

        .box{
            width: 466px;
            height: 480px;
            background-color:blueviolet;
            margin: 65px;
        }

        .boxes{
            display: flex;
        }

        .text{
            width: 1000px;
            border: 2px solid black;
            padding: 44px;
            border-radius: 35px;
            margin: 24px;
            display: flex;
            justify-content: center;
            font-family:"Poppins", serif;
            font-weight: bolder;
        }

        .class{
            display: flex;
            justify-content: center;
        }

        footer{
            background-color: chartreuse;
            height: 56px;
            margin: 0px;
            padding: 0;
        }
     .circle1{
      width: 60px; /* Diameter of the circle */
      height: 60px; /* Diameter of the circle */
      background-color: rgb(255, 30, 0); /* Circle color */
      border-radius: 50%; /* Makes the shape a circle */
      position: fixed;
      bottom: 0px;
      right: 0px;
    }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li>About</li>
                <li>Home</li>
                <li>servise</li>
                <li>Content us</li>
            </ul>
        </nav>
    </header>
<main>
    <div class="container">
        <div class="boxes">
            <div class="box"></div>
            <div class="box"></div>
        </div>
    </div>

    <div class="circle circle1"></div>

    <div class="class">
        <div class="text">Wellcome to this Sigma Wed Development Course</div>
    </div>
</main>

    <footer>

    </footer>
</body>
</html>

