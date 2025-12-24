# Website-Index.html
Website index.hml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyToken Info</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.jsdelivr.net/npm/ethers@5.7.2/dist/ethers.min.js"></script>
</head>
<body>
    <div class="container">
        <h1>MyToken Info</h1>
        <p><strong>Token Address:</strong> <span id="tokenAddress"></span></p>
        <p><strong>Name:</strong> <span id="tokenName"></span></p>
        <p><strong>Symbol:</strong> <span id="tokenSymbol"></span></p>
        <p><strong>Total Supply:</strong> <span id="totalSupply"></span></p>
        <p><strong>Your Balance:</strong> <span id="userBalance"></span></p>
        <button id="connectButton">Connect Wallet</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
