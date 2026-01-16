<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Currency Converter</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h2>💱 Currency Converter</h2>

    <input type="number" id="amount" placeholder="Enter amount" value="1">

    <select id="fromCurrency">
        <option value="USD">USD - Dollar</option>
        <option value="EUR">EUR - Euro</option>
        <option value="IQD">IQD - Iraqi Dinar</option>
        <option value="GBP">GBP - Pound</option>
        <option value="TRY">TRY - Turkish Lira</option>
        <option value="JPY">JPY - Yen</option>
    </select>

    <select id="toCurrency">
        <option value="USD">USD - Dollar</option>
        <option value="EUR">EUR - Euro</option>
        <option value="IQD">IQD - Iraqi Dinar</option>
        <option value="GBP">GBP - Pound</option>
        <option value="TRY">TRY - Turkish Lira</option>
        <option value="JPY">JPY - Yen</option>
    </select>

    <button onclick="convert()">Convert</button>

    <div class="result" id="result"></div>
</div>

<script src="script.js"></script>
</body>
</html>