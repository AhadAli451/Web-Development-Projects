
## This is a simple card desgin in **HTML** and **CSS**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>This is a card</title>
    <style>
@import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@400..800&family=Baloo+Bhai+2:wght@400..800&family=Buda:wght@300&family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap');

        * {
            padding: 0;
            margin: 0;
        }

        body {
            background-color: rgb(116, 110, 110);
            padding: 50px;
        }

        .card {
            width: 250px;
            height: 460px;
            border: 2px solid rgb(182, 174, 174);
            background-color: white;
            border-radius: 16px;
        }

        .image {
            padding: 5px;
        }

        .image img {

            border-radius: 16px;
        }

        .text {
            padding: 0 34px 0 34px;
            font-family: "Baloo 2", serif;;
        }

        .text span {
            border: 2px solid rgb(189, 182, 182);
            padding: 1px 5px;
            border-radius: 11px;
            font-size: 12px;
        }

        .content {
            font-size: 13px;
            padding: 30px 12px;
            font-family: "Baloo 2", serif;;
        }

        .div content h2 {
            padding: 7px 12px;
        }

        .button {
            text-align: center;
        }

        .button button {
            padding: 7px 22px;
            border-radius: 10px;
            font-size: 11px;
            background-color: rgb(124, 167, 223);
            color: blue;
            font-family: "Baloo 2", serif;;
        }
    </style>
</head>

<body>
    <div class="card">

        <div class="image">
            <img width="240" src="see side.jpg" alt="">
        </div>

        <div class="text">
            <span>Nature</span>
            <span>Lake</span>
        </div>




        <div class="content">
            <h2>Ahad</h2>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius aliquid suscipit dolor aliquam quae ad, ab
            odit. Maxime ad mollitia sint dicta corporis quas iusto, nesciunt ipsum id, minus fugit est hic amet
            placeat!
        </div>

        <div class="button">
            <button>Read More</button>
        </div>

    </div>


</body>

</html>