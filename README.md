# Ex04 Places Around Me
# Date : 15.11.2023
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
## main.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Mapping an Image</title>
</head>
<body>
    <h1><Center> EXNO:4 IMAGE MAP</Center></h1>
<h1><Center>Divya S -212221040042</Center></h1>

<img src="map3.png" usemap="#nearme">

<map name="nearme">
    <area  title="Deco" href="http://127.0.0.1:5501/exp4wp/static/Deco.html" coords="17,12,663,311" shape="rect">
    <area  title="Rohini" href="http://127.0.0.1:5501/exp4wp/static/Rohini.html" coords="678,11,1409,319" shape="rect">
    <area  title="AGS" href="http://127.0.0.1:5501/exp4wp/static/AGS.html" coords="16,332,663,597" shape="rect">
    <area  title="Temp" href="http://127.0.0.1:5501/exp4wp/static/vadatemp.html" coords="688,356,1558,829" shape="rect">
    <area  title="aya temp" href="http://127.0.0.1:5501/exp4wp/static/Ayapan.html" coords="1567,367,1818,841" shape="rect">
</map>
</body>
</html>

```
## AGS.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>AGS Cinemas</title>
</head>
<body style="background-color: rgb(189, 101, 219);">
    <h1><Center>Welcome to AGS Cinemas<Center></h1>
    
    <h2>Now Showing Movies</h2>
    <ul>
        <li>Kandukondain Kandukondain</li>
        <li>Nanban</li>
        <li>Dear Zindagi</li>
    </ul>
    
    <h2>Showtimes</h2>
    <p>Kandukondain Kandukondain : 11:00 AM, 4:30 PM, 8:00 PM</p>
    <p>Nanban : 12:00 PM, 2:45 PM, 9:15 PM</p>
    <p>Dear Zindagi: 12:30 PM, 4:00 PM, 9:30 PM</p>
    
    <h2>Facilities</h2>
    <ul>
        <li>Comfortable seating</li>
        <li>State-of-the-art audio and visual technology</li>
        <li>Concession stand with snacks and drinks</li>
    </ul>
</body>
</html>

```

## Ayapan.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Ayappan Temple</title>
</head>
<body style="background-color: rgb(219, 166, 101);"></body>
    <h1><Center>Welcome to Ayappan Temple</Center></h1>
    <h2>Upcoming Pujas and Festivals</h2>
    <ul>
        <li>Mandala Pooja</li>
        <li>Swamye Saranam Ayyappa Festival</li>
        <li>Padi Pooja and Makaravilakku</li>
    </ul>
    
    <h2>Temple Timings</h2>
    <p>Monday - Saturday: 4:00 AM - 11:00 AM, 5:00 PM - 9:00 PM</p>
    <p>Sunday: 4:00 AM - 12:00 PM, 5:00 PM - 9:30 PM</p>
    
</body>
</html>

```
## Demo.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Decathlon Sports Store</title>
</head>
<body style="background-color: rgb(101, 156, 219);"></body>
    <h1><Center>Welcome to Decathlon Sports Store</Center></h1>
    <h2>Featured Products</h2>
    <ul>
        <li>Running Shoes</li>
        <li>Cycling Gear</li>
        <li>Tennis Rackets</li>
    </ul>
    
    <h2>Store Hours</h2>
    <p>Monday - Friday: 9:00 AM - 8:00 PM</p>
    <p>Saturday: 10:00 AM - 6:00 PM</p>
    <p>Sunday: Closed</p>
    
</body>
</html>

```
## Rohini.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Rohini Silver Screen Theater</title>
</head>
<body style="background-color: rgb(132, 219, 101);"></body>
    <h1><Center>Welcome to Rohini Silver Screen Theater</Center></h1>
    <h2>Now Showing Movies</h2>
    <ul>
        <li>Leo</li>
        <li>Alai Payuthey</li>
        <li>Spider-Man</li>
    </ul>
    
    <h2>Showtimes</h2>
    <p>Leo Showtimes: 10:00 AM, 2:30 PM, 7:00 PM</p>
    <p>Alai Payuthey Showtimes: 11:00 AM, 3:45 PM, 8:15 PM</p>
    <p>Spider-Man Showtimes: 12:30 PM, 4:00 PM, 9:30 PM</p>
    
</body>
</html>

```
## vadatemp.html
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Alurumugi Murugan Vadapalani Temple</title>
</head>
<body style="background-color: rgb(219, 215, 101);"></body>
    <h1>Welcome to Alurumugi Murugan Vadapalani Temple</h1>
    <h2>Upcoming Events</h2>
    <ul>
        <li>Thaipusam Festival</li>
        <li>Panguni Uthiram Celebration</li>
        <li>Monthly Bhajans</li>
    </ul>
    
    <h2>Temple Timings</h2>
    <p>Weekdays: 6:00 AM - 12:00 PM, 4:00 PM - 9:00 PM</p>
    <p>Weekends: 6:00 AM - 9:30 PM</p>
    <p>Please check the calendar for special event timings.</p>
    
</body>
</html>

```
## OUTPUT
![image](https://github.com/divz2711/NearMe/assets/121245222/5f78f07f-dc7b-498d-b7cf-23e3dc116bda)
![image](https://github.com/divz2711/NearMe/assets/121245222/28863d11-c049-431e-bfe7-6da32faf7e49)
![image](https://github.com/divz2711/NearMe/assets/121245222/cf30638f-9f1d-4438-9c25-38f8b3a517a0)
![image](https://github.com/divz2711/NearMe/assets/121245222/81b68551-3353-4e8a-8791-6754663d2731)
![image](https://github.com/divz2711/NearMe/assets/121245222/688eec2c-97a1-4aba-92dd-474e2156c792)
![image](https://github.com/divz2711/NearMe/assets/121245222/8c7bdb4d-d507-4324-a8fa-cf5e8adc9650)


## RESULT
The program for implementing image maps using HTML is executed successfully.
