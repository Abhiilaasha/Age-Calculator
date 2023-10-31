# Age-Calculator
[Link to the Site](https://superlative-naiad-eed992.netlify.app)




<!DOCTYPE html>
<html>
<head>
    <title>Age Calculator README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007BFF;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        h2 {
            font-size: 24px;
            margin-top: 20px;
        }

        p {
            font-size: 18px;
            line-height: 1.5;
        }

        code {
            font-family: 'Courier New', monospace;
            background-color: #f5f5f5;
            padding: 2px 5px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }

        .demo {
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Age Calculator</h1>
        <p>An interactive age calculator using HTML, CSS, and JavaScript.</p>
    </header>
    <div class="container">
        <h2>About</h2>
        <p>This project is a simple web-based age calculator that allows you to calculate your age based on your birthdate. It's built using HTML for structure, CSS for styling, and JavaScript for functionality.</p>

        <h2>How to Use</h2>
        <p>To calculate your age, follow these steps:</p>
        <ol>
            <li>Open the <code>index.html</code> file in your web browser.</li>
            <li>Enter your birthdate in the input field.</li>
            <li>Click the "Calculate Age" button.</li>
            <li>Your age will be displayed below the button.</li>
        </ol>

        <h2>Example</h2>
        <div class="demo">
            <label for="birthdate">Enter your birthdate:</label>
            <input type="date" id="birthdate">
            <button onclick="calculateAge()">Calculate Age</button>
            <p id="result"></p>
        </div>

        <h2>Contributing</h2>
        <p>If you'd like to contribute to this project or report issues, please feel free to fork the repository and submit pull requests or issues on GitHub.</p>

        <h2>License</h2>
        <p>This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.</p>
    </div>
</body>
</html>

