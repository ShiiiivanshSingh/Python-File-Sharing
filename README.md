<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTTP Server with QR Code</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        h1 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        h2 {
            color: #333;
            margin-top: 20px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 5px;
        }
        ol, ul {
            margin: 0 0 20px 20px;
        }
        li {
            margin-bottom: 10px;
        }
        code {
            background: #e9ecef;
            padding: 0.2em 0.4em;
            border-radius: 4px;
            font-size: 0.9em;
        }
        pre {
            background: #e9ecef;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
            white-space: pre-wrap;
        }
        .example {
            margin: 20px 0;
            text-align: center;
        }
        .example img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            border-top: 1px solid #ddd;
            font-size: 0.9em;
        }
        .footer a {
            color: #007bff;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Simple HTTP Server with QR Code</h1>
        <p>This project sets up a basic HTTP server using Python and generates a QR code for accessing the server locally.</p>
        
        <h2>How It Works</h2>
        <ol>
            <li>Sets up an HTTP server on port <code>8010</code>.</li>
            <li>Generates a QR code containing the server's local IP address and port.</li>
            <li>Displays the QR code and server information in the terminal.</li>
        </ol>
        
        <h2>Usage</h2>
        <p>To use this project, follow these steps:</p>
        <ol>
            <li>Clone this repository:</li>
            <pre><code>git clone https://github.com/your-username/your-repo.git</code></pre>
            <li>Navigate to the project directory:</li>
            <pre><code>cd your-repo</code></pre>
            <li>Run the script:</li>
            <pre><code>python your_script.py</code></pre>
            <li>Open the QR code image <code>myqr.svg</code> or visit the displayed URL in your browser.</li>
        </ol>
        
        <h2>Example QR Code</h2>
        <p>Here is an example of what the generated QR code might look like:</p>
        <div class="example">
            <img src="myqr.svg" alt="QR Code Example">
        </div>
        
        <h2>Requirements</h2>
        <ul>
            <li>Python 3.x</li>
            <li>pyqrcode</li>
            <li>python3-png (for PNG support)</li>
        </ul>
        
        <h2>License</h2>
        <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
    </div>
    <div class="footer">
        <p>© 2024 Your Name. All rights reserved.</p>
    </div>
</body>
</html>
