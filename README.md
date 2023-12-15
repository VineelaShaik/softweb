# Ex.07 Software Product Company Website
## Date:15-12-2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html

<html>
    <head>
        <title>my website</title>
        <link rel="stylesheet" href="./style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <div class="main">
           
            <div class="nav">
                <img src="logo.png"> 
                <p class="comp">SHAVALT Solutions</p>
               <ul class="list">
                <a href=home.html><li class="item">HOME</li></a>
                <a href=people.html><li class="item">PEOPLE</li></a>
                <a href=product.html><li class="item">PRODUCTS</li></a>
                <a href=contact.html><li class="item">CONTACTS</li></a>
               </ul>
               <div class="search">
                <input class="es" type="text" placeholder="Enter to Search">
               <input class="srh" type="button" value="Search">
            </div>
            
            </div>
           <div class="label">
           
                <h1>A <span>Software Agency</span> shaping<br>
                ideas into Products</h1>
                <h3>"People who are really seroius about software <br>
                    should make their own hardware" -Alan Kay.</h3>
                <input class="join"type="button" value="JOIN US">
            </div>
            <div class="lb">
                <input type="button" class="lg1" value="Login Here">
                <input type="text" class="us" placeholder="Username or Email">
                <input type="text" class="pswd" placeholder="Password">
                <input type="button" class="lg2" value="Login">
                <p class="da"> Don't have an account<br>    <span class="sgn">Sign up</span> here </p>
                <p class="lg">Log in with</p>
                <div class="icon">
                <a href="#" class="fa fa-facebook"></a>
                <a href="#" class="fa fa-instagram"></a>
                <a href="#" class="fa fa-twitter"></a>
                <a href="#" class="fa fa-google"></a>
            </div>
            </div>
        </div>
        
    </body>
    <footer align="center">Designed and Developed by &copy;Vineela Shaik</footer>
</html>

home.css
*{
    margin: 0;
    padding: 0;
}
a{
    text-decoration: none;
    color:black
}

body{
    background: linear-gradient(to right,lavender,rgb(239, 216, 220));
    
}
.main{
    height: 67vh;
    
}

img{
    height:70px;
    margin-top:25px;
    margin-left:35px;
    mix-blend-mode: multiply;
}
.comp{
  padding:30px;
  font-family: 'Lucida Sans';
  font-weight:bold;
  font-size: large;
}
.nav{
    width:400px;
    height:100px;
    display:flex;
    top:25px;
    
}
.list{
    margin-left:160px;
    display:flex;
    
}
.item{
    list-style:none; 
    padding:40px;
    font-family:Arial;
    
}
.item:hover{
    color:rgb(153, 18, 153); 
    
}
.search{
    margin-top:37px;
    display:flex;
    margin-left:30px
}
.es{
    border:none;
  background-color:  rgb(239, 216, 220);
    height:28px;
    width:200px; 
    border-bottom:2px solid  rgb(153, 18, 153);  
}
.srh{
    background-color:rgb(153, 18, 153);
    width:120px;
    height:28px;
    border-bottom: none;
    color:white;
    border-radius:5px
}
.label{
    margin-left:200px;
    margin-top:150px;
    position: relative;
  
    
}
h1{
    font-size:xxx-large;
    font-family: 'Lucida Sans Unicode';
    letter-spacing:3px;
}
span{
    color:rgb(153, 18, 153);
}
h3{
    margin-top:15px;
    line-height:30px;
    font-family:arial;
    letter-spacing: 2px;
}
.join{
    margin-top: 25px;
    width:95px;
    height:30px;
    border-radius:5px;
    padding:2px;
    background-color:rgb(153, 18, 153);
    color:white;
    position: relative;
}
.lb{
    position:relative;
    top:-320px;
    left:1050px;
    background-color: lavender;
    height:420px;
    width:290px;
    border-radius: 9px;
   
}
.lg1{
    height:40px;
    width:250;
    margin-left:19px;
    margin-top:19px;
    border:none;
    border-radius: 7px;
    color:rgb(153, 18, 153);
    font-size:large;
    font-family:arial;
}
.us{
    height:40px;
    width:250;
    margin-left:19px;
    margin-top:19px;
    border:none;
    background-color:lavender;
    border-bottom: 2px solid rgb(153, 18, 153);
}
.pswd{
    height:40px;
    width:250;
    margin-left:19px;
    margin-top:19px;
    border:none;
    background-color:lavender;
    border-bottom: 2px solid rgb(153, 18, 153);
}
.lg2{
    height:40px;
    width:250;
    margin-left:19px;
    margin-top:29px;
    border:none;
    border-radius: 7px;
    color:white;
    font-size:large;
    font-family:arial;
    background-color:rgb(153, 18, 153) ; 
}
.da{
    margin-top:25px;
    margin-left:75px
}
.sgn{
    margin-left:18px
}
.lg{
    margin-left:100px;
    margin-top:25px;
}
.icon{
    margin-left:27px
}
.fa {
    padding: 20px;
    font-size: 27px;
    text-align: center;
    text-decoration: none;
   
  }
footer{
    margin-top: 225px;
    background-color: lightsalmon;
  
}

people.html

<html>
    <head>
        <title>products</title>
        <style>
           
            *{
    margin: 0;
    padding: 0;
}
a{
    text-decoration: none;
    color:black
}

body{
    background: linear-gradient(to right,lavender,rgb(239, 216, 220));
    
}
.main{
    height: 67vh;
    
}

img{
    height:70px;
    margin-top:25px;
    margin-left:35px;
    mix-blend-mode: multiply;
}
.comp{
  padding:30px;
  font-family: 'Lucida Sans';
  font-weight:bold;
  font-size: large;
}
.nav{
    width:400px;
    height:100px;
    display:flex;
    top:25px;
    
}
.list{
    margin-left:160px;
    display:flex;
    
}
.item{
    list-style:none; 
    padding:40px;
    font-family:Arial;
    
}
.item:hover{
    color:rgb(153, 18, 153); 
    
}
.search{
    margin-top:37px;
    display:flex;
    margin-left:30px
}
.es{
    border:none;
  background-color:  rgb(239, 216, 220);
    height:28px;
    width:200px; 
    border-bottom:2px solid  rgb(153, 18, 153);  
}
.srh{
    background-color:rgb(153, 18, 153);
    width:120px;
    height:28px;
    border-bottom: none;
    color:white;
    border-radius:5px
}
footer{
    margin-top: 225px;
    background-color: lightsalmon;
} 
.people{
    display:flex;
    margin-top: 50px;
    margin-left: 180px;

} 
.people img{
    height: 200px;
    border-radius: 50%;
    width:140px;
    margin: 30px;
}  
.people img:hover{
    border-radius: 10%;
} 
.name{
    display: flex;
    margin-left: 180px;
    margin-top: 7px;
    padding-left:30;
}
.name p{
    width:170px;
    margin-left:30px;
    font-family: 'Gill Sans';
    font-weight: bold;
}  
.desg{
    display: flex;
    margin-left: 180px;
    margin-top: 3px;
    padding-left:30;
}
.desg p{
    width:170px;
    margin-left:30px;

}
        </style>
    </head>
    <body><div class="main">
        <div class="nav">
            <img src="logo.png"> 
            <p class="comp">SHAVALT Solutions</p>
           <ul class="list">
            <a href=home.html><li class="item">HOME</li></a>
            <a href=people.html><li class="item">PEOPLE</li></a>
            <a href=product.html><li class="item">PRODUCTS</li></a>
            <a href=contact.html><li class="item">CONTACTS</li></a>
           </ul>
           <div class="search">
            <input class="es" type="text" placeholder="Enter to Search">
           <input class="srh" type="button" value="Search">
        </div>
        </div>
        <div class="people">
            <p><img src="Screenshot_20230710-1037202.png"></p>
            <p><img src="Screenshot 2023-12-06 230806.png"></p>
            <p><img src="Screenshot 2023-12-06 223518.png"></p>
            <p><img src="Screenshot 2023-12-06 224202.png"></p>
            <p><img src="Screenshot 2023-12-06 223745.png"></p>
            <p><img src="Screenshot 2023-12-06 230728.png"></p>
        </div>
        <div class="name">
         <p>Vineela Shaik</p>
         <p>Abdul Latheef Shaik</p>
         <p>Angela Yu</p>
         <p>Rowan Atkinson</p>
         <p>Jimmy Fallon</p>
         <p>Denzel Washington</p>
        </div>
        <div class="desg">
            <p>CEO</p>
            <p>CEO,Co-Founder</p>
            <p>CTO,Co-Founder</p>
            <p>Director</p>
            <p>Asst.Director</p>
            <p>Dy.Director</p>
           </div>
    </div>
</body>
<footer align="center">Designed and Developed by &copy;Vineela Shaik</footer>
</html>

product.html

<html>
    <head>
        <title>products</title>
        <style>
           
            *{
    margin: 0;
    padding: 0;
}
a{
    text-decoration: none;
    color:black
}

body{
    background: linear-gradient(to right,lavender,rgb(239, 216, 220));
    
}
.main{
    height: 67vh;
    
}

img{
    height:70px;
    margin-top:25px;
    margin-left:35px;
    mix-blend-mode: multiply;
}
.comp{
  padding:30px;
  font-family: 'Lucida Sans';
  font-weight:bold;
  font-size: large;
}
.nav{
    width:400px;
    height:100px;
    display:flex;
    top:25px;
    
}
.list{
    margin-left:160px;
    display:flex;
    
}
.item{
    list-style:none; 
    padding:40px;
    font-family:Arial;
    
}
.item:hover{
    color:rgb(153, 18, 153); 
    
}
.search{
    margin-top:37px;
    display:flex;
    margin-left:30px
}
.es{
    border:none;
  background-color:  rgb(239, 216, 220);
    height:28px;
    width:200px; 
    border-bottom:2px solid  rgb(153, 18, 153);  
}
.srh{
    background-color:rgb(153, 18, 153);
    width:120px;
    height:28px;
    border-bottom: none;
    color:white;
    border-radius:5px
}
footer{
    margin-top: 225px;
    background-color: lightsalmon;

  
}
            .con{
                margin-left: 360px;
              
                gap:40px;
            }
            .r1{
                display:flex;
               
            }
            .r2{
                display:flex;
               
            }
            .con img {
                height: 250;
              
                border: 2px solid black;
                
            }
            img:hover{
                border-radius: 10%;
            }

          
        </style>
    </head>
    <body><div class="main">
        <div class="nav">
            <img src="logo.png"> 
            <p class="comp">SHAVALT Solutions</p>
           <ul class="list">
            <a href=home.html><li class="item">HOME</li></a>
            <a href=people.html><li class="item">PEOPLE</li></a>
            <a href=product.html><li class="item">PRODUCTS</li></a>
            <a href=contact.html><li class="item">CONTACTS</li></a>
           </ul>
           <div class="search">
            <input class="es" type="text" placeholder="Enter to Search">
           <input class="srh" type="button" value="Search">
        </div>
        </div>
        <div class="con">
            <div class="r1">
            <div><img src="p1.png"></div>
            <div><img src="p2.png"></div>
            <div><img src="p3.png"></div>
            <div><img src="p4.png"></div>
            <div><img src="p5.png"></div>
        </div>
            <div class="r2">
                <div><img src="p6.png"></div>
                <div><img src="p7.png"></div>
                <div><img src="p8.png"></div>
                <div><img src="p9.png"></div> 
                <div><img src="p10.png"></div>
            </div>
        </div>
    </div>
    </body>
    <footer align="center">Designed and Developed by &copy;Vineela Shaik</footer>
</html>
contact.html
<html>
    <head>
        <title>products</title>
        <style>
           
            *{
    margin: 0;
    padding: 0;
}
a{
    text-decoration: none;
    color:black
}

body{
    background: linear-gradient(to right,lavender,rgb(239, 216, 220));

}

img{
    height:70px;
    margin-top:25px;
    margin-left:35px;
    mix-blend-mode: multiply;
}
.comp{
  padding:30px;
  font-family: 'Lucida Sans';
  font-weight:bold;
  font-size: large;
}
.nav{
    width:400px;
    height:100px;
    display:flex;
    top:25px;
    
}
.list{
    margin-left:160px;
    display:flex;
    
}
.item{
    list-style:none; 
    padding:40px;
    font-family:Arial;
    
}
.item:hover{
    color:rgb(153, 18, 153); 
    
}
.search{
    margin-top:37px;
    display:flex;
    margin-left:30px
}
.es{
    border:none;
  background-color:  rgb(239, 216, 220);
    height:28px;
    width:200px; 
    border-bottom:2px solid  rgb(153, 18, 153);  
}
.srh{
    background-color:rgb(153, 18, 153);
    width:120px;
    height:28px;
    border-bottom: none;
    color:white;
    border-radius:5px
}
footer{
    margin-top: 370px;
    background-color: lightsalmon;
    position: fixed;
    width:1500px;
}
.contact{
    margin-top:-200px;
    height: 0;
    
}
.hrc{
    margin-top:450;
    border: 7px solid rgb(153, 18, 153) ;   
}
.cf{
    display: flex;
    border: 4px solid rgb(153, 18, 153);
}
.f1{
    padding: 20px;
    border: 4px solid rgb(153, 18, 153);
}
.f1 input,textarea{
    margin:15px
}
.f1 input[type="submit"]{
    width:80px;
    background-color: rgb(49, 107, 243);
    color:white;
    border:none;
    border-radius: 4px;
    padding: 10px;
}
.text{
    height: 30px;
    width:650
}
.f2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-left: 240;
    
}
.f2 div{
    padding: 7px;
}


 </style>
    </head>
    <body><div class="main">
        <div class="nav">
            <img src="logo.png"> 
            <p class="comp">SHAVALT Solutions</p>
           <ul class="list">
            <a href=home.html><li class="item">HOME</li></a>
            <a href=people.html><li class="item">PEOPLE</li></a>
            <a href=product.html><li class="item">PRODUCTS</li></a>
            <a href=contact.html><li class="item">CONTACTS</li></a>
           </ul>
           <div class="search">
            <input class="es" type="text" placeholder="Enter to Search">
           <input class="srh" type="button" value="Search">
        </div>
        </div>
        <div class="contact">
            <hr class="hrc">
            <div class="cf">
            <form class="f1">
                <big><big>CONTACT US</big></big><br>
                <input type="text" class="text" placeholder="Your Name"><br>
                <input type="email"class="text" placeholder="Your Email"><br>
                <textarea rows="5" cols="86"></textarea><br>
                <input type="submit" value="Submit">
            </form>
            <div class="f2">
                <div><big><b>CONTACT&nbsp;&nbsp;INFORMATION</b></big></div><br>
                <div > <b>Address:</b>123 Main Street ,Addanki ,Ongole </div>
                <div><b>Email:</b>shavaltsolution@gmail.com</div>
                <div><b>Phone:</b>044-0804</div>
            </div>
        </div>
    </div>
</body>
<footer align="center">Designed and Developed by &copy;Vineela Shaik</footer>
</html>
```


## OUTPUT:
![Alt text](<Screenshot 2023-12-15 220301.png>)
![Alt text](<Screenshot 2023-12-15 220333.png>)
![Alt text](<Screenshot 2023-12-15 220343.png>)
![Alt text](<Screenshot 2023-12-15 220356.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
