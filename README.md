<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot and Risk Prediction Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        header {
            background: #4caf50;
            color: white;
            padding: 10px 0;
            text-align: center;
            border-radius: 8px;
        }
        section {
            background: white;
            border-radius: 8px;
            margin: 20px 0;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table th, table td {
            padding: 12px;
            border: 1px solid #ddd;
            text-align: left;
        }
        table th {
            background: #4caf50;
            color: white;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
        }
        a {
            color: #4caf50;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chatbot and Risk Prediction Platform</h1>
    </header>
    <section>
        <h2>🤖 Chatbot Functionality</h2>
        <p>
            The chatbot is built using the <strong>T5 model</strong>, fine-tuned on a dataset of <strong>4,825 question-answer pairs</strong>. It provides accurate and personalized responses to pregnant women about symptoms, precautions, and potential risks.
        </p>
    </section>
    <section>
        <h2>🩺 Risk Prediction Model</h2>
        <p>
            A deep neural network model predicts health risks for pregnant women. Users can input personal data such as:
        </p>
        <ul>
            <li>🌡️ Temperature</li>
            <li>👩‍🦳 Age</li>
            <li>❤️ Heart rate</li>
        </ul>
        <p>The model classifies risks into three categories:</p>
        <ul>
            <li>✅ Low Risk</li>
            <li>⚠️ Medium Risk</li>
            <li>❗ High Risk</li>
        </ul>
    </section>
    <section>
        <h2>📋 Technology Stack</h2>
        <table>
            <thead>
                <tr>
                    <th>Component</th>
                    <th>Technology</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Backend</td>
                    <td>Django Framework</td>
                </tr>
                <tr>
                    <td>Frontend</td>
                    <td>Django Templates</td>
                </tr>
                <tr>
                    <td>Chatbot Model</td>
                    <td>T5 (fine-tuned)</td>
                </tr>
                <tr>
                    <td>Risk Prediction Model</td>
                    <td>Deep Neural Networks</td>
                </tr>
            </tbody>
        </table>
    </section>
    <footer>
        <p>
            Developed by <a href="mailto:your-email@example.com">Your Name</a> | 
            <a href="https://github.com/yourusername">GitHub Profile</a>
        </p>
    </footer>
</body>
</html>
