# Ex04 Places Around Me
## Date:09-04-2024 

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
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>VELLORE</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>JAYAPRIYA (212221220022)</b></font>
        </h3>
        <center>
            <img src="VELLORE.png" usemap="#MyCity" height="510" width="1050">
            <map name="MyCity">
                <area shape="rect" coords="50,50,400,300" href="fort.html" title="VELLORE FORT">
                <area shape="circle" coords="50,50,400,400" href="temple.html" title="JALAGENDESHWARAR TEMPLE">
                <area shape="rect" coords="50,50,400,400" href="park.html" title="PERIYAR PARK">
                <area shape="rect" coords="500,500,1328,1691" href="park2.html" title="VELLORE PARK">
            </map>
        </center>
    </body>
</html>
```
FORT.HTML
```

<!DOCTYPE html>
<html lang="en">
    <head>
        <title></title>
    </head>
    <body bgcolor="cyan">
    <h1 align="center">
    <font color="black"><b>Vellore</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>VELLORE FORT</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justify">
    <font face="Georgia" size="5">
       1) Vellore Fort is a large 16th-century fort situated in heart of the Vellore city, in the state of Tamil Nadu.
       2) India built by the Emperors of Vijayanagara.
       3) The fort was at one time the imperial capital of the Aravidu Dynasty of the Vijayanagara Empire.</font>
    </p>
    </body>
</html>
```
PARK.HTML
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title></title>
    </head>
    <body bgcolor="cyan">
    <h1 align="center">
    <font color="black"><b>Vellore</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>PERIYAR PARK</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justify">
    <font face="Georgia" size="5">
        1)The park is a repository of rare, endemic, and endangered flora and fauna.
        2)The major watershed of two important rivers of Kerala: the Periyar and the Pamba. 
        3)The park is located high in the Cardamom Hills and Pandalam Hills of the south Western Ghats along the border with Tamil Nadu.</font>
    </p>
    </body>
</html>
```
PARK2.HTML
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title></title>
    </head>
    <body bgcolor="cyan">
    <h1 align="center">
    <font color="black"><b>Vellore</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>VELLORE PARK</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justify">
    <font face="Georgia" size="5">
        1)Vellore Fort Park is an attractive park in the Vellore Fort premises. 
        2)It is a garden that spans a vast area of land that is covered with a carpet of the well-maintained grass. 
        3)The whole park is spacious due to its location in the fort.</font>
    </p>
    </body>
</html>
```
TEMPLE.HTML
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title></title>
    </head>
    <body bgcolor="cyan">
    <h1 align="center">
    <font color="black"><b>Vellore</b></font>
    </h1>
    <h3 align="center">
    <font color="purple"><b>VELLORE PARK</b></font>
    </h3>
    <hr size="3" color="white">
    <p align="justify">
    <font face="Georgia" size="5">
        1)Vellore Fort Park is an attractive park in the Vellore Fort premises. 
        2)It is a garden that spans a vast area of land that is covered with a carpet of the well-maintained grass. 
        3)The whole park is spacious due to its location in the fort.</font>
    </p>
    </body>
</html>
```


## OUTPUT



<img width="609" alt="VELLORE" src="https://github.com/Jayapriya242/NearMe/assets/114279259/aec01d36-f4c3-4cfc-9deb-e29f3daede8e">
<img width="959" alt="Screenshot 2024-04-09 101923" src="https://github.com/Jayapriya242/NearMe/assets/114279259/393b8a55-5587-4208-ab08-5ef225c12b69">
<img width="960" alt="Screenshot 2024-04-09 101651" src="https://github.com/Jayapriya242/NearMe/assets/114279259/8c47e91d-8525-43bb-92bc-603310446eef">
<img width="960" alt="Screenshot 2024-04-09 101710" src="https://github.com/Jayapriya242/NearMe/assets/114279259/6f589978-3eb5-4ed5-b6b2-d7a17cde036d">
<img width="960" alt="Screenshot 2024-04-09 101546" src="https://github.com/Jayapriya242/NearMe/assets/114279259/32557b0b-b63d-4aeb-b9bd-688df8c8518a">


## RESULT
The program for implementing image maps using HTML is executed successfully.
