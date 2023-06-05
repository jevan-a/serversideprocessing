# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:

Clone the Repositary from GitHub.

### Step 2:

Create a Server Folder and then create my app.

### Step 3:

Input the codes from urls.py and settings.py.

### Step 4:

Create templates folder and create index.html file.

### Step 5:

Input the HTML Codes.
Successfully Completed.
### Step 6:

Publish the website in the given URL.

## PROGRAM :
 python
 ~~~
<html> 
<head> 
<meta charset='utf-8'> 
<meta http-equiv='X-UA-Compatible' content='IE=edge'> 
<title>Area of Rectangle</title> 
<meta name='viewport' content='width=device-width, initial-scale=1'> 
<style type="text/css"> 
body
{ 
background-color:rgb(150, 149, 149)
} 
.edge
{ 
width: 1080px;
margin-left:auto; 
margin-right:auto; 
padding-top:200px; 
padding-left:300px; 
} 
.box
{ 
display:block; 
border:Thick dashed red; 
width:500px; 
min-height:300px; 
font-size:20px;
background-color:rgba(90, 29, 102, 0.8); 
} 
.formelt{
color: rgb(22, 19, 19); 
text-align:center; 
margin-top:5px; 
margin-bottom:5px; 
} 
h1 
{
color: yellow; 
text-align:center; 
padding-top:20px; 
} 
</style> 
</head> 
<body>
<div class="edge"> 
<div class="box"> 
<h1>Area of a Rectangle</h1> 
<form method="POST">
{%csrf_token %}
<div class="formelt"> 
Length:<input type="text" name="length" value="{{l}}"></input>(in m)<br/> 
</div> 
<div class="formelt"> 
Breadth:<input type="text" name="breadth" value="{{b}}"></input>(in m)<br/> 
</div> 
<div class="formelt"> 
<input type="submit" value="Calculate"></input><br/> 
</div> 
<div class="formelt"> 
Area:<input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/> 
</div>
</form>
</div>
</div> 
</body>

~~~

## OUTPUT:
![Area of Rectangle](https://user-images.githubusercontent.com/103949835/213884296-e2b97fa0-85e8-4952-bda7-20ad7dc31d57.png)

### Home Page:
http://asokanjevan.student.saveetha.in:8000/areaofrectangle/

## Result:
Successfully Completed.
