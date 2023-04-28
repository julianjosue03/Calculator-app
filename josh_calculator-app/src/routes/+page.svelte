<!DOCTYPE html>  
<html lang = "en">  
<head>

<style>  
 
.formstyle  
{  
width: 300px;  
height: 490px;  
margin: auto;  
border: 3px solid black;  
border-radius: 15px;  
padding: 20px; 
padding-top:20px ; 
}  
  
   
input  
{  
width: 50px;
height: 80px;
background-color: lightgray;  
color: black;  
border-radius: 3px;  
padding: 34px;  
font-size: 20px;
font-weight: bold;

}  
  
input #calc {
	padding-top: 10px;
}
  
#calc{  
width: 250px;  
height: 50px;
border: 3px solid black;  
border-radius: 3px;  
padding: 20px;  
}  
  
</style>  
</head>  
<body>  
<div class= "formstyle">  
<form name = "form1">  
      
  <input id = "calc" type ="text" name = "answer"> <br> <br>   
  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">  
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">  
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">  
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">  
  <br> <br>  
    
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">  
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">  
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">  
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">  
  <br> <br>  
    
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">  
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">  
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">  
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">  
  <br> <br>  
    
  <input type = "button" value = "C" onclick = "form1.answer.value = ' ' " >   
   
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">  
       
  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">  
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' "> 
  <br>    
       
</form>  
</div>  
</body>  
</html>  