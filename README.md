# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai
        </h1>
        <h3 align="center">
            <font colour='blue'><b> GOKUL D R (25017732)</b></font>
        </h3>
        <center>
            <img src="Screenshot 2025-10-05 115431.png" usemap="#mycity" alt="map" height="610" width="1450">
            <map name="mycity">
                <area shape="rect" coords="420,400,440,430" href="vamsha.html" title="Vamsha Maharaja">
                <area shape="rect" coords="805,350,830,375" href="thangamayil.html" title="Thangamayil Jewellery">
                <area shape="rect" coords="870,230,900,260" href="busstand.html" title="Mayiladuthurai Old Bus Stand">
                <area shape="rect" coords="835,113,860,138" href="aasife.html" title="Aasife Biriyani">
                <area shape="rect" coords="780,185,800,210" href="pams.html" title="Hotel PAMS">
            </map>
        </center>
    </body>
</html>

aasife.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai</b>
            </font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Aasife Biriyani</b>
            </font>
        </h2>
        <p align="center">
            <font> 
               Aasife Biriyani is a known restaurant in Mayiladuthurai, specializing in biriyani and offering a diverse menu that also includes South Indian, Chinese, Mughlai, and Chettinad cuisines, alongside various starters and beverages. The establishment in Mayiladuthurai is prominently located on State Bank Road, in the Pattamangalam area, and was established in the year 2017. It functions as a full-service dining spot, providing options for Dine-in, Pickup, Delivery, and In-Car ordering, and is generally open from 11:00 AM to 10:30 PM. The restaurant is well-regarded by many customers for its authentic cuisine, good presentation, and a nice ambiance, although some reviews have occasionally raised concerns about the quantity of food or customer service. The menu offers several varieties, including Chicken, Mutton, Prawn, Mushroom, and Veg Biriyani, along with different bucket options.  
            </font>
        </p>
    </body>
</html>

busstand.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai</b>
            </font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Old Bus Stand</b>
            </font>
        </h2>
        <p align="center">
            <font>
                The old bus stand in Mayiladuthurai is the Kamarajar Bus Stand, established by the Mayiladuthurai Municipality in the early 1960s. Located at the heart of the town on Gandhi Nagar, it historically served as the main transportation hub, connecting the town with northern and western districts. Despite the later addition of a second town bus stand near Varadachariar Park to manage some traffic flow, the Kamarajar bus stand continues to function as a crucial and overcrowded terminal. Originally designed for a much smaller volume, it now handles over a thousand trips daily, leading to significant congestion, especially in the surrounding areas. The age of the facility is evident in its poor maintenance and inadequate basic amenities like usable toilets and sufficient seating, which frequently draw complaints from commuters and local activists, even as the construction of a new, modern bus stand at Manakudi nears completion to finally alleviate the pressure on this vital, decades-old central hub.
            </font>
        </p>
    </body>
</html>

pams.html
html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai</b>
            </font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>HOTEL PAMS</b>
            </font>
        </h2>
        <p align="center">
            <font>
                PAMS Hotel is a well-established and popular business-class hotel in Mayiladuthurai, highly favored for its exceptionally convenient location, situated directly opposite the old bus stand in the Koranad area. Functioning since 1999, the hotel is a key accommodation option for both business travelers and pilgrims visiting the numerous temples in the region, offering a blend of comfort and accessibility. It provides a range of amenities expected of a modern hotel, including air-conditioned and spacious rooms, complimentary Wi-Fi, 24-hour room service, and ample free parking. The hotel also features an in-house multi-cuisine restaurant that serves a variety of North Indian, South Indian, and Continental dishes, with a complimentary breakfast often highlighted by guests. Beyond its lodging facilities, PAMS Hotel also caters to events with its banquet and mini-function halls.
            </font>
        </p>
    </body>
</html>

thangamayil.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai</b>
            </font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Thangamayil Maharaja</b>
            </font>
        </h2>
        <p align="center">
            <font>
               Thangamayil Jewellery is a prominent and well-known retail jewelry chain in South India, with a dedicated branch operating in Mayiladuthurai to cater to the local community's needs. The Mayiladuthurai showroom, which was a significant addition to the company's expanding network of over 60 stores across Tamil Nadu, offers a wide and varied collection of ornaments, specializing in Gold, Diamond, and Platinum jewelry. Customers can find traditional to trendy designs of bangles, necklaces, earrings, and more, all guaranteed for purity as the company holds a BIS hallmarking license. Beyond retail sales, the store provides popular customer-centric services, including various gold savings schemes like the Super Gold and Future Plus plans, and the digital DigiGold savings application, allowing residents of Mayiladuthurai to conveniently invest and save for their future jewelry purchases. The Mayiladuthurai branch is located in a prominent area, ensuring accessibility and providing personalized customer service.
            </font>
        </p>
    </body>
</html>

vamsha.html
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Mayiladuthurai</b>
            </font>
        </h1>
        <h2 align="center">
            <font color="blue"><b>Vamsha Maharaja</b>
            </font>
        </h2>
        <p align="center">
            <font>
                Vamsha Maharaja in Mayiladuthurai refers to a popular and well-established local retail business, specifically a clothing store named Vamsha - Maharaja Of Clothing.
                Located on Gandhiji Road in Koranad, this establishment specializes in a wide range of garments, including silk sarees, wedding collections, and various types of festive wear for men, women, and children.
                The name itself suggests a lineage or evolution, with promotional materials indicating "Maharaja to Vamsha Mayiladuthurai," highlighting a history of trust over twenty years, often in connection with Thiruvarur Maharaja Silks.
                The store is a major shopping destination for local residents, particularly during festive seasons like Diwali, offering a variety of apparel collections and special offers. 
            </font>
        </p>
    </body>
</html>




```
# OUTPUT
![alt text](<Screenshot 2025-10-07 213218.png>)
![alt text](<Screenshot 2025-10-07 213253.png>)
![alt text](<Screenshot 2025-10-07 213303.png>)
![alt text](<Screenshot 2025-10-07 213328.png>)
![alt text](<Screenshot 2025-10-07 213345.png>)
![alt text](<Screenshot 2025-10-07 213509.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
