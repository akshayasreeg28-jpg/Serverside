# Ex.05 Design a Website for Server Side Processing
## Date:29-09-2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
BMI = W/H<sup>2</sup>
<br> H --> Height (M)
<br> I --> Weight (Kg)

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

<body>
    <center>
    <h2>Body Mass Index (BMI) Calculator</h2>
    <form method="POST">
        {% csrf_token %}
        <label>Height (m):</label>
        <input type="text" name="height"><br>
        <label>Weight (kg):</label>
        <input type="text" name="weight"><br>
        <button type="submit">Calculate</button>
    </form>

    {% if BMI %}
    <h3>Your BMI is: {{ BMI }}</h3>
    {% endif %}
</body>

</html>
```

## SERVER SIDE PROCESSING:
![alt text](<Screenshot (22).png>)

## HOMEPAGE:

![alt text](<Screenshot (21).png>)
## RESULT:
The program for performing server side processing is completed successfully.
