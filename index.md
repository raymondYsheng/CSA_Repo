---
layout: default
title: Raymond Sheng Blog
---
<head>
<style>
  .calculator {
      width: 300px;
      margin: 0 auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      text-align: center;
      background-image: linear-gradient(blue, #7a55e0 100%);
  }
  input[type=button] {
	background:linear-gradient(to bottom, #b6bae3 5%, #415989 100%);
	background-color:#2e466e;
	border-radius:17px;
	border:1px solid #1f2f47;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Times New Roman;
	font-size:15px;
	padding:13px 15px;
	text-decoration:none;
}
  input[type=button]:hover {
	background:linear-gradient(to bottom, #415989 5%, #2e466e 100%);
	background-color:#415989;
}
  input[type=button]:active {
	position:relative;
	top:1px;
}
#calc {
  	padding:13px 15px;
}
</style>
</head>

<html>
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/03fcccb9-e6ca-4f75-b00c-408ac15ce7d6' width="250">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/227c1f2d-c74e-4239-b062-7fd054684ccb' width="500" height="490">

<body>
  <h1>Calculator</h1>

<div class="calculator">
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

  <input type = "button" value = "=" onclick = "calculate()">  
  <br><br>
  <input type = "button" value = "A/C" onclick = "form1.answer.value = ' ' " id= "clear" >  
  <br>   
  <script>
    function calculate() {
            try {
                form1.answer.value = eval(form1.answer.value);
            } catch (error) {
                form1.answer.value = 'Error';
            }
    }
  </script>
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

