## Web Design for a Software Product Company

# AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Code for home page:
```
<html>
<title>TECCOL</title>
<style>
    body{
        background:url(../static/img/b4.jpg) ;
        background-size: cover;
        
    }

    h1{
        color: aliceblue;
    }
    h2{
        color: aliceblue;
    }
    h3{
        color:tomato;
        align:center;
    }

/* the main window options*/ 
.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:url(123.jpg);

    scroll-padding-left: 5px;
    border:2px solid white;
}
.login input[type="button"] {
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #ffffff;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; /* Add padding for better appearance */
    transition: background-color 0.3s; /* Add transition for a smooth effect */
        /* Set initial background color */
        background-color: #ffffff;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; /* Adjust the color as needed */
}
.join{
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #ffffff;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: aquamarine;
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="people.html">
                <input type="button" value="People">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>WELCOME TO TECCOL</h1>
    <h2>one of the most trusted and valuble company</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"People who need something really important they must know how what is the process to get it"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: aliceblue;">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: aliceblue;">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="products.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:rgb(233, 154, 7);margin-top:240 ; border: none;">
    <P style="color:#0b0a0a; ;"align="center">Designed and Devoloped by vijay K (23004034) </P>
</footer>
</html
```
### codes for peoplepage:
```

<html>
<title>People</title>
<head>
    <link rel="stylesheet" type="text/css" href="layout.css" media=”screen” />
</head>
<style>
    p{
        color: antiquewhite;
    }
    body{
        background:url(../static/img/b4.jpg);
        background-size: cover;
    }
    .styled form {
            margin margin-top:20px;
            display:flex;
            justify-content:space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: antiquewhite;
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="people.html">
                <input type="button" value="People">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="../static/img/people/pexels-hamann-la-1192609.jpg" height="200" width="200">
    <img src="../static/img/people/pexels-hasibullah-zhowandai-819530.jpg" height="200" width="200">
    <img src="../static/img/people/pexels-pixabay-157675.jpg" height="200" width="200">
    <img src="../static/img/people/pexels-pixabay-262391.jpg" height="200" width="200">
    <img src="../static/img/people/pexels-pixabay-415263.jpg" height="200" width="200">
    <img src="../static/img/people/pexels-reead-886285.jpg" height="200" width="200">
</div>
<div CLASS="names">
    <P style="margin-left:-50;">JESSY PINKMEN (FOUNDER) </P>    
    <P style="margin-left:-65;">GUSTOV(CEO)</P>    
    <P style="margin-left:-45;">WALTER WHITE (COOK)</P>    
    <P style="margin-left:-55;">ANDER (ASST)</P>    
    <P style="margin-left:-35;">NADIA (CHAIRMAN)</P>    
    <P style="margin-left:-55;">VALT (HR)</P>     
</div>

</body>
<footer style="background-color:rgb(229, 104, 21);margin-top: 235; border: none;">
    <P style="color:#080707; ;"align="center">Designed and Devoloped by vijay K (23004034) </P>
</footer>
</html>
```
### codes for contactpage:

```
<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:cornflowerblue
        }
        p {
            color: aliceblue;
        }

        body {
            background:url(../static/img/b4.jpg);
        }

        .yourinfo {
            background:url(r4.jp);
            border:5px solid rgb(232, 71, 71);
            margin-right: 800px ;
            
            margin-top: 200px; /* Adjusted margin-top */
            padding: 10px; /* Added padding for better spacing */
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #2278c3; /* Adjust the color as needed */
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: aqua;
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background:url(bg5.jpg);

scroll-padding-left: 5px;
border:2px solid white;
}
.message textarea {
        background-color: white; /* Set the default background color */
        color: black; /* Set the default text color */
    }

    /* Styles for the text area when it is in focus */
.message    textarea:focus {
        background-color: cadetblue; /* Set the background color when in focus */
        color: white; /* Set the text color when in focus */
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="mainpage.html">
                <input type="button" value="HOME">
            </a>
            <a href="products.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="people.html">
                <input type="button" value="People">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: aliceblue;">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >16,Sultan street ,3rd post</p>
        <p >ECR road</p>
        <p >Chennai-600114</p>
        <b >Email:</b>
        <p >akashkumar481@gmail.com</p>
        <b >Phone</b>
        <p >7812875309</p>
    </center>
    </div>
</body>
<footer style="background-color:rgb(239, 154, 7);margin-top: 210px; border: none;">
    <P style="color:black ;"align="center">Designed and Devoloped by  vijay K (23004034) </P>
</footer>
</html
```
### codes for productpage:
```

<html>
    <title>our products</title>
    <style>  
    body{
        background:url(../static/img/b4.jpg);
        background-size:contain;
    } 
    h1{
        color: aliceblue;
    }  
    .styled form {
            margin margin-top: 20px;
            display:flex ;
            justify-content:space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #f47c0c; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #ed9a1e; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:bisque;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="mainpage.html">
                    <input type="button" value="HOME">
                </a>
                <a href="products.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="people.html">
                    <input type="button" value="People">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRODUCTS </h1>
        <img src="../static/img/camera.jpg" height="200" width="200">
        </div>
           
        <img src="../static/img/lens.jpg" height="200" width="200">
        </div>
           
        <img src="../static/img/bag.jpg" height="200" width="200">
        </div>
          
        <img src="..//static/img/laptop.jpg" height="200" width="200">
        </div>
          
        <img src="../static/img/mouse.jpg" height="200" width="200">
        </div>
          
        <img src="../static/img/keyboard.jpeg" height="200" width="200">
        </div>
           
        <img src="../static/img/headphone.jpeg" height="200" width="200">
        </div>
            
        <img src="../static/img/phone.jpg" height="200" width="200">
        </div>
           
        <img src="../static/img/fan.jpeg" height="200" width="200">
        </div>
           
        <img src="../static/img/cycle.jpeg" height="200" width="200">
        </div>
        <img src="../static/img/watch.jpg" height="200" width="200">

       
        </div>
             
        <img src="../static/img/shoe.jpg" height="200" width="200">
        </div>
           
    </center>
    </body>
    <footer style="background-color:rgb(255, 123, 0);margin-top: 170; border: none;">
        <P style="color:black; ;"align="center">Designed and Devoloped by vijay K (23004034) </P>
    </footer>
</html
```
## OUTPUT:

### Home Page:

![image](https://github.com/dharshini-29/productcompanywebsite/assets/147474632/7aa64a8e-6a8d-41a8-a5ee-6cfa05f34bd2)

### productpage:

![image](https://github.com/dharshini-29/productcompanywebsite/assets/147474632/ec235e0a-d317-4e49-ad06-97b567021056)

### peoplepage:

![image](https://github.com/dharshini-29/productcompanywebsite/assets/147474632/4bdcf8a5-87a2-4bdf-b9f5-8f7dd9206261)

### contactpage:

![image](https://github.com/dharshini-29/productcompanywebsite/assets/147474632/58d4c55c-e725-4c26-a8d2-e73e63ace2ae)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
