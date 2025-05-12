# Ex.05 Design a Website for Server Side Processing
## Date:13.5.25

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>SURFACE AREA OF RIGHT CYLINDER</title>
<h2 align="center">JEEVANANDAM M</h2>
<h3 align="center">212222220017</h3>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background-color: rgb(207, 155, 59);
}
.edge {
    width: 100%; /* Set width to 100% */
    display: flex;
    justify-content: center; /* Center the content horizontally */
    align-items: center; /* Center the content vertically */
    height: 100vh; /* Set height to 100% of the viewport height */
}
.box {
    border: Thick dashed rgb(193, 117, 18);
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: pink;
    padding: 20px; /* Add padding for better appearance */
}
.formelt {
    color: black;
    text-align: center;
    margin-top: 7px;
    margin-bottom: 6px;
}
h1 {
    color: black;
    text-align: center;
    padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>SURFACE AREA OF RIGHT CYLINDER </h1>
        <form method="POST">
            {% csrf_token %}
            <div class="formelt">
                Radius : <input type="text" name="Radius" value="{{ r }}"></input>(in m)<br/>
            </div>
            <div class="formelt">
                Height : <input type="text" name="height" value="{{ h }}"></input>(in m)<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"></input><br/>
            </div>
            <div class="formelt">
                Area : <input type="text" name="area" value="{{ area }}"></input>m<sup>2</sup><br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>



```


## SERVER SIDE PROCESSING:
![Screenshot 2025-04-28 113453](https://github.com/user-attachments/assets/74d59d9f-5615-4bd5-9166-3155f1b6a6b6)


## HOMEPAGE:
![Screenshot 2025-05-13 001055](https://github.com/user-attachments/assets/3d24137b-863f-4a0b-87ca-62d7f3dec4b3)


## RESULT:
The program for performing server side processing is completed successfully.
