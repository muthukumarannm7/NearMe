# Ex03 Places Around Me
## Date: 01-12-2025

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
html>
    <head>
        <title>My City</title>
    </head>
        <body>
            <h1 align="center" textcolor="red">Chennai City</h1><br>
            <h3 align="center" textcolor="blue">Muthukumran NM (25009369)</h3>
            <img src="City.png" usemap="#image-map" align="center">
             

            <map name="image-map">
                <area target="" alt="Chennai  Port" title="Chennai  Port" href="chennaiport.html" coords="1704,125,1870,177" shape="rect">
                <area target="" alt="Government Museum" title="Government Museum" href="museum.html" coords="1255,563,94" shape="circle">
                <area target="" alt="AGS" title="AGS" href="cinema.html" coords="152,604,322,682" shape="rect">
                <area target="" alt="Rail Museum" title="Rail Museum" href="railmuseum.html" coords="686,98,889,111,889,201,696,225,630,155" shape="poly">
                <area target="" alt="Marina Beach" title="Marina Beach" href="beach.html" coords="1629,762,103" shape="circle">
                </map>
        </body>
    
    

</html>

cinema.html

<html>
    <head>
        <title>
           AGS Cinema
        </title>

    </head>
    <body bgcolor="grey">
        <h1 align="center">Chennai</h1>
        <h2 align="center">MUTHUKUMARAN NM (25009369)</h2>
        <h3 align="center">AGS Cinema</h3>
        <hr>
        AGS Entertainment ventured into film production in 2006 with Susi Ganesan's Thiruttu Payale (2006),[1] which was followed by Santosh Subramaniam (2008), both emerging commercial successes.[2][3] Their subsequent productions included the masala flick Maasilamani (2009), Chimbudevan's Western comedy Irumbukkottai Murattu Singam (2010), the period piece Madrasapattinam, Bale Pandiya (2010), Myshkin's crime thriller Yuddham Sei (2011), Bala's comedy entertainer Avan Ivan (2011), Prabhu Deva directed romance film Engeyum Kadhal (2011), Vellore Maavattam (2011) starring Nandha, the K. V. Anand-Suriya project Maattrraan (2012) and Atlee directed sports action film Bigil (2019), while the distribution of films includes Kandhakottai, Inidhu Inidhu, Mynaa and Payanam.
        <map name="image-map">
            <area target="" alt="AGS" title="AGS" href="cinema.html" coords="152,604,322,682" shape="rect">
        </map>
    </body>
</html>

chennaiport.html

<html>
    <head>
        <title>Chennai Port</title>
    </head>
    <body bgcolor="grey">
        <h1 align="center">Chennai</h1>
        <h2 align="center">MUTHUKUMARAN NM (25009369)</h2>
        <h3 align="center">Chennai Port</h3>
        <hr>
        Chennai Port, formerly known as Madras Port, is the second largest container port of India, behind Mumbai's Jawaharlal Nehru Port also known as Nhava Sheva. The port is the largest one in the Bay of Bengal. It is the third-oldest port among the 12 major ports of India with official port operations beginning in 1881, although maritime trade started much earlier in 1639 on the undeveloped shore. It is an artificial and all-weather port with wet docks. Once a major travel port, it became a major container port in the post-Independence era. An established port of trade of British India since the 1600s, the port remains a primary reason for the economic growth of Tamil Nadu, especially for the manufacturing boom in South India, and has contributed greatly to the development of the city of Chennai.[3] It is due to the existence of the port that the city of Chennai eventually became known as the Gateway of South India.
        <map name="image-map">
                <area target="" alt="Chennai  Port" title="Chennai  Port" href="chennaiport.html" coords="1704,125,1870,177" shape="rect">
        </map>        
    </body>
</html>

beach.html

<html>
    <head>
        <title>Marina Beach</title>

    </head>
    <body bgcolor="grey">
        <h1 align="center">Chennai</h1>
        <h2 align="center">MUTHUKUMARAN NM (25009369)</h2>
        <h3 align="center">Marina Museum</h3>
        The Marina is a primarily sandy beach, with an average width of 300 m (980 ft)[5] and the width at the widest stretch is 437 m (1,434 ft). Bathing and swimming at the Marina are legally prohibited because of the dangers, as the undercurrent is very turbulent. It is one of the most crowded beaches in the country and attracts about 30,000 visitors a day during weekdays[6] and 50,000 visitors a day during the weekends and on holidays.[7][8][9] During summer months, about 15,000 to 20,000 people visit the beach daily.[10]
        <map name="image-map">
             <area target="" alt="Marina Beach" title="Marina Beach" href="beach.html" coords="1629,762,103" shape="circle">
                </map>
        </map>
    </body>
</html>

railmuseum.html

<html>
    <head>
        <title>
            Rail Museum
        </title>
    </head>
    <body bgcolor="lightblue">
        <h1 align="center">Chennai</h1>
        <h2 align="center">MUTHUKUMARAN NM (25009369)</h2>
        <h3 align="venter">Rail Museum</h3>
        <hr>
        The Chennai Rail Museum is a railway museum in Chennai, Tamil Nadu, India. The museum opened on 16 April 2002 in the Furnishing Division of the Integral Coach Factory (ICF) near Perambur. The 6.25-acre (2.53 ha) museum has technical and heritage exhibits, with a sizable collection of steam engines from the British Raj. It also has vintage coaches (such as Ooty trains), which were endemic on Indian railways. Most of the older models were manufactured by the North British Locomotive Company,[1] with some trains in the collection dating back more than a century.[2] Toy-train rides are available. There are 3 air-conditioned Indoor Galleries (ICF Gallery, Rail History Gallery, Art Gallery, 2 Other Non-airconditioned Galleries, a 90-seater air-conditioned Dolby Digital Movie Theatre (Railway and Railway Heritage Films), Natyarangam, Amphitheatre, a Number of Metal Sculptures made from scrap, 3D MURAL at the entrance, Cartoon Hero Characters better viewed from the Joyous Toy Train Ride, Rail Coach Restaurant, Eco Green Park, Lust Green vegetation, etc., The museum is managed and maintained by the ICF.
        <map name="image-map">
            <area target="" alt="Rail Museum" title="Rail Museum" href="railmuseum.html" coords="686,98,889,111,889,201,696,225,630,155" shape="poly">
        </map>
    </body>    
    

</html>

museum.html

<html>
    <head>
        <title>Government Museum</title>
    </head>
    <body bgcolor="grey" >
        <h1 align="center">Chennai</h1>
        <h2 align="center">MUTHUKUMARAN NM (25009369)</h2>
        <h3 align="center">Government Museum</h3>
        <hr>
        The Government Museum, Chennai, or the Madras Museum, is a museum of human history and culture located in the Government Museum Complex in the neighbourhood of Egmore in Chennai, India. Started in 1851, it is the second oldest museum in India after the Indian Museum in Kolkata. It has among the largest collection of Roman currency outside Europe.[1] The Museum Theatre is a central landmark of the museum.[2] The National Art Gallery is also present in the museum premises. Built in Indo-Saracenic style, it houses rare European and Asian painting of renowned artists, including Raja Ravi Varma.[3][4] It had 600,000 visitors in 2018. It has a large collection of bronze idols, 500 of them dating to 1000 BCE, in Asia
        <map name="image-map">
            <area target="" alt="Government Museum" title="Government Museum" href="museum.html" coords="1255,563,94" shape="circle">
        </map>
    </body>
</html>
```


## OUTPUT

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)
![alt text](image-5.png)







## RESULT
The program for implementing image maps using HTML is executed successfully.
