# Places Around Me

## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
Step 1:
Create a Django project abd app.

Step 2:
create the html and css files based on your place in the image.

Step 3:
Define new function in views file.

Step 4:
Import views files and define the paths in urls file.

Step 5:
Run the server

## Code:
```
<!DOCTYPE html>
{% load static %}
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.map.com</title>
    <link rel="stylesheet" href=static/css/map.css>
    <style>
        body{
             background:url('static/images/map.png');
             background-repeat:no-repeat;
             background-attachment: fixed;
        }
    </style>
</head>
<body>
    <ul>
   <a href="temple.html"> <li  id="temple">TEMPLE</li> </a>
    
   <a href="home.html">    <li id="home">HOME</h3> </li></a>
    <a href="church.html">   <li  id="church">Church</h3> </li></a>
    <a href="school.html">   <li  id="school">School</h3> </li></a>
    <a href="park.html">   <li  id="park">Park</h3> </li></a>
            
            </ul> 

   
    
</body>
</html>

```

## Output:
![webpage](https://user-images.githubusercontent.com/118707079/215282745-074ae25b-3a92-49cc-9aa7-eb815c021787.png)

![validator](https://user-images.githubusercontent.com/118707079/215282720-0ad055a0-53c0-42d0-a9c6-9512bf00f846.png)


## Result:
The experiment was executed successfully.
