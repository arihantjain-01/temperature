<!DOCTYPE html>
<html lang="en">
<head>
   <link href="temper.css" rel="stylesheet">

    <title>temperature</title>
</head>
<body>
<div class="outer">
    <form>
        <div class="contvert">
            <h1>Temperature Converter</h1>
            <label>Celsius</label>
            <input type="number" id="celsius" oninput="cc()">
            <br><br>            
            <label>Fahrenheit</label>
            <input type="number" id="fahrenheit" oninput="ff()">
            <br><br>  
            <label>Kelvin</label>
            <input type="number" id="kelvin" oninput="kk()">
            <script src="temper.js"></script>
        </div>               
    </form>
</div>
</body>
</html>
