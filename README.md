# Ex04 Places Around Me
## Date: 23-11-2024

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

map.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align = 'center' >
            <b>BENGALARU</b>
        </h1>
        <h3 align = 'center'>
            Akshay M(24900489)
        </h3>
        <center>
        <img src="map.png" usemap="#Bengaluru">
        <map name="Bengaluru">
            <area alt="White Field" title="White Field" href="wf.html" coords="1144,336,61" shape="circle" target="_blank">
            <area target="_blank" alt="Banashankari" title="Banashankari" href="bs.html" coords="445,489,63" shape="circle">
            <area target="_blank" alt="Lal Bagh" title="Lal Bagh" href="lal.html" coords="540,374,616,445" shape="rect">
            <area target="_blank" alt="Bengaluru Palace" title="Bengaluru Palace" href="palace.html" coords="547,191,644,245" shape="rect">
            <area target="_blank" alt="Koramangala" title="Koramangala" href="kora.html" coords="692,493,672,462,696,420,750,446,745,497" shape="poly">
        </map>
        </map>
        </center>
    </body>
</html>

```

wf.html

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            White Field
        </title>
    </head>
    <body>
        <h1 align="center">
            White Field
        </h1>
        <p>
            Known for its tech parks and upmarket apartment complexes, lively Whitefield is also a shopping and entertainment hub. Upscale malls like Phoenix Marketcity and VR Bengaluru house global brands, movie theaters, live music, and alfresco bars. Hip mall eateries serve Pan-Asian, European, and Indian cuisines. Beyond the malls, casual South Indian cafes and popular brewpubs are frequented by an after-hours office crowd.
        </p>
        <center>
        <br>
        <img src="wf.jpg" width="1000" height="600">
        </center>
    </body>
</html>

```

kora.html

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Koramangala
        </title>
    </head>
    <body>
        <h1 align="center">
            Koramangala
        </h1>
        <p>
            Cosmopolitan Koramangala is popular with young tech workers and students, due to the many IT companies and colleges in the area. Hip restaurants and rooftop bars cluster around 80 Feet Main Road, while the streets around Jyoti Nivas College are also known for trendy stores selling funky clothes and accessories. Upscale apartment complexes are interspersed with the commercial buildings on the tree-lined avenues.
        </p>
        <center>
        <br>
        <img src="kora.jpg" width="1000" height="600">
        </center>
    </body>
</html>

```

lal.html

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Lalbagh
        </title>
    </head>
    <body>
        <h1 align="center">
            Lalbagh
        </h1>
        <p>
            Lalbagh Botanical Garden or simply Lalbagh, is a botanical garden in Bangalore, India, with an over 200-year history. First planned and laid out during the dalavaiship of King Hyder Ali, the garden was later managed under numerous British Superintendents before Indian Independence.
        </p>
        <center>
        <br>
        <img src="lal.jpg" width="1000" height="600">
        </center>
    </body>
</html>
```

bs.html

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Banashankari
        </title>
    </head>
    <body>
        <h1 align="center">
            Banashankari
        </h1>
        <p>
            Banashankari, commonly abbreviated as BSK, is a locality spread across South and West Bangalore. Its name is derived from the Banashankari Amma Temple on Kanakapura Road, one of Bangalore's renowned temples constructed by Subramanya Shetty in 1915.
        </p>
        <center>
        <br>
        <img src="bs.jpeg">
        </center>
    </body>
</html>
```

palace.html

```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Bengaluru Palace
        </title>
    </head>
    <body>
        <h1 align="center">
            Bengaluru Palace
        </h1>
        <p>
            Bangalore Palace is a 19th century royal palace located in Bangalore, Karnataka, India, built in an area that was owned by the Rev. John Garrett, the first principal of the Central High School in Bangalore.
        </p>
        <center>
        <br>
        <img src="palace.jpg">
        </center>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (47)-1.png>)

![alt text](<Screenshot (48).png>)

![alt text](<Screenshot (49).png>)

![alt text](<Screenshot (50).png>)

![alt text](<Screenshot (51).png>)

![alt text](<Screenshot (52).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
