# Ex04 Places Around Me
## Date: 
18.04.2024
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
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurants</title>
</head>
<script>
    function coord(event) {
        let x = event.clientX;
        let y = event.clientY;
        document.getElementById("txt1").value=x;
        document.getElementById("txt2").value=y;

    }
</script>
<body>
 
<img src="Map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Anjappar Chettinadu" title="Anjappar Chettinadu" href="https://www.anjappar.com/" coords="734,402,923,462" shape="rect">
    <area target="" alt="Dindigul Thalapakkati" title="Dindigul Thalapakkati" href="https://thalappakatti.com/" coords="727,516,632,442" shape="rect">
    <area target="" alt="Saangeetha Veg Restaurant" title="Saangeetha Veg Restaurant" href="https://www.sangeethaveg.com/" coords="472,422,613,476" shape="rect">

</map><br>
</body>
</html>

## OUTPUT
![alt text](<output 1.png>)
![alt text](<output 2.png>)
![alt text](<output 3.png>)
![alt text](<output 4.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
