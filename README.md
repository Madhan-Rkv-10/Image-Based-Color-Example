<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Color Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        h1 {
            text-align: center;
            color: #444;
        }
        p {
            margin-bottom: 20px;
        }
        .image-container {
            text-align: center;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>Dynamic Color Example</h1>
    <p>
        This example demonstrates the use of the <code>ColorScheme.fromImageProvider</code> API in Flutter to dynamically
        generate a color scheme based on the content of selected images. Users can switch between light and dark themes
        and view how the color scheme adapts based on the chosen image.
    </p>
    <div class="image-container">
        <img src="output/output.gif" alt="Dynamic Color Example Output" >
    </div>
    <h2>Features</h2>
    <ul>
        <li>Dynamic color scheme generation from image content.</li>
        <li>Toggle between light and dark themes.</li>
        <li>Responsive UI for both small and large screens.</li>
    </ul>
    <h2>Installation & Usage</h2>
    <p>
        To run this Flutter project locally, follow these steps:
    </p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/Madhan-Rkv-10/Image-Based-Color-Example.git</code></pre>
        <li>Navigate to the project directory and install dependencies:</li>
        <pre><code>flutter pub get</code></pre>
        <li>Run the app on a connected device or emulator:</li>
        <pre><code>flutter run</code></pre>
    </ol>
    <h2>License</h2>
    <p>
        This project is licensed under the MIT License. See the LICENSE file for more details.
    </p>
</div>
</body>
</html>
