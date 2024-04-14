# Ex04 Places Around Me
## Date: 14/04/24
## Name: VAISHNAVIDEVI V
## Reg No: 212223040230
## Dept: CSE

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

## CODE:
```
map.html
<html>
    <head>
        <title>PLEASANT CITY</title>
    </head>
    <body bgcolor="lilblue">
        <h1 align="center">
            <font color="black"><b>KARAIKUDI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>V.VAISHNAVIDEVI(212223040230)</b></font>
        </h3>
        <center>
            <img src="mapk.png" usemap="#PLEASANTCITY" height="630" width="1500">
            <map name="PLEASANTCITY">
                <area shape="rect" coords="700,250,850,400" href="town.html" title="AAYIRAM JANNAL VEEDU">
                <area shape="circle" coords="570,240,45" href="palace.html" title="KANADUKATHAN PALACE">
                <area shape="circle" coords="550,220,45" href="university.html" title="ALAGAPPA CHETTIAR">
                <area shape="rect" coords="920,360,55" href="food.html" title="CHETTINAD FOODS">
                <area shape="rect" coords="950,120,1100,140" href="temple.html" title="TAMILTHAI KOVIL">

            </map>
        </center>
    </body>
</html>   
```
```
town.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="violet">
        <h1 align="center">
            <font color="dangerred">AAYIRAM JANNAL VEEDU</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <img src="download (1).jpeg" usemap=#aayiramjannalveedu height="300" width="400">
            <img src="AAA.jpg" usemap=#aayiramjannalveedu height="300" width="400">
            <img src="AA.jpeg" usemap=#aayiramjannalveedu height="300" width="400">
            <br>
            
            <font face="Georgia" size="6">

                Aayiram Jannal Veedu is a famous landmark in the town of Karaikudi. The literal translation of the name of the place means the house with a thousand windows;a very apt name for a house that has thousand windows!!!
                
                
                The house is very famous among the tourists who make it a point to visit the place when in Karaikudi. In fact, once in the town, simply ask anyone for directions to the house. Built in 1941 on 20,000 square feet of area, the house is very spacious and costed 1 lakh 25 thousand at the time, a meager sum of money now. The house has 25 huge rooms and five very large halls. There are some 20 doors in the house along with 1000 windows.



            </font>
        </p>
    </body>
</html>

```
```
palace.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="lilblue">
        <h1 align="center">
            <font color="white">KANADUKATHAN PALACE</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <img src="kkk.jpg" usemap=#kanadukathanpalace height="300" width="600">
            <img src="k2.jpeg" usemap=#kannadukathanpalace height="300" width="400">
            <img src="k1.jpeg" usemap=#kanadukathanpalace height="300" width="400"><br>
            <font face="Georgia" size="5">
                This palace was built by Rajah Sir Annamalai Chettiar in 1912. With so many beautiful ornamental details it took seven years to complete the construction of the palace. This palace exposes the traditional Chettinad architecture
                This palace is the composite of art, architecture and tradition. As an example, it exposes the cultural facets of Chettinadu people. The wishes of Chettiars are found elsewhere throughout the structure. Ornamental lights, teak wood materials, glasses, marbles, carpets and crystals were imported from overseas for the construction of the building. In spite of that it has different types of arts and styles in unique way
                On the palace grounds there is a vast courtyard used for carrying out many functions such as marriage or religion oriented rituals. On one corner the puja room of the wife of Annamalai Chettiar, where she did puja for so many years is found. In this palace many valuable items and households used by the family are kept safeThis palace has a car shed, with 1990 sq.ft. Nine cars could be parked there. Lift is also available
            </font>
        </p>
    </body>
</html>


```
```
university.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="brown">ALAGAPPA CHETTIAR</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <img src="alagu3.jpeg" usemap=#alagappachettair height="300" width="600">
            <img src="alagappa.jpeg" usemap=#alagappachettair height="300" width="400">
            <img src="alga2.jpeg" usemap=#alagappachettair height="300" width="400"><br>
            <font face="Georgia" size="5">
                Alagappa University has emerged from<b> the galaxy of institutions initially founded during 1950`s</b> by the Padma Bhushan ,<b>   Dr. RM. Alagappa Chettiar</b> (06.04.1909 - 05.04.1957). Alagappa University is a State Government University established by <b>    an Act of the Tamil Nadu State Legislature in 1985 as Unitary type</b>; later became Affiliating type during 2002. The University is situated at Karaikudi<b> (in 420 acre lush green campus)</b>, in the District of Sivaganga, in the State of Tamil Nadu.
                Alagappa University was brought into existence by a Special Act of the Government of Tamil Nadu in May 1985 with the objective of <b>fostering research, development and dissemination of knowledge in various branches of learning</b>. Alagappa University is recognized by the University Grants Commission (UGC) of India. The University has 44 Departments, 3 Academic Centres and 2 Constituent Colleges (AUCE, AUCPE) on its campus. 45 Colleges located in the districts of Sivaganga and Ramanathapuram are Affiliated to the University. The University is offering UG & PG programmes in the four Faculties (Arts, Science, Education, Management).
The University offers education through Regular, Distance, Online and Collaborative modes. Through all modes of education, the University caters to the needs of the student community of around 1.12 lakhs.

As a member of the Association of Indian Universities (AIU), as well as the member of the Association of Commonwealth Universities (ACU), it has rewarding relations with other academic institutions, research laboratories and industrial establishments that promise a spectacular future.
            </font>
        </p>
    </body>
</html>
```
```
food.html

<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red">CHETTINAD FOODS</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <img src="FOODS.jpeg" usemap=#thanthaiperiyarnagar height="300" width="400">
            <img src="f4.jpg" usemap=#thanthaiperiyarnagar height="300" width="400">
            <img src="F2.jpeg" usemap=#thanthaiperiyarnagar height="300" width="350">
            <img src="F3.jpeg" usemap=#thanthaiperiyarnagar height="300" width="310">
            <br>
            <font face="Georgia" size="5">
                Karaikudi is extremely famous for its spicy dishes. The unique kind of culinary delicacies will blow you off your feet! Nothing stands next to the taste of<b>"Chettinady Samayal"</b>.People from around the world, flock into Karaikudi for its one-of-a-kind dishes. From traditional to fast food, you will find different types of food varieties in the city. The place is apt for foodies from all around the world. The awesome food in Karaikudi will make you visit the city several times.
                It is a world famous culinary, which has a<b> history of 200 years</b>. The world renowned dishes are made with a unique blend of spices and ingredients. Additionally, its traditional style of cooking sets it apart from many other cooking methods. Chettinadu Samayal techniques are handed down from several generations. Traditionally, <b>Chettinadu Samayal is also known as Achi Samayal</b>, which is done using a special kind of firewood. People believe that fumes from the firewood enhances the food's final taste and smell.
                <b>"One is lucky to eat like a Chettiar"</b>, they say in the Southern part of the country. Chettiar food is a feast in itself. Their hospitality is legendary. Known for its spices and aromatic nature, Karaikudi has an endless collection of non vegetarian meals. The place is filled with restaurants that master the preparation of scrumptious dishes with hot, freshly grounded masalas
            </font>
        </p>
    </body>
</html>

```
```
temple.html
<html>
    <head>
        <title>MY HOME TOWN</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center">
            <font color="darkblue">TAMILTHAI KOVIL</font>
        </h1>
        <hr size="3" color="pink">
        <p align="justify">
            <img src="t4.jpeg" usemap=#thanthaiperiyarnagar height="300" width="350">
            <img src="t2.jpeg" usemap=#thanthaiperiyarnagar height="300" width="400">
            <img src="t3.jpeg" usemap=#thanthaiperiyarnagar height="300" width="350">
            <img src="t1.jpeg" usemap=#thanthaiperiyarnagar height="300" width="310">
            <br>
            <font face="Georgia" size="5">
               <b>TAMIL THAI</b>refers to the allegorical and sometimes anthropomorphic personification of the Tamil language as a mother.
               The concept became popular in the Tamil-speaking world after the publication of a song invoking and praising Tamil mother in a play titled, <b>"Manonmaniyam"</b>, written by<b> Manonmaniam Sundaram Pillai</b>
               It is the only temple in the <b>world for worshipping a language as a goddess</b>.The temple is situated inside the <b>Kamban Mani Mandabam</b>, and the street in which the temple is located has been named Tamil Thai Kovil Street.
               The idea of establishing such a temple was conceived by Kamban Adippodi Saw Ganesan the founder of Kamban Kazhagam. The Tamil Thai temple was declared open in 1993, by Karunanidhi. The main shrine is for Tamil Thai. On either side of the idol of Tamil Thai, there are smaller idols of<b> Agathiyar and Tolkappiyar</b>. Outside the main shrine are icons of<b> Oli Thai (the goddess of sound) and Vari Thai (the goddess of verses)</b>. There are separate enclosures for<b> Kamban, Ilango Adigal, and Thiruvalluvar. V. Ganapati Sthapati,</b> temple architect and builder from Karaikudi, designed, constructed, and did the sculpturing work of the temple.
            </font>
        </p>
    </body>FOO
</html>

```


## OUTPUT:

 MY HOME TOWN:
 
![home](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/2cb721b9-1c99-4804-a44a-edec7247793e)

AAAYIRAM JANNAL VEEDU:

![1000](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/9ff03b10-996f-482f-8aef-3535b0b30b3b)

KANADUKATHAN PALACE:

  ![kanadukathan](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/9d4e53e6-0028-435a-82e3-ce1d908f8dbc)

  ALAGAPPA UNIVERSITY:

  ![alagappa](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/2e2c6d89-2293-4d59-885b-a65445f97a0e)

 CHETTINAD FOODS:

 ![food](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/f7343580-3356-44a7-8bcf-cafae65da1ae)

 TAMILTHAI TEMPLE:

 ![TAMILTHAI ](https://github.com/vaishnavidevi23013992/NearMe/assets/151864235/9a6ec42d-f6e8-4003-91e4-d7844198cf2d)



  











## RESULT
The program for implementing image maps using HTML is executed successfully.
