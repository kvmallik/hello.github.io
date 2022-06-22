
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>assignment</title>
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
    <link rel="stylesheet" type="text/css" href="CSS2.css">
  <style>
    #{
    padding: 0;
    max-width: 0;
    text-decoration: none;
    list-style: none;
    box-sizing: border-box;
   }

   body{
    font-family: monospace;
   }

   nav{
    background-color: aqua;
    height: 80px;
    width: 100%;
   }

   .logo{
    color: aliceblue;
    font-size: 35px;
    line-height: 80px;
    padding: 0 100px;
    font-weight: bold;
   }

    nav ul{
    float: right;
    margin-right: 20px;
   }

   nav ul li{
    display: inline-block;
    line-height: 80px;
    margin: 0 5px;
   }

   nav ul li a {
    color: white;
    font-size: 17px;
    padding: 7px 13px;
    border-radius: 3px;
    text-transform: uppercase;
   }

   a.active,a:hover {
    background-color: rgb(9, 132, 132);
    transition: .5s;
   }

   .checkbtn{
      font-size: 30px;
      color: white;
      float: right;
      line-height: 80px;
      margin-right: 40px;
      cursor: pointer;
      display: none;
   }

   #check{
    display: none;
   }
   
   h1{
        color: #2c3e50;
        text-align: center;
        margin-left: 0;
        padding-left: 0px;
    }
    
   section{
        background: wheat;
        color: #2c3e50;
        margin: 0;
        padding: 10px;
    }


   @media (max-width: 952px) {
    lable.logo{
        font-size: 30px;
        padding: 50px;
    }
    nav ul li a{
        font-size: 16px;
    } 
   }

   @media (max-width: 858px) {
    .checkbtn{
        display: block;
    }
    ul{
        position: fixed;
        width: 100%;
        height: 100vh;
        background: #2c3e50;
        top: 80px;
        left: -109%;
        text-align: center;
        transition: all .5s;
    }
    nav ul li{
        display: block;
        margin: 50px 100px;
        line-height: 30px;
    }
    nav ul li a{
        font-size: 20px;
    }
    a:hover,a.active{
        background: none;
        color: #0082e6;
    }
    #check:checked ~ ul{
        left: 0%;
    }
    h1{
        padding: 10px;
    }
   }




body { background-color:rgb(244, 215, 215);
margin: 1%;
padding: 1;
font-family: sans-serif;

}
.container{
width: 800px;
margin: 50px auto 0;
display: table;
box-sizing: border-box;
}
.row{
margin: 20px 0;
border-left: 10px solid rgb(231, 223, 223);
transition: .5s;
}
h1 { color : rgb(16, 16, 16);
text-align:center;
}

.column{
background-color: aqua;
display: table-cell;
padding: 10px;
width: 33.33%;text-align: center;
color: black;
vertical-align: middle;
border-right: 10px solid rgb(231, 223, 223);
border-left: 10px solid rgb(231, 223, 223);
transition: .5s;
}
.row:nth-child(1) .column:nth-child(1){
background-color: rgb(157, 43, 43);
}
.row:nth-child(1) .column:nth-child(2){
background-color: rgb(3, 242, 255);
}
.row:nth-child(1) .column:nth-child(3){
background-color: rgb(68, 57, 189);
}
@media (max-width: 992px) {
.container{
    margin: 0;
    padding: 10px;
    width: 100%;
}
.column{
    width: 100%;
    display: block;
    margin: 10px 0;
    border: none;
    box-sizing: border-box;
}
.row{
    margin: 0;
}
body{
    margin-bottom: 100px;
}
}

#h6{
text-align: right;
border: 1px solid black;
 background-color: rgb(252, 251, 251);
 margin-left: 200px;
 padding: 5px 10px;
 width: fix-content;
 height: fit-content;
}
@media (max-width: 872px) {
#h6{
text-align: center;
 padding: 0px 20px 0px 20px;
margin-left: 70%;
}
}

@media (max-width: 1020px) {
#h6{
text-align: center;
 padding: 0px 20px 0px 20px;
margin-left: 70%;
}
}

.footer a{
float: right;
margin-right: 30px !important;
color: rgb(255, 0, 0);
font-size: 20px;
font-family: 'Courier New', Courier, monospace;
}

.footer a i{
width: 35px;
height: 35px;
border-radius: 50%;
border: 2px solid rgb(255, 0, 0);
text-align: center;
line-height: 28px;
}
</style
</head>
<body>
    
    <nav>
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
        <i class='fa fa-bars' style='color: white'></i>
        </label>
         <lable class="logo">FOOD,LLC</lable>
            <ul>
                <li><a href="" target="_blank">chicken</a></li>
                <li><a href="" target="_blank">beef</a></li>
               <li><a href="" target="_blank">sushi</a></li>      
            </ul>
        </nav>
        
    <h1>our menu</h1>

    <div class="container">
        <div class="row">
            <div class="column"><h6 id="h6">chicken</h6><p>lorem ipsum dolor sit amet,consecteture adipisicing elit, sed do siusmod tempor incididunt ut lobore  et dolore mogna alique . ut emin qd minim veniam , quis nostured  exerc itation ullamco loboris  nisi ut aliquip ex ea commcda consequat</p></div>
            <div class="column"><h6 id="h6">beef</h6><p>lorem ipsum dolor sit amet,consecteture adipisicing elit, sed do siusmod tempor incididunt ut lobore et dolore mogna alique . ut emin qd minim veniam , quis nostured exerc itation ullamco loboris nisi ut aliquip ex ea commcda consequat</p></div>
            <div class="column"><h6 id="h6">sushi</h6><p> lorem ipsum dolor sit amet,consecteture adipisicing elit, sed do siusmod tempor incididunt ut lobore et dolore mogna alique . ut emin qd minim veniam , quis nostured exerc itation ullamco loboris nisi ut aliquip ex ea commcda consequat</div>
        </div>
    </div>
    <div class="footer">
    <a href="">Back To Top<i class="fa fa-angle-up"></i></a>
</div>
</body>
</html>
