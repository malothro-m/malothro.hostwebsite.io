<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        main {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
        }
        h1, h2 {
            color: #444;
        }
        .project {
            border: 1px solid #ddd;
            border-radius: 8px;
            background: #fff;
            margin-bottom: 1.5rem;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .project h3 {
            margin-top: 0;
        }
        .project a {
            color: #0073e6;
            text-decoration: none;
        }
        .project a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            margin-top: 2rem;
            padding: 1rem;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Explore my projects and work below</p>
    </header>
    <main>
        <section class="project">
            <h3>Multi-Digit Handwritten Number Recognition</h3>
            <p>
                Developed a CRNN model for recognizing sequences of handwritten digits using data augmentation, CNN encoders, and bidirectional LSTM decoders. 
                This project focuses on applications like OCR and sequence recognition.
            </p>
            <a href="https://github.com/malothro-m/Digit-Recognizer" target="_blank">View Project</a>
        </section>
        <section class="project">
            <h3>Land Use and Land Cover Image Analysis</h3>
            <p>
                Built a land classification model using Random Forest in Google Earth Engine to classify satellite imagery into land-use categories.
                This project highlights geospatial analysis for environmental monitoring and urban planning.
            </p>
            <a href="https://github.com/malothro-m/Land-Use-and-Land-cover-Image-analysis" target="_blank">View Project</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
