# Ex03 Places Around Me
## Date:28/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```

nearme.html

<html>
    <head>
        <title>my city</title>
    </head>
    <body bgcolor="black">
        <h1 align="center"><font color="white">KRISHNAGIRI</font></h1>
        <h3 align="center"><font color="white">LOGA SRI M (25012855)</font></h3>
        <br>
        <div style="text-align:center;">
        <img src="Screenshot 2025-11-28 112707.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="KRISHNAGIRI FORT" title="KRISHNAGIRI FORT" href="fort.html" coords="250,23,344,67" shape="rect">
    <area target="" alt="CHILDREN'S PARK" title="CHILDREN'S PARK" href="park.html" coords="74,242,39" shape="circle">
    <area target="" alt="GOVERNMENT MUSEUM" title="GOVERNMENT MUSEUM" href="museum.html" coords="461,366,520,388,517,416,426,419,425,386" shape="poly">
    <area target="" alt="RAMRAJ COTTONS" title="RAMRAJ COTTONS" href="shop.html" coords="416,489,513,538" shape="rect">
    <area target="" alt="HOTEL MANGALAM" title="HOTEL MANGALAM" href="hotel.html" coords="221,226,265,226,289,258,260,290,223,289,197,255" shape="poly">
</map>
    </body>
</html>

fort.html

<html>
    <head>
        <title>FORT</title>
    </head>
    <body bgcolor="#ECE3FC">
        <h1 align="center">KRISHNAGIRI</h1>
        <h3 align="center">KRISHNAGIRI FORT</h3>
        <br>
        <hr>
        <br>
        <p>Krishnagiri fort is a historic fortress built in the 16th century by the Vijayanagara Empire.
           It has been a strategic stronghold for various dynasties, including the Madurai Nayaks and the Mysore Wodeyars.</p>
    </body>
</html>

park.html

<html>
    <head>
        <title>PARK</title>
    </head>
    <body bgcolor="#EDF2FB">
        <h1 align="center">KRISHNAGIRI</h1>
        <h3 align="center">CHILDREN'S PARK</h3>
        <br>
        <hr>
        <br>
        <p>Children's Park in Krishnagiri, Tamil Nadu, is a family-friendly destination. It offers a variety of activities for children, including swings, slides, and open play areas, while families can relax and spend quality time together. The park is open daily from 4:00 AM to 7:00 PM, providing a refreshing atmosphere amidst greenery. It is a peaceful place to unwind with loved ones, making it an ideal spot for short trips or weekend getaways.</p>
    </body>
</html>

museum.html

<html>
    <head>
        <title>MUSEUM</title>
    </head>
    <body bgcolor="beige">
        <h1 align="center">KRISHNAGIRI</h1>
        <h3 align="center">GOVERNMENT MUSEUM KRISHNAGIRI</h3>
        <br>
        <hr>
        <br>
        <p>The Government Museum in Krishnagiri, Tamil Nadu, is a significant cultural institution established in 1993. It serves as a window into the rich history, art, and natural wealth of the Krishnagiri district, spanning from the Paleolithic period to the modern age.</p>
    </body>
</html>

shop.html

<html>
    <head>
        <title>SHOP</title>
    </head>
    <body bgcolor="#CCDBFD">
        <h1 align="center">KRISHNAGIRI</h1>
        <h3 align="center">RAMRAJ COTTONS</h3>
        <br>
        <hr>
        <br>
        <p>The Ramraj Cotton showroom in Krishnagiri is a popular retail outlet specializing in high-quality traditional Indian wear, particularly known for its dhotis and cotton shirts.   The showroom features a wide range of Ramraj Cotton's products, including various styles of dhotis (veshtis), cotton and linen shirts, kurtas, innerwear, and clothing for women (like sarees, leggings, and nightwear) and kids. They focus on ethnic wear, blending tradition with modern styles.</p>
    </body>
</html>

hotel.html

<html>
    <head>
        <title>HOTEL</title>
    </head>
    <body bgcolor="#E8FBE1">
        <h1 align="center">KRISHNAGIRI</h1>
        <h3 align="center">HOTEL MANGALAM</h3>
        <br>
        <hr>
        <br>
        <p>Hotel Mangalam Non Veg & Veg A/C in Krishnagiri is a cherished culinary haven known for its commitment to quality ingredients and exceptional service. The restaurant offers a variety of dishes that cater to different taste preferences, with a focus on authentic non-vegetarian and vegetarian cuisine.</p>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (22).png>)

![alt text](<Screenshot (23).png>)

![alt text](<Screenshot (24).png>)

![alt text](<Screenshot (25).png>)

![alt text](<Screenshot (26).png>)

![alt text](<Screenshot (27).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
