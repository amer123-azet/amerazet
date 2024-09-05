# amerazet
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="out.css">
</head>
<body>
    <div id="nav"></div>
    <div id="m1"></div>
    <div id="m2">
        <div id="m3"></div>
        <div id="m4"></div>
    </div>
    
    
    <div id="b"></div>
    <div id="d1"></div>
    <div id="d2"></div>
    <div id="d3"></div>
    <div id="d4"></div>
    <div id="footer"></div>
    
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    

}
div{
    border: 3px solid black;
}
#nav{
width: 100%;
height: 10vh;
background-color: aqua;
}
#m1{
    width: 50%;
    height: 20vh;
    background-color: blue;
}
#m2{
width: 50%;
height: 20vh;
background-color: blueviolet;
}
#m3{
    width: 25%;
    height: 10vh;
    background-color: rgb(207, 75, 75);
}
#m4{
    width: 25%;
    height: 20vh;
    background-color: rgb(133, 121, 121);

}

#b{
    width: 100%;
    height: 20vh;
    background-color: yellowgreen;
}
#d1{
    width: 20%;
    height:20vh ;
    background-color: violet;
}
#d2{width: 30%;
height: 20vh;
background-color: tan;
}
#d3{
    width: 30%;
    height:20vh ;
    background-color: slateblue;

}
#d4{
    width: 20%;
    height: 20vh;
    background-color: chartreuse;
}
#footer{
    width: 100%;
    height: 20vh;
    background-color: rgb(36, 33, 31);
}

