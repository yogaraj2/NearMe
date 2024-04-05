# Ex04 Places Around Me
## Date: 5-4-2024

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
    <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>
         </h1>
         <h3 align="center">
            <font color="blue"><b> YOGARAJ .S(212223040248)</b></font>
         </h3>
         <center>
            <img src="IMG1.png" usemap="#MYCITY" height="650" width="1400">
            <map name="MYCITY">
                <area shape="rect" coords="740,350,780,380" href="fort.html" title="VELLORE FORT">
                <area shape="rect" coords="835,10,938,78" href="college.html" title="VELLORE INSTITUTE OF TECHNOLOGY">
                <area shape="rect" coords="457,548,621,604" href="temple.html" title="SRI LAKSHMI NARAYANI GOLDEN TEMPLE">
                <area shape="rect" coords="790,300,820,350" href="hospital.html" title="CMC HOSPITAL">
                <area shape="rect" coords="1100,190,1157,250" href="dmart.html" title="D Mart">
            </map>
         </center>
    </body>
</html>

college.html


<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="pink">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="green"><b>College</b></font>
</h2>
<hr size="3" color="blue">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>VELLORE INSTITUTE OF TECHNOLOGY:</i></u></h>
<u1>

<li>It was established under Section 3 of the University Grants Commission (UGC) Act, 1956, and was founded in 1984 as a
     self-financing institution called the Vellore Engineering College.</li>
<li>The Union Ministry of Human Resources Development conferred University status on Vellore Engineering College in 2001.</li>
<li>The University is headed by its founder and Chancellor, Dr. G. Viswanathan, a former Parliamentarian and Minister in the Tamil 
    Nadu Government.</li>
<li> In recognition of his service to India in offering world class education, he was conferred an honorary doctorate by the
     West Virginia University, USA. Mr.Sankar Viswanathan, Dr.Sekar Viswanathan and Dr.G.V. Selvam are the Vice-Presidents;
      Dr. Rambabu Kodali is the Vice-Chancellor and Dr. Partha Sharathi Mallick is the Pro-Vice Chancellor I/C.</li>


<u1>

<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>


</font>
</p>
</body>
</head>
</html>

dmark.html

<html>
<head>
<title>Dmart</title>
</head>

<body bgcolor="lavender">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="green"><b>Dmart</b></font>
</h2>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>DMART:</i></u></h>
<ul>
<li>DMart is a one-stop supermarket chain that aims to offer customers a wide range of basic home and personal products under one roof.</li>
<li>Each DMart store stocks home utility products - including food, toiletries, beauty products, garments, kitchenware, bed and bath linen, home appliances and more - available at competitive prices that our customers appreciate. Our core objective is to offer customers good products at great value.</li>
<li>DMart was started by Mr. Radhakishan Damani and his family to address the growing needs of the Indian family.</li>
<li>From the launch of its first store in Powai in 2002, DMart today has a well-established presence in 365 locations across Maharashtra, Gujarat, Andhra Pradesh, Madhya Pradesh, Karnataka, Telangana, Chhattisgarh, NCR, Tamil Nadu, Punjab and Rajasthan. With our mission to be the lowest priced retailer in the regions we operate, our business continues to grow with new locations planned in more cities.</li>
<li>The supermarket chain of DMart stores is owned and operated by Avenue Supermarts Ltd. (ASL). The company has its headquarters in Mumbai.

    The brands D Mart, D Mart Minimax, D Mart Premia, D Homes, Dutch Harbour, etc are brands owned by ASL.</li>
</ul>
<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>

</font>
</p>
</body>
</head>
</html>
 
 fort.html

 <html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="pink">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="Blue"><b>VELLORE FORT</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>VELLORE FORT :</i></u></h>
<u1>
<li>The fort was constructed by then the rule Bommu Nyakar and his brother during 1526-1595 AD</li>
<li>The first against the brithish in india broke out in vellore fort tippu mahal,hyder mahal,condy mahal,badhusha mahaland the begam mahal inside the fort</li>
<li>The fort at vellore is one of the great attractions in the district.</li>
<li>the fort was occupied by the brithish in 1760 and used as a military garrison.</li>
</u1>
<style>
    .centerimage{
    display: block;
    margin-left:auto;
    margin-right: auto;
    }
</style>
     
</font>
</p>
</body>
</head>
</html>

hospital.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="yellow">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>HOSPITAL</b></font>
</h2>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>CMC HOSPITAL :</i></u></h>
<u1>
<li>An Unending Dedication to Excellence in Research, Education, and Service.</li>
<li>The Christian Medical College (CMC) in Vellore was founded in 1900 as a one-room clinic by Dr. Ida S. Scudder, the only daughter of second-generation American missionaries.</li>
<li>People from around the world visit CMC to get world-class care, delivered with honesty, fairness, compassion, and integrity.</li>
<li>CMC's excellence continues with advances in research and an evolving curriculum aimed at transforming India's promising medical students into creative and compassionate healthcare providers.</li>
<li>CMC has come a long way from its humble start as a one-room clinic, growing into one of India's most prestigious private hospitals and medical schools.</li>
<li> Today, CMC cares for over two million patients and trains one thousand doctors, nurses and other medical professionals each year.</li> 
</u1>


<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>

</font>
</p>
</body>
</head>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="orange">
<h1 align="center" >
<font color="red"><b>VELLORE</b></font>
</h1>
<h2 align="center">
<font color="green"><b>TEMPLE</b></font>
</h2>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="4">
<i><u><h>GOLDEN TEMPLE-SRIPURAM:</i></u></h>
<u1>

<li>The temple is located on 100 acres of land and has been constructed by the Vellore-based charitable trust, Sri Narayani Peedam, headed by its spiritual leader Sri Sakthi Amma also known as 'Narayani Amma'.</li>
<li> The temple with its gold (1500 kg) covering, has intricate work done by artisans specialising in temple art using gold.</li>
<li>Every single detail was manually created, including converting the gold bars into gold foils and then mounting the foils on copper.
<li> Gold foil from 9 layers to 10 layers has been mounted on the etched copper plates.</li>
<li> Every single detail in the temple art has significance from the vedas.</li>
</u1>


<style>
.centerimage{
display: block;
margin-left:auto;
margin-right: auto;
}
</style>

</font>
</p>
</body>
</head>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-04-05 203349.png>)

![alt text](<Screenshot 2024-04-05 203404.png>)

![alt text](<Screenshot 2024-04-05 203416.png>)

![alt text](<Screenshot 2024-04-05 203432.png>)

![alt text](<Screenshot 2024-04-05 203447.png>)

![alt text](<Screenshot 2024-04-05 203500.png>)
## RESULT
The program for implementing image maps using HTML is executed successfully.
