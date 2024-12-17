# Ex.07 Restaurant Website
## Date: 17/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
resurtant.html

<html>
<head>
        <title>OCEAN BREEZE</title>
    </head>
    <style>
        body{
            background-image: url(sfback.jpeg);
            background-size: cover;
            background-position: center;
        }
    </style>
    <br>
    <body style="color: white;">
        <p>
            <a href="resurtant.html" style="color: palegoldenrod;">HOME</a> |
            <a href="menu.html" style="color: palegoldenrod;">MENU</a> |
            <a href="contact.html" style="color: palegoldenrod;">CONTACT</a> |
            <a href="administrator.html" style="color: palegoldenrod;">ADMINISTRATION</a>
        </p>
        <center>
            <img src="aqua.avif" style="height: 150px; width: 150px;">
        </center> 
        <center>
            <h1 style="color: whitesmoke; font-size: 35px; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;" >AQUA BITES</h1>
        </center>
        <center>
        <table>
    
        <tr>
            <td><img src="lob.jfif" style="height: 250px; width: 250px;"></td>
            <td><img src="sf2.jfif" style="height: 250px; width: 250px;"></td>
            <td><img src="sf3.jfif" style="height: 250px; width: 250px;"></td>
            <td><img src="squid.jfif" style="height: 250px; width: 250px;"></td>
            <td><img src="octopus.jfif" style="height: 250px; width: 250px;"></td>
        </tr>
    </center>
    <tr>
        <td><h3 style="color: beige; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"><center>Lobster</center></h3></td>
        <td><h3 style="color: beige;  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"><center>Fish</center></h3></td>
        <td><h3 style="color: beige;  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"><center>Prawn</center></h3></td>
        <td><h3 style="color: beige; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"><center>Squid</center></h3></td>
        <td><h3 style="color: beige;  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;"><center>Octopus</center></h3></td>
    </tr>
</table>
<h2 style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif">Decalaration:</h2>
<p style="font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">seafood was less prestigious than other animal meats, and was often seen as merely an alternative to meat on fast days.<br> Still, seafood was the mainstay of many coastal populations.Over 33,000 species of fish and many more marine invertebrate species have been identified.<br> Bromophenols, which are produced by marine algae, give marine animals an odor and taste that is absent from freshwater fish and invertebrates.<br>"Enjoy a taste of Italy at Bella's, where our authentic recipes and cozy atmosphere make every meal special."
</p>
<hr>
<h1 style="font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">CONTACT</h1>
<H2>+91 9472817490 | aquabites@gmail.com</H2>

    </body>
</html>

menu.html

<!DOCTYPE html>
<html>
    <head>
        <title>Menu</title>
    </head>
    <body>
        <style>
             body{
            background-image: url(sfback.jpeg);
            background-size: cover;
        }
        </style>
        <div class="nav-list">
        
            <a href="resurtant.html" style="color: bisque;">HOME</a> |
            <a href="menu.html" style="color: bisque;">MENU</a> |
            <a href="contact.html" style="color: bisque;">CONTACT</a> |
            <a href="administrator.html" style="color: bisque;">ADMINISTRATION</a>
    
            </div>
        <center>
        <h1 style="color: seashell">FOOD MENU</h1></center>
        <br>

       <center> <h1 style="color: beige;">SOUP VARIETIES:</h1></center>
        <table>
            <tr>
     
        <th><img src="chowder.jfif"><th>
            <center><th><h3 style="color: wheat;">chowder Soup</h3>
           <p style="color: wheat;">Rate: 200/-</p></th></center> 
        
       
            <td><img src="tom.jfif" style="height: 400px; width: 400px;"></td>
           <th> <h3 style="color: wheat;">Tom Yum Soup</h3>
            <p style="color: wheat;">Rate: 250/-</p></th>
        
            <td><img src="lobster bisque.jpg" style="height: 400px; width: 415px;"></td>
            <th><h3 style="color: wheat;">Lobster Bisque</h3>
                <p style="color: wheat;">Rate: 200/-</p>
            </th>
        </tr>
    </table>
    <center>
    <h1 style="color: beige;">PRAWN VARIETIES:</h1></center>
    <table>
        <tr>
            <th><img src="tiger.webp" style="height: 400px; width: 400px;"></th>
            <th><h3 style="color: wheat;">Tiger Prawn</h3>
                <p style="color: wheat;">Rate: 200/-</p></th>
        
            <td><img src="king.jpg" style="height: 400px; width: 400px;"></td>
            <th><h3 style="color: wheat;">King Prawn</h3>
                <p style="color: wheat;">Rate: 270/-</p></th>
        </tr>
    </table>
    <center>
    <h1 style="color: beige;">OCTOPUS VARIETIES:</h1></center>
    <table>
        <tr>
            <th><img src="takoyaki.jpeg" style="height: 400px; width: 400px;"></th>
            <th><h3 style="color: wheat;">Takoyaki</h3>
                <p style="color: wheat;">Rate: 270/-</p></th>

            <td><img src="nakji.jfif"></td>
            <th><h3 style="color: wheat;">Nakji Bokkeum</h3>
                <p style="color: wheat;">Rate: 170/-</p></th>
        </tr>
    </table>
    <center>
        <h1 style="color: beige;">SCALLOPS VARIETIES:</h1></center>
        <table>
            <tr>
                <th><img src="michelin star scallop.avif" style="height: 400px; width: 400px;"></th>
                <th><h3 style="color: wheat;">Michelin star Scallop</h3>
                    <p style="color: wheat;">Rate: 190/-</p></th>
           
                <td><img src="scallop pasta.jpg" style="height: 400px; width: 400px;"></td>
                <th><h3 style="color: wheat;">Scallop Pasta</h3>
                <p style="color: wheat;">Rate: 220/-</p></th>
            
                <td><img src="scallop.jpg" style="height: 400px; width: 400px;"></td>
                <th><h3 style="color: wheat;">Scallop</h3>
                <p style="color: wheat;">Rate: 200/-</p></th>
            </tr>
        </table>
        <center>
            <h1 style="color: beige;">CEVICHE VARIETIES:</h1></center>
            <table>
                <tr>
                    <th><img src="shrimp ceviche.jpg" style="height: 400px; width: 400px;"></th>
                    <th><h3 style="color: wheat;">Shrimp Ceviche</h3>
                        <p style="color: wheat;">Rate: 150/-</p></th>
                
                    <td><img src="tuna ceviche.jpg" style="height: 400px; width: 400px;"></td>
                    <th><h3 style="color: wheat;">Tuna Ceviche</h3>
                    <p style="color: wheat;">Rate: 125/-</p></th>
               
                    <td><img src="mexican ceviche.jpeg" style="height: 400px; width: 400px;"></td>
                    <th><h3 style="color: wheat;">Mexican Ceviche</h3>
                    <p style="color: wheat;">Rate: 160/-</p></th>
                </tr>
            </table>
   



        
    </body>
</html>

Administrator.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AQUA BITES - Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #070c31;
            background-color: #f63a3a;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #27cbbe;
            color: rgb(69, 171, 199);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(1, 33, 15, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #2a688b;
        }

        .admin-container {
            padding: 40px 20px;
            background: tan;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #315b67;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(180, 185, 153);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(159, 154, 149, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1>AQUA BITES</h1>
        <nav>
            <a href="resurtant.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="contact.html">CONTACT</a>
            <a href="administrator.html">ADMINISTRATION</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR BACKBONES</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="adam evan.jpg" alt="CEO">
                <div class="admin-details">
                    <h3>ADAM EVAN</h3>
                    <p>CEO of AQUA BITES</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="koushik.jpg" alt="Manager">
                <div class="admin-details">
                    <h3>KOUSHIK</h3>
                    <p>Manager of AQUA BITES</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="eric ripert.jpg" alt="Master Chef">
                <div class="admin-details">
                    <h3>ERIC RIPERT</h3>
                    <p>Master Chef of AQUA BITES</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="jasper.webp" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>JASPER</h3>
                    <p>Assistant Managing Director of AQUA BITES</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 AQUA BITES. All rights reserved. | <a href="resurtant.html">Back to Home</a></p>
    </footer>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
    <head>
        <title>Contact</title>
    </head>
    <body>
        <br>
        <nav>
            <a href="resurtant.html" style="color: burlywood;">HOME</a> |
            <a href="menu.html" style="color: burlywood;">MENU</a> |
            <a href="contact.html" style="color: burlywood;">CONTACT</a> |
            <a href="administrator.html" style="color: burlywood;">ADMINISTRATION</a>
        </nav>
        <style>
            body{
                background-image: url(contact1.jpg);
                background-size: cover;
            }
        </style>
        <h1 style="color: purple; padding-left: 400px; font-size: 60px;">BOOK YOUR TABLE</h1>
        <h2 style="color: yellowgreen; padding-left: 540px;" >Registration</h2>
        <form>
            <table>
                <tr>
                    <td style=" padding-left: 500px;">Name:</td> <td><input type="text" placeholder="Enter Your Name"></td>
                </tr>
                <tr>
                    <td style="padding-left:500px">Email:</td> <td><input type="text" placeholder="Enter Your Email"></td>
                </tr>
                <tr>
                    <td style="padding-left: 500px;">Message:</td> <td><input type="text" placeholder="Enter Your Message"></td>
                </tr>
                <tr>
                    <td style="padding-left: 500px;"></td> <td><input type="submit"></td><a href="file:///C:/Users/yuvas/OneDrive/Documents/timetable/sumit.html"></a>
                </tr>
                <tr>
                    <td style="padding-left: 500px;"></td> <td><input type="reset"></td>
                </tr>
            </table>
        </form>
        <br>
        <h1 style="font-size: 50px; padding-left: 325px;">REACH US</h1>
        <h2 style="padding-left: 375px;">OPEN HOURS</h2>
        <table>
            <tr>
                <td style="padding-left: 370px;">Monday:4:00pm-Evening</td>
            </tr>
            <tr>
                <td style="padding-left: 370px;">Tue-Fri:2:00pm-Afternoon</td>
            </tr><tr>
                <td style="padding-left: 370px;">Saturday-4:00pm-Evening</td>
            </tr>
        </table>
        <hr>
        <center>
        <h1 style="color: crimson;">CONTACT US</h1>
        <p>No.123, Gandhi Nagar, chennai.</p>
        <H2>+91 9472817490 | aquabites@gmail.com</H2>

    </center>
    </body>
</html>

```

## OUTPUT:
![Screenshot 2024-12-17 211356](https://github.com/user-attachments/assets/af2c672a-5ab3-4462-9d83-0485b4d56e5a)

![Screenshot 2024-12-17 211410](https://github.com/user-attachments/assets/3f74fcbc-919e-420a-b01d-b0d342977fda)

![Screenshot 2024-12-17 211428](https://github.com/user-attachments/assets/bbadcf44-33e2-47ac-a296-797365d4d31d)

![Screenshot 2024-12-17 211609](https://github.com/user-attachments/assets/2add5979-ecce-41ae-858d-27eab2d57953)

![Screenshot 2024-12-17 211713](https://github.com/user-attachments/assets/9f2a6999-c5d3-492a-b077-5331ea21e735)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
