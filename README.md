# Ex04 Places Around Me
## Date: 22/04/2025

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
Map.html:
~~~
<html>

<head>

<title>My City</title>

</head>

<body>

<h1 align="center">

<font color="red"><b>Salem</b></font>

</h1>

I

<h3 align="center">

<font color="green"><b>Rihan Ahamed.S (212224040276)</b></font>

</h3>

<center>

<img src="map (2).png" usemap="#MyCity" >

<map name="MyCity">

<area shape="rect" coords="824,424,903,479" href="home.html" title="My home town">
<area shape="rect" coords="866,2,945,57" href="zoo.html" title="Zoological Park">
<area shape="rect" coords="5,64,111,101" href="themepark.html" title="Theme Park">
<area shape="rect" coords="1480,132,1671,191" href="fort.html" title="Fort">
<area shape="rect" coords="1042,85,1199,1" href="yercaud.html" title="yercaud">


</map>

</center>

</body>

</html>
~~~
Home.html:
~~~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>SALEM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Yercaud</b></font>
        </h2>
        <br>
        <hr size="3" color="green">
        <br>
        <center><img src="Salem.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
            <b>Home Town</b>
            <br>
            <br>
            Living near the Salem Collector Office offers a peaceful and balanced lifestyle for a teenager. The area is well-organized, relatively quiet, and considered safe, which creates a calm atmosphere for growing up. Being centrally located, it provides easy access to schools, tuition centers, and libraries, making academic life convenient and focused. The surroundings are clean, and with the backdrop of hills like Shevaroy and Kanjamalai, there’s always a touch of nature nearby. Weekends can mean short trips to places like Yercaud, which offer both relaxation and adventure. The community around the area is warm and rooted in tradition, with festivals and local events bringing people together. Parks, small cafes, and open spaces offer teenagers safe spots to hang out and unwind. With fewer distractions compared to a big city, there’s more space for personal growth, hobbies, and stronger family connections. Overall, Salem, especially around the Collectorate, is a peaceful and wholesome hometown for a teenager to thrive.            </font>
        </p>
    </body>
</html>
~~~
Yercaud.html:
~~~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>SALEM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Yercaud</b></font>
        </h2>
        <br>
        <hr size="3" color="green">
        <br>
        <center><img src="1715682873_shutterstock_2341377521.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
            <b>Yercaud</b>
            <br>
            <br>
            Yercaud is a hill station town in the south Indian state of Tamil Nadu. It lies in the Shevaroy Hills, known for their orange groves, and coffee, fruit and spice plantations. Yercaud Lake has a boathouse, and is surrounded by gardens and woods. On the lake’s eastern shore, Anna Park has local plants and a Japanese garden with bonsai. To the southwest, Lady’s Seat vantage point has a watchtower with a telescope. 
            </font>
        </p>
    </body>
</html>
~~~
Zoo.html:
~~~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>SALEM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Zoological Park</b></font>
        </h2>
        <br>
        <hr size="3" color="green">
        <br>
        <center><img src="zoo.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
            <b>Zoological Park</b>
            <br>
            <br>
            The Kurumbapatti Zoological Park is a second largest zoo in Tamil Nadu next to Arignar Anna Zoological Park, situated in the foothills of the Shervaroyan Hills, 10 km from Salem, Tamil Nadu, India. It was set up in 1981 as a small museum and was later extended to 69 Ha. The zoo houses many species of wildlife, with monkeys as the major attraction, and is in the vicinity of reserve forest, permitting visitors the opportunity to also experience the flora and fauna there. The park has a gentle topography, areas of bamboo and woodland and semi-perennial streams.[6] Facilities include a children's playground area.
            </font>
        </p>
    </body>
</html>
~~~
Themeprk.html:
~~~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>SALEM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Theme Park</b></font>
        </h2>
        <br>
        <hr size="3" color="green">
        <br>
        <center><img src="themepark.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
            <b>Theme Park</b>
            <br>
            <br>
            Paravasa Ulagam is a popular water and amusement theme park located near Salem, Tamil Nadu, along the Salem–Namakkal Highway in Mallur. Spread across 15 acres amidst scenic hills, it offers a variety of over 70 attractions, including water rides like wave pools, lazy rivers, rain dance, and tube slides, as well as dry rides such as mini roller coasters, flying saucers, and breakdance rides. The park also features unique additions like a 7D theater, go-karting, a science park, and areas for kids. Open daily from 10:00 AM to 6:00 PM, entry is ₹750 for adults, ₹600 for children between 90–130 cm, and free for those below 90 cm. The park provides various amenities including restaurants, locker rooms, swimwear rentals, and safety services, making it a fun and family-friendly destination for a day of adventure and relaxation.            </font>
        </p>
    </body>
</html>
~~~
Fort.html
~~~
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>SALEM</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Fort</b></font>
        </h2>
        <br>
        <hr size="3" color="green">
        <br>
        <center><img src="sankagirifort.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
            <b>Sankagirifort</b>
            <br>
            <br>
            Sangagiri Fort was built in 15th century Vijayanagar empire. It has 14 fort walls built on and around a hill and the last phase these walls were built by the British. The fort served as a British tax storage facility for Kongu Nadu, a region comprising the districts of Salem, Erode, Coimbatore, Tiruppur, Namakkal, Karur and Dindukal. It is also known as Guptha Giri.

It was an important military base for Tipu Sultan and later for the British East India Company. This is because only one side of the hill is climbable, as all the others are too steep to climb. This has a death well, granary, two oil godowns, one explosives godown, two masjiths, 2 Varadharaja Perumal temples, former British administrative buildings, and cemeteries formerly used by armies that were stationed at the fort.  </font>
        </p>
    </body>
</html>
~~~
## OUTPUT
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (4).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
