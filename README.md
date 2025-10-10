# Ex04 Places Around Me
## Date: 23.09.2025

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
```
map.html
<html>
    <head>
        <title>Thoothukudi</title>
    </head>
    <body>
        <h1 align="center" fontcolor="orange">THOOTHUKUDI</h1>
        <h2 align="center" fontcolor="yellow">Swarna Priya S(25009452)</h2>
        <img src="map.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="ERAL" title="ERAL" href="eral.html" coords="1121,772,1223,829" shape="rect">
            <area target="" alt="THARUVAI" title="THARUVAI" href="tharuvaikulam.html" coords="1435,232,98" shape="circle">
            <area target="" alt="SPICNAGAR" title="SPICNAGAR" href="spicnagar.html" coords="1338,552,1425,562,1413,616,1347,635,1297,607" shape="poly">
            <area target="" alt="SRIVAIKUNDAM" title="SRIVAIKUNDAM" href="srivaikuntam.html" coords="868,771,1009,823" shape="rect">
            <area target="" alt="KULATHUR" title="KULATHUR" href="kulathur.html" coords="1479,9,1441,45,1471,78,1538,71,1541,15" shape="poly">
        </map>
    </body>
</html>
eral.html
<html>
    <title>eral</title>
    <body bgcolor = "grey">
        <h1 align="center">ERAL</h1>
       <p>Eral serves as a commercial hub of Thoothukudi district.It is commercially significant town and taluk within the Thoothukudi district of tamil nadu.Situated on the southern Thambirabarani river,it is a vibrant commercial center for a wide range of goods
        </p>
    </body>
</html>

kulathur.html
<html>
    <head>
        <title>KULATHUR</title>
        
    </head>
         <body bgcolor="yellow">
           <h1 align="center">KULATHUR</h1>
       <p>
        Kulathur in Thoothukudi district is a village in Vilathikulam bhadrakali Amman Temple,known for it's kodai vizha festival.It consists of around 1287 families.
       </p>
    </body>
</html>

spicnagar.html
<html>
    <head>
        <title>SPICNAGAR</title>
    </head>
    <body bgcolor = "orange">
        <h1 align="center">SPICNAGAR</h1>
        <p>Spicnagar is an industrial area and township within the Thoothukudi district of tamilnadu,known for its industrial development,especially by SIPCOT.</p>
    </body>
</html>

srivaikuntam.html
<html>
    <head>
    <title>SRIVAIKUNTAM</title>
    </head>

    <body bgcolor="blue">
            <h1 align="center">SRIVAIKUNDAM</h1>
        <p>
            Srivaikundam is renowed for its superb architecture and outstanding carvings,the kallapiran temple at Srivaikuntam.It is located on the banks of the river Thambirabarani.
        </p>
    </body>
</html>

tharuvaikulam.html
<html>
    <head>
    <title>THARUVAIKULAM</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">THARUVAIKULAM</h1>
        <p>Tharuvaikulam is a coastal village in the thoothukudi district of tamil nadu known for its boatyards,marine ecotourism initiatives and agricultural products like tomatoes and red chillies.</p>
    </body>
</html>
```

# OUTPUT

![alt text](<Screenshot 2025-09-27 144316.png>)
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
