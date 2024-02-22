<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rotary Window Data Input</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Rotary Window Data Input</h1>
        <form id="rotaryWindowForm">
            <div class="form-group">
                <label for="windowDiameter">Window Diameter (inches):</label>
                <input type="number" id="windowDiameter" name="windowDiameter" required>
            </div>
            <div class="form-group">
                <label for="glassThickness">Glass Thickness (inches):</label>
                <input type="number" id="glassThickness" name="glassThickness" required>
            </div>
            <div class="form-group">
                <label for="frameMaterial">Frame Material:</label>
                <select id="frameMaterial" name="frameMaterial" required>
                    <option value="">Select Material</option>
                    <option value="aluminum">Aluminum</option>
                    <option value="wood">Wood</option>
                    <option value="vinyl">Vinyl</option>
                </select>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>


