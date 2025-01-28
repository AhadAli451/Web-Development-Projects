
```CSS
nav ul{
    gap: 24px;
    display: flex;
    
}

nav{
    display: flex;
    justify-content:space-around;
    font-family: Segoe UI;
    padding: 8px;
    
}
nav ul li{
    list-style: none;
    display: flex;
    align-items: center;
    cursor: pointer;

}

.logo{
    display: flex;
    justify-content:space-around;
    align-items: center;
    padding-right: 246px;
}

.translat{
    display: flex;
    justify-content: center;
    align-items: center;
}

.search{
    display: flex;
    justify-content: center;
    align-items: center;
}
.conatiner{
    display: flex;
    justify-content: center;
    text-align: center;
    align-items: center;
    margin-top: 80px;
    /* max-width: 600px; */
}

.title{
    font-size: 48px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}

.subtitle{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 23px;
    margin-top: 42px;
    max-width: 900px;
}

div span{
    font-weight: bold;
}

.button-container {
    margin: 19px;
}

.button{
    text-decoration: none;
    font-size: 15px;
    /* border: 2px solid black; */
    padding: 14px 15px;
    font-weight: bolder;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #00C6D7;
    color: rgb(255, 255, 254);
    border-radius: 6px;
    border: none;
}

.button:hover{
    background-color: #00A5B7;
}

.logos{
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    margin-top: 76px;
}

.copy{
    font-size: 13px;
    padding-top: 20px;

}

.boxes{
    display: grid;
    grid-template-columns: 310px 310px 310px;
    grid-template-rows: 230px 230px 230px;
    margin-top: 43px;
    justify-content: flex-start;
    align-items: flex-start;


}

.item{
    height: 200px;
    width: 290px;
    background-color:aliceblue;
    border-radius: 7px;
    font-size: 22px;
    font-weight: bold;

}
    @media screen and (max-width: 945px) {
        .boxes{
            grid-template-columns: 1fr;

        }
    }


.items{
    margin: 13px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.item-one{
    font-size: 12px;
    padding-bottom: 11px;

}

/* .item-two{
    margin-top: 10px;
    background-color: rgb(32, 90, 32);
    color: white;
    font-size: 16px;
    padding: 18px 10px;
} */

.item-three{
    font-size: 9px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.item-four{
    font-size: 9px;
    display: flex;
    justify-content: center;
    align-items: center;
    word-break: break-all;
    line-height: 12px;
}

button{
    padding: 7px 15px;
    border-radius: 9px;
    list-style: none;
    text-decoration: none;
    /* background-color: rgba(70, 212, 70, 0.555)); */
    background-color: rgba(8, 148, 8, 0.671);
    color: rgb(255, 255, 255);
    font-size: 8px;
    font-weight: bold;
    font-size: 13px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    border: none;
}