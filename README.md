# Ex03 Places Around Me
## Date: 12\9\25

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
map.html

<html>
    <head>
        <title>MAP</title>
    </head>

    <body bgcolor="cyan">
        <h1 align="center">VILLUPURAM -- SUDHARSAN S (24009664)</h1>
        <br>
        
        
       <img src="map (2).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="MGR GOVT COLLEGE" title="MGR GOVT COLLEGE" href="clg.html" coords="901,685,592,803" shape="rect">
    <area target="" alt="VILLUPURAM RAILWAY STATION" title="VILLUPURAM RAILWAY STATION" href="rs.html" coords="922,323,1084,377" shape="rect">
    <area target="" alt="PANAMPET LAKE" title="PANAMPET LAKE" href="lake.html" coords="1059,738,147" shape="circle">
    <area target="" alt="VALEESHWARAR TEMPLE" title="VALEESHWARAR TEMPLE" href="temple.html" coords="1603,474,1907,565" shape="rect">
    <area target="" alt="THENDRAL PARK" title="THENDRAL PARK" href="park.html" coords="765,229,958,308" shape="rect">
</map>
</body>
</html>


clg.html

<html>
    <head>
        <title>MGR GOVT COLLEGE</title>
    </head>
    <body>
        <h>MGR GOVT COLLEGE</h>
        <p>  Dr.M.G.R. Government Arts and Science College for Women, Villupuram was established in the year 2017, in memory of Late Chief Minister of Tamil Nadu, Bharat Ratna, Dr. M.G.Ramachandran. Affiliated to the Thiruvalluvar University, the College aims to impart knowledge and holistic development to aspiring young women especially from the socially and economically backward classes of the society. Standing by its moto "ulluvadhellam uyarvullal" meaning  whatever you ponder let your aim be lofty still, the college has created a niche for itself in a very short span of time. With over 1400 students the college offers a wide range of undergraduate programs in Science, Arts and Humanities.</p>
    </body>
</html>

lake.html

<html>
    <head>
        <title>PANAMPET LAKE</title>
    </head>
    <body>
        <h>PANAMPET LAKE</h>
        <p>Panampet Lake is a lake located in Viluppuram, Tamil Nadu, India. It is known for its biodiversity and attracts numerous bird species, making it a popular spot for birdwatching. 
Location and overview
Location: The lake is in the Viluppuram district of Tamil Nadu. It is a well-known landmark in the area, and a guest house is located nearby.  </p>
    </body>
</html>

park.html

<html>
    <head>
        <title> THENDRAL PARK</title>
    </head>
    <body>
        <h>THENDRAL PARK</h>
        <p> Thendral Park is an inn located in Villupuram, Tamil Nadu. It is not a public park, but a lodging facility. 
Key details about Thendral Park Inn:
Location: It is situated on Hospital Road, within the city limits of Villupuram, and is easily accessible from both the highway and the railway station.
Facilities: The guest house offers air-conditioned, soundproof family rooms with a flat-screen TV and a private bathroom. Other amenities include free Wi-Fi, a 24-hour front desk, and an elevator.</p>
    </body>
</html>

rs.html

<html>
    <head>
        <title>VILLUPURAM RAILWAY STATION</title>
    </head>
    <body>
        <h>VILLUPURAM RAILWAY STATION</h>
        <p>Villupuram Junction (VM) is a major and busy railway station in Tamil Nadu that serves as a vital interchange for trains connecting Chennai to the southern and central parts of the state. As of June 2024, the station was undergoing redevelopment under the Amrit Bharat Scheme to enhance its amenities and infrastructure. 
Key features
Connectivity: Villupuram is a crucial junction where train lines diverge, connecting to various parts of South India. It is a major hub for trains going to and from Chennai, Tiruchirappalli, Ramanathapuram, and other southern destinations. </p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>VALEESHWARAR TEMPLE</title>
    </head>
    <body>
        <h>VALEESHWARAR TEMPLE</h>
        <p> The Aadhi Valeeswarar Temple in Villupuram is a Shiva temple known for its association with the mythical Vanara king, Vali, from the epic Ramayana. Located in the Poonthottam area, the temple has ancient origins and has been renovated over time. 
Key details about the temple:
Deity: Lord Shiva, worshipped as Aadhi Valeeswarar. The name reflects the legend that the mythical Vanara King, Vali, worshipped Shiva at this location.</p>
    </body>
</html>
```


## OUTPUT
<img width="1249" height="625" alt="image" src="https://github.com/user-attachments/assets/5f63d68b-ca0f-4785-bb21-32b1a5596103" />
<img width="1462" height="692" alt="Screenshot 2025-11-16 174235" src="https://github.com/user-attachments/assets/97e40134-f59b-4a51-8b06-67ec6eb3bfcf" />
<img width="1468" height="684" alt="image" src="https://github.com/user-attachments/assets/6e4077f2-63ab-4ba0-8b41-7f0eca61b3a0" />
<img width="1451" height="684" alt="image" src="https://github.com/user-attachments/assets/b7d4b290-0e18-40d4-8893-6340b765cb14" />
<img width="1453" height="683" alt="image" src="https://github.com/user-attachments/assets/a187f31a-4b7a-4e12-988a-493d65bd6d33" />
<img width="1456" height="688" alt="image" src="https://github.com/user-attachments/assets/88fcd805-46c1-4e31-872e-6ee4d639d835" />






## RESULT
The program for implementing image maps using HTML is executed successfully.
