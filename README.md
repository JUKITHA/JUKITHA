<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HBL Template</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>House Bill of Lading</h1>
        <form id="hblForm">
            <div class="form-group">
                <label for="shipper">Shipper:</label>
                <input type="text" id="shipper" name="shipper" required>
            </div>
            <div class="form-group">
                <label for="consignee">Consignee:</label>
                <input type="text" id="consignee" name="consignee" required>
            </div>
            <div class="form-group">
                <label for="notifyParty">Notify Party:</label>
                <input type="text" id="notifyParty" name="notifyParty" required>
            </div>
            <div class="form-group">
                <label for="vessel">Vessel:</label>
                <input type="text" id="vessel" name="vessel" required>
            </div>
            <div class="form-group">
                <label for="voyage">Voyage:</label>
                <input type="text" id="voyage" name="voyage" required>
            </div>
            <div class="form-group">
                <label for="portOfLoading">Port of Loading:</label>
                <input type="text" id="portOfLoading" name="portOfLoading" required>
            </div>
            <div class="form-group">
                <label for="portOfDischarge">Port of Discharge:</label>
                <input type="text" id="portOfDischarge" name="portOfDischarge" required>
            </div>
            <div class="form-group">
                <label for="goodsDescription">Description of Goods:</label>
                <textarea id="goodsDescription" name="goodsDescription" required></textarea>
            </div>
            <div class="form-group">
                <label for="quantity">Quantity:</label>
                <input type="number" id="quantity" name="quantity" required>
            </div>
            <div class="form-group">
                <label for="grossWeight">Gross Weight:</label>
                <input type="text" id="grossWeight" name="grossWeight" required>
            </div>
            <div class="form-group">
                <label for="measurements">Measurements:</label>
                <input type="text" id="measurements" name="measurements" required>
            </div>
            <button type="submit">Generate HBL</button>
        </form>
    </div>
    <script src="script.js"></script>
</body>
</html>
