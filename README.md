# Ex04 Places Around Me
## reference:25012447
## Date: 9.12.2025

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
~~~
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Shunmathi S S(25012447)</b></font>
        </h3>
        <center>
       <img src="map.png" usemap="#image-map">

      <map name="image-map">
    <area target="" alt="home" title="home" href="thiyagarajanagar.html" coords="1005,175,1305,443" shape="rect">
    <area target="" alt="college" title="college" href="government college of engineering.html" coords="436,510,114" shape="circle">
    <area target="" alt="temple" title="temple" href="saibaba temple.html" coords="1312,695,1527,802" shape="rect">
    <area target="" alt="Mall" title="Mall" href="saravana selvarathinam.html" coords="321,117,190" shape="circle">
    <area target="" alt="Hills" title="Hills" href="reddiarpetti hills.html" coords="964,685,1196,766" shape="rect">
    </map>
        
        </center>
    </body>
</html>

thiyagarajanagar.html
html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="yellow"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>MY HOME</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Thyagaraja Nagar (T.Nagar) in Tirunelveli is a well-connected, residential area (Pincode 627007) offering a mix of traditional charm
                 and modern amenities, known for its friendly atmosphere, temples like Sringeri Sarada Temple, good schools (Jayendra, Pushpalatha), access to hospitals (Sri Kala, Venkateswara),
                  and proximity to the Periyar River for nature lovers, serving as a convenient base with diverse housing options (plots, houses, apartments) for living or renting. 
                   </font>
        </p>
        </body>
       </html>

       saravana selvarathinam.html
       <html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">
            <font color="yellow"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b> Saravana Selvarathinam Mall</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Saravana Stores in Tirunelveli offers a wide range of products (textiles, jewellery, electronics,
                 groceries), known for its variety and affordability, functioning as a one-stop shop;
                  however, some customers report issues with crowds, long billing queues, and cleanliness,
                   with specific branches in areas like Melapalayam and Tirunelveli East catering to different needs,
                    including dedicated Elite jewellery showrooms and general stores, operating with typical retail hours. 
                     </font>
        </p>
        </body>
       </html>

       saibaba temple.html
       <html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="black"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>SaiBaba Temple</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
             <font face="Georgia" size="5" color="white"></font>
             The main Sai Baba Temple in Tirunelveli is the Shri Kubera Sai Baba Temple at Reddiarpatti, 
             known for its peaceful atmosphere, beautiful white marble idol, and special poojas on Thursdays,
              offering city views and rejuvenation, with good accessibility. 
              Key points include its location near the Kanyakumari Highway, serene environment, sub-shrines (Ganesha,
               Dattatreya, Gayatri), clean premises, and popularity, especially on auspicious Thursdays for devotees 
               seeking peace and positive vibes.
                </font>
        </p>
        </body>
       </html> 
       reddiarpetti hills.html
       <html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">
            <font color="yellow"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Rediarpetti Hills</b></font>
        </h3>
        <hr size="3" color="pink">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
                Reddiarpatti Hills in Tirunelveli isn't a major tourist destination like Manjolai,
                 but it's a notable locality/hillock near Tirunelveli city (Pin Code 627007), known for its accessible location and
                  proximity to urban amenities, serving as a backdrop to the town, and being part of the broader Tirunelveli region known for Western Ghats views,
                   sacred sites (like Nellaiappar Temple), and natural beauty like Manimuthar Falls. 
                   </font>
        </p>
        </body>
       </html>
       government college of engineering.html
       <html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="yellow"><b>TIRUNELVELI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Government Engineering College Tirunelveli</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5" color="white">
             Government College of Engineering (GCE) Tirunelveli, established in 1981, 
             is a reputable, state-owned institute affiliated with Anna University, known for offering quality engineering education 
             with low fees, strong labs, experienced faculty, and good campus facilities like hostels and banks, though seats are limited, 
             focusing on core branches like CSE, ECE, EEE, and Civil Engineering with decent placements, aiming to develop skilled, responsible engineers. 
            </font>
        </p>
        </body>
       </html>
       
 ~~~



## Output
![alt text](shunmathi/mapapp/map.png.png)
![alt text](<shunmathi/mapapp/temple screenshot.png>)
![alt text](<shunmathi/mapapp/rediarpettihills screenshot.png>)
![alt text](<shunmathi/mapapp/saravana stores screenshot.png>)
![alt text](<shunmathi/mapapp/my home screenshot.png>)
![alt text](<shunmathi/mapapp/government college screenshot.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
