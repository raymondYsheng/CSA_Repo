---
layout: default
title: Raymond Sheng Blog
---
<style>
  input  
  {  
  width: 20px;  
  background-color: white;
  color: black;
  border: 3px solid gray;  
      border-radius: 5px;  
      padding: 26px;  
      margin: 5px;  
      font-size: 15px;  
  }
  #clear
  { 
    width: 270px;  
    border: 3px solid gray;  
    border-radius: 3px;  
    padding: 20px;  
    color: blue;  
  }
  #calc{  
    width: 270px;  
    border: 3px solid black;  
    border-radius: 3px;  
    padding: 20px;  
  }  
  

  
</style>
<html>
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/03fcccb9-e6ca-4f75-b00c-408ac15ce7d6' width="250">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/227c1f2d-c74e-4239-b062-7fd054684ccb' width="500" height="490">

<body>
  <h1>Calculator</h1>
  
<div class="calculator-grid">
<form name = "form1">  
      
  <input id = "calc" type ="text" name = "answer"> <br> <br>

  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">  
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">  
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">  
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">  
  <br> <br>  
    
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">  
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">  
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">  
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">  
  <br> <br>  

  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">  
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">  
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">  
  <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">  
  <br> <br>  
    
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">  
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">  
  <input type = "button" value = "." onclick = "form1.answer.value += '.' ">  

  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">  
  <br>   
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >  
  <br>   
    
</form>  
</div>
  
</body>
</html>

| Class Name | Teacher    |
|------------|------------|
| CSA        | Mortenson  |
| AP Stats   | Edelstein  |
| APEL       | West       |
| APUSH      | Swanson    |
| AP Bio     | Cheskaty   |

