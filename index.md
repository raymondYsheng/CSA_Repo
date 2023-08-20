---
layout: default
title: Raymond Sheng Blog
---
<style>
    .image {
    float: left;
    margin-right: 20px;
  }
</style>

<html>
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/03fcccb9-e6ca-4f75-b00c-408ac15ce7d6' width="250">
    <img src='https://github.com/raymondYsheng/CSA_Repo/assets/142441804/227c1f2d-c74e-4239-b062-7fd054684ccb' width="500" height="490">

    <body>
      <h1>Simple Calculator</h1>
      
      <input type="text" id="display" readonly>
      
      <table>
          <tr>
              <td><button onclick="clearDisplay()">C</button></td>
              <td><button onclick="appendToDisplay('7')">7</button></td>
              <td><button onclick="appendToDisplay('8')">8</button></td>
              <td><button onclick="appendToDisplay('9')">9</button></td>
              <td><button onclick="appendToDisplay('+')">+</button></td>
          </tr>
          <tr>
              <td><button onclick="appendToDisplay('4')">4</button></td>
              <td><button onclick="appendToDisplay('5')">5</button></td>
              <td><button onclick="appendToDisplay('6')">6</button></td>
              <td><button onclick="appendToDisplay('-')">-</button></td>
          </tr>
          <tr>
              <td><button onclick="appendToDisplay('1')">1</button></td>
              <td><button onclick="appendToDisplay('2')">2</button></td>
              <td><button onclick="appendToDisplay('3')">3</button></td>
              <td><button onclick="appendToDisplay('*')">*</button></td>
          </tr>
          <tr>
              <td><button onclick="appendToDisplay('0')">0</button></td>
              <td><button onclick="calculate()">=</button></td>
              <td><button onclick="appendToDisplay('.')">.</button></td>
              <td><button onclick="appendToDisplay('/')">/</button></td>
          </tr>
      </table>
      
      <script>
          function appendToDisplay(value) {
              document.getElementById('display').value += value;
          }

          function clearDisplay() {
              document.getElementById('display').value = '';
          }

          function calculate() {
              try {
                  const expression = document.getElementById('display').value;
                  const result = eval(expression);
                  document.getElementById('display').value = result;
              } catch (error) {
                  document.getElementById('display').value = 'Error';
              }
          }
      </script>
    </body>
</html>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        text-align: center;
    }

    h1 {
        color: #333;
    }

    #display {
        width: 200px;
        height: 30px;
        font-size: 20px;
        margin: 10px;
    }

    table {
        margin: 0 auto;
        border-collapse: collapse;
    }

    td {
        padding: 10px;
    }

    button {
        width: 50px;
        height: 50px;
        font-size: 20px;
        background-color: #3498db;
        color: #fff;
        border: none;
        cursor: pointer;
    }

    button:hover {
        background-color: #2980b9;
    }
</style>

| Class Name | Teacher    |
|------------|------------|
| CSA        | Mortenson  |
| AP Stats   | Edelstein  |
| APEL       | West       |
| APUSH      | Swanson    |
| AP Bio     | Cheskaty   |

