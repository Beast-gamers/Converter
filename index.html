<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alphabet and Expression Converter</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(to right, #74ebd5, #ACB6E5); /* Gradient background */
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ensures the background covers the entire viewport */
        }
        .container {
            max-width: 900px;
            background: #ffffff;
            border-radius: 15px; /* Rounded corners */
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); /* Enhanced shadow */
            padding: 30px; /* More padding for a spacious feel */
            overflow: hidden; /* Hide overflow in container */
        }
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 30px; /* Adds more space below the header */
        }
        h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
            margin-bottom: 20px; /* Adds space below the sub-header */
        }
        input, textarea, button {
            padding: 12px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
            font-size: 16px;
            transition: all 0.3s ease; /* Smooth transition for hover effects */
        }
        textarea {
            height: 120px;
            resize: vertical;
            width: calc(100% - 22px);
        }
        .button-group {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .button-group button {
            margin: 0 5px;
            flex: 1;
        }
        button.convert-button {
            background-color: #28a745; /* Convert button is green */
            color: white;
        }
        button.convert-button:hover {
            background-color: #218838; /* Darker green on hover */
        }
        button.copy-button {
            background-color: #007bff; /* Copy button is blue */
            color: white;
        }
        button.copy-button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
        button:focus {
            outline: none;
        }
        button.success {
            background-color: #28a745;
        }
        button.success::before {
            content: '✓ ';
        }
        .pre-container {
            max-width: 100%;
            overflow: hidden; /* Prevent horizontal overflow */
        }
        pre {
            background: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 15px;
            max-width: 100%; /* Prevent horizontal stretching */
            overflow: auto; /* Add scrollbars if needed */
            max-height: 300px; /* Limit height to stretch vertically */
            font-family: 'Courier New', Courier, monospace;
            color: #333;
            box-sizing: border-box; /* Ensure padding and border are included in width and height */
        }
        .clear-button {
            background-color: #dc3545;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease; /* Smooth hover effect */
        }
        .clear-button:hover {
            background-color: #c82333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Alphabet and Code Converter</h1>

        <div>
            <h2>Convert Alphabets to Code</h2>
            <input type="text" id="inputText" placeholder="Enter alphabets">
            <div class="button-group">
                <button class="convert-button" id="convertTextButton" onclick="convertText()">Convert</button>
                <button class="copy-button" id="copyResultButton" onclick="copyToClipboard('result')">Copy</button>
                <button class="clear-button" onclick="clearInput('inputText')">Clear</button>
            </div>
            <div class="pre-container">
                <pre id="result"></pre>
            </div>
        </div>

        <div>
            <h2>Convert Code to Alphabets</h2>
            <textarea id="inputExpressions" placeholder="Enter code"></textarea>
            <div class="button-group">
                <button class="convert-button" id="convertExpressionsButton" onclick="convertExpressions()">Convert</button>
                <button class="copy-button" id="copyResultExpressionsButton" onclick="copyToClipboard('resultExpressions')">Copy</button>
                <button class="clear-button" onclick="clearInput('inputExpressions')">Clear</button>
            </div>
            <div class="pre-container">
                <pre id="resultExpressions"></pre>
            </div>
        </div>
    </div>

    <script>
        const expressions = [
            '[\' + "]', 
            '[\' - "]', 
            '[" - \']', 
            '[\' * "]', 
            '[\' / "]', 
            '[" / \']',
            '[\' + ""] * \']', 
            '[\' + ""] * "]', 
            '[\' - ""] * \']', 
            '[" - \'] * "]',
            '[\' + ""] / \']', 
            '[\' + ""] / "]', 
            '[\' - ""] / \']', 
            '[" - \'] / "]',
            '[\' + "] - "]', 
            '[\' - "] + "]', 
            '[\' * "] - "]', 
            '[" * "] / \']',
            '[\' / "] + "]', 
            '[" / "] * \']', 
            '[\' + "] / "]', 
            '[\' - "] * "]', 
            '[\' * "] + "]', 
            '[" * "] - "]',
            '[\' / "] - "]', 
            '[" / "] * \"]',
            '[" "]' // Equation for space
        ];

        function convertText() {
            const input = document.getElementById('inputText').value.toLowerCase();
            let result = '';

            for (let char of input) {
                if (char === ' ') {
                    result += '[" "]' + '°'; // Correct space handling
                } else if (char >= 'a' && char <= 'z') {
                    const index = char.charCodeAt(0) - 'a'.charCodeAt(0);
                    if (index >= 0 && index < expressions.length) {
                        result += expressions[index] + '°'; // Use ° as a separator
                    } else {
                        result += 'Expression not defined °';
                    }
                } else {
                    result += char + '°'; // Add unrecognized character directly followed by °
                }
            }

            document.getElementById('result').textContent = result.trim();
        }

        function convertExpressions() {
            const input = document.getElementById('inputExpressions').value.trim().split('°');
            let result = '';

            input.forEach(expression => {
                const trimmedExpression = expression.trim();
                if (trimmedExpression === '[" "]') {
                    result += ' ';
                } else {
                    const index = expressions.findIndex(exp => exp === trimmedExpression);
                    if (index !== -1) {
                        result += String.fromCharCode('a'.charCodeAt(0) + index);
                    } else {
                        result += trimmedExpression; // Add unrecognized expression directly without extra space
                    }
                }
            });

            document.getElementById('resultExpressions').textContent = result.trim();
        }

        function copyToClipboard(elementId) {
            const text = document.getElementById(elementId).textContent;
            navigator.clipboard.writeText(text).then(() => {
                const button = document.querySelector(`#copy${elementId.charAt(0).toUpperCase() + elementId.slice(1)}Button`);
                button.textContent = 'Copied';
                button.classList.add('success');
                setTimeout(() => {
                    button.textContent = 'Copy';
                    button.classList.remove('success');
                }, 2000);
            }).catch(err => {
                console.error('Error copying text: ', err);
            });
        }

        function clearInput(inputId) {
            document.getElementById(inputId).value = '';
        }
    </script>
</body>
</html>
