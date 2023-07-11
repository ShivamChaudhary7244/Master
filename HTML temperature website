<!DOCTYPE html>
<html>
<head>
  <title>Temperature Converter</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    
    h1 {
      color: #333;
    }
    
    input {
      margin: 10px;
      padding: 5px;
      width: 200px;
    }
    
    button {
      padding: 5px 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    
    #result {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Temperature Converter</h1>
  <input type="number" id="temperature" placeholder="Enter temperature">
  <br>
  <button onclick="convertToCelsius()">Convert to Celsius</button>
  <button onclick="convertToFahrenheit()">Convert to Fahrenheit</button>
  <div id="result"></div>
  
  <script>
    function convertToCelsius() {
      var temperatureInput = document.getElementById("temperature").value;
      
      if (!isNaN(temperatureInput)) {
        var temperatureCelsius = (temperatureInput - 32) * 5 / 9;
        document.getElementById("result").innerHTML = temperatureInput + " °F = " + temperatureCelsius.toFixed(2) + " °C";
      } else {
        document.getElementById("result").innerHTML = "Invalid input!";
      }
    }
    
    function convertToFahrenheit() {
      var temperatureInput = document.getElementById("temperature").value;
      
      if (!isNaN(temperatureInput)) {
        var temperatureFahrenheit = temperatureInput * 9 / 5 + 32;
        document.getElementById("result").innerHTML = temperatureInput + " °C = " + temperatureFahrenheit.toFixed(2) + " °F";
      } else {
        document.getElementById("result").innerHTML = "Invalid input!";
      }
    }
  </script>
</body>
</html>
