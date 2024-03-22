# Ex04 Places Around Me
## Date: 

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
sanjay.html
<html>
    <head>
        <title>MAP</title>
    </head>
    <body>
        <h1 align="center"><font color="yellow"><b>SOWCARPET</b></font></h1>
        <h3 align="center"><font color="orange">
            <b>SanjayKumar N B (212223230189)</b></h3>
            <center>
        <img src="map.png" usemap="#image-map">       
        <map name="image-map">
            <area target="" alt="bus stop" title="bus stop" href="Vallalar nagar.html" coords="631,325,402,194" shape="rect">
            <area target="" alt="hospital" title="hospital" href="stanlay hospital.html" coords="804,149,984,262" shape="rect">
            <area target="" alt="metro rail" title="metro rail" href="washermenpet metro.html" coords="593,1,776,74" shape="rect">
            <area target="" alt="college" title="college" href="bharathi womens college.html" coords="989,247,1147,348" shape="rect">
            <area target="" alt="temple" title="temple" href="jain temple.html" coords="483,600,627,671" shape="rect">
        </map>
            </center>
    </body>
</html>


stanlay hospital.html
<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="yellow"><b>Sowcarpet</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>Stanley hospital</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Stanley Hospital is one of the leading hospital in Chennai. 
                The best healthcare professionals provide Comprehensive healthcare. 
                It is located at Old Washermanpet. 
                It provides advanced levels of care in over different specialties including Dermatology, Cardiology, Orthopedic, Urology, Gynecology and Obstetrics.
            </font>
        </p>
    </body>
</html>


washermenpet mettro.html
<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
            <font color="black"><b>Sowcarpet</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>washermenpet Metro Rail</b></font>
        </h3>
        <hr size="3" color="orange">
        <p align="justify">
            <font face="Georgia" size="9" color="white">
                Washermanpet is an underground metro station on the North-South Corridor of the Blue Line of Chennai Metro in Chennai, India. This station serves the neighbourhoods of Washermanpet and Royapuram.
            </font>
        </p>
    </body>
</html>


jain temple.html
<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="black"><b>Sowcarpet</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>Jain temple</b></font>
        </h3>
        <hr size="3" color="blue">
        <p align="justify">
            <font face="Georgia" size="9" color="white">
                he Mint Jain temple, also known as Gomateswar Jain Temple, is located in Sowcarpet. It is one of the largest Jain temples in India and attracts a large number of visitors each year. The temple is dedicated to the 24th Tirthankara, Parshvanatha, and is an important pilgrimage site for Jains around the world. The temple complex covers over 12 acres and features beautiful architecture, intricate carvings, and stunning statues.
            </font>
        </p>
    </body>
</html>


vallalar nagar.html
<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="meroon">
        <h1 align="center">
            <font color="yellow"><b>Sowcarpet</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>MINT Bus stop</b></font>
        </h3>
        <hr size="3" color="green">
        <p align="justify">
            <font face="Georgia" size="9" color="white">
                The old bus terminus on Old Jail Road in Mint has been restored with basic facilities, which include steel shelters, bus bays, concrete flooring, lighting and a seating arrangement for commuters.
                Chennai Metro Rail Limited (CMRL) carried out the restoration of the terminus during the lockdown months, honouring the terms of an agreement with Greater Chennai Corporation. 
                CMRL had acquired land from the terminus for the construction of a Metro Rail station.
            </font>
        </p>
    </body>
</html>

bharathi womens college.html
<html>
    <head>
        <title>Map</title>
    </head>
    <body bgcolor="orage">
        <h1 align="center">
            <font color="green"><b>Sowcarpet</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>womens college</b></font>
        </h3>
        <hr size="3" color="cyan">
        <p align="justify">
            <font face="Georgia" size="9" color="white">
                Bharathi Women’s College was established in 1964 and is very famous for its academic standing and leadership building for women. The college is affiliated to University of Madras, Chennai and has been re-accredited Grade B by NAAC. The college is named after a famous Tamil poet Subramanian Bharathi.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<map/Screenshot 2024-03-22 050837.png>)
![alt text](<map/Screenshot 2024-03-22 051446.png>)
![alt text](<map/Screenshot 2024-03-22 051503.png>)
![alt text](<map/Screenshot 2024-03-22 051517.png>)
![alt text](<map/Screenshot 2024-03-22 051530.png>)
![alt text](<map/Screenshot 2024-03-22 051653.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
