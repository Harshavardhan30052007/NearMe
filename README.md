# Ex04 Places Around Me
## Date: 12.11.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
'''
map.html
<html>
<head>
    <title>My City</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>Vaniyambadi</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Tharrun D (24900893)</b></font>
    </h3>
    <center>
        <img src="map.png" usemap="#MyCity">
        <map name="MyCity"> 
            <area shape="rect" coords="579,388,617,418" title="My House" href="house.html">
            <area shape="rect" coords="839,275,881,315" title="M S Hall" href="hall.html">
            <area shape="rect" coords="277,150,316,185" title="Ahmedia Hotel" href="hotel.html">
            <area shape="rect" coords="77,324,120,358" title="Shivan Temple" href="temple.html">
            <area shape="rect" coords="965,394,1011,434" title="High School" href="school.html">
        </map>
    </center>
</body>
</html>

hall.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>M S Hall</h1>
    </header>
    <div class="content">
        <p>A function hall is a versatile space designed to host various types of events and gatherings. It can accommodate personal, social, or corporate functions.The M.S. Hall may host various events such as weddings, conferences, community gatherings, or cultural celebrations. Its design and amenities are tailored to ensure a smooth and memorable experience for attendees. </p>
    </div>
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ahmedia Hotel </h1>
    </header>
    <div class="content">
        <p>Ahmedia Hotel offers a blend of modern comfort and traditional charm, making it an ideal choice for travelers. Conveniently located, it provides exceptional hospitality, spacious accommodations, and world-class amenities. Whether for leisure or business, the hotel ensures a memorable stay.</p>
    </div>
</body>
</html>

house.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My House</h1>
    </header>
    <div class="content">
        <p>My house is a cozy and comfortable place where I live with my family. It has a beautiful garden in the front, a spacious living room, and a warm kitchen that fills the air with delightful aromas.</p>
        <p>The bedrooms are painted in soft, calming colors, and the walls are adorned with family photographs and artwork. My favorite spot is the balcony, where I enjoy watching sunsets and sipping tea.</p>
    </div>
</body>
</html>

school.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>High School</h1>
    </header>
    <div class="content">
        <p><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>High School</h1>
    </header>
    <div class="content">
        <p>High school is a transformative journey filled with growth and discovery. It's where friendships are forged, dreams take shape, and challenges build resilience. Each day brings new lessons, both in and out of the classroom. These years leave lasting memories and pave the way for a bright future.</p>
    </div>
</body>
</html>
    </div>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Shivan Temple</h1>
    </header>
    <div class="content">
        <p>Shivan Temple is a sacred place dedicated to Lord Shiva, known for its spiritual significance and architectural beauty. Devotees gather to offer prayers and experience peace in the serene atmosphere. The temple often features intricate carvings and rituals steeped in tradition, symbolizing devotion and divine energy.</p>
    </div>
</body>
</html>
'''

## OUTPUT

![alt text](<Screenshot 2024-12-06 230045.png>)

![alt text](<Screenshot 2024-12-07 135704.png>)

![alt text](<Screenshot 2024-12-07 135722.png>)

![alt text](<Screenshot 2024-12-07 135746.png>)

![alt text](<Screenshot 2024-12-07 135812.png>)

![alt text](<Screenshot 2024-12-07 135833.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
