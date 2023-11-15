# Ex.07 Software Product Company Website
## Date:31/10/23

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XI TECH</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color:wheat;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;

        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:cadetblue;
            height: 500px;        
            overflow: hidden;
            line-height: 30px;
        }

        h1,h2{
            text-align: center;
        }

        .image1 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
        }

        .image3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .image2  img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="xitech.jpg" alt="logo" border="2"></a>
        </div>
        <a class ="cname"><h1>XI TECH</h1></a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <h1>WELCOME GUYS</h1>
        <h2>" Code is like a humor. When u have to explain it,its bad "</h2>
        <div class="image1">
            <img src="index1.jpg" alt="image1">
        </div>
        <div class="image2">
            <img src="index2.jpg" alt="image2">
        </div>
        <div class="image3">
            <img src="index3.jpg" alt="image3">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT:
![image](https://github.com/skiruthika648/softweb/assets/128348968/7ddcecb9-00ed-486b-ac50-04d443d5d264)
![image](https://github.com/skiruthika648/softweb/assets/128348968/008202b2-c535-4469-b0f5-4b7247f7992b)
![image](https://github.com/skiruthika648/softweb/assets/128348968/b9363a5c-bd08-4f93-ba2b-77f36584fe0c)
![image](https://github.com/skiruthika648/softweb/assets/128348968/ced0906f-b382-43e4-80dd-b3ebb791d7f3)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
