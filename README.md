<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhinav's High-Tech Projects</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        /* General Styling */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #2c3e50, #34495e);
            color: white;
            overflow-x: hidden;
        }

        header {
            background: rgba(0, 0, 0, 0.7);
            color: #f39c12;
            padding: 40px 20px;
            text-align: center;
            font-size: 3em;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* Project Section Styling */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
            gap: 30px;
            padding: 40px;
        }

        .project-box {
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
            color: white;
            height: 350px;
            position: relative;
        }

        .project-box:hover {
            transform: translateY(-10px);
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.2);
        }

        .project-box .icon {
            font-size: 40px;
            color: #f39c12;
            position: absolute;
            top: -30px;
            right: 20px;
        }

        .project-box h3 {
            font-size: 1.8em;
            margin: 20px 0;
        }

        .project-box p {
            font-size: 1.2em;
            line-height: 1.6;
        }

        .project-box a {
            text-decoration: none;
            color: #f39c12;
            font-size: 1.1em;
            font-weight: bold;
            position: absolute;
            bottom: 20px;
            left: 20px;
        }

        .project-box a:hover {
            color: #e67e22;
        }

        /* Footer Section */
        .footer {
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            margin-top: 60px;
        }

        .footer a {
            color: #f39c12;
            text-decoration: none;
            font-weight: bold;
            margin: 0 10px;
        }

        .footer a:hover {
            color: #e67e22;
        }

        /* Feedback Form Styling */
        .feedback-form {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 30px;
            color: white;
            border-radius: 10px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.3);
            width: 90%;
            max-width: 500px;
            margin: 40px auto;
            display: block;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 10;
            display: none; /* Initially hidden */
        }

        .feedback-form input,
        .feedback-form textarea {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .feedback-form button {
            background-color: #f39c12;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }

        .feedback-form button:hover {
            background-color: #e67e22;
        }

        /* Mobile Styling */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        Abhinav's High-Tech Projects
    </header>

    <div class="container">
        <div class="project-box">
            <div class="icon">🎮</div>
            <h3>Project 1: Quiz App</h3>
            <p>A dynamic quiz app that lets users test their knowledge across different categories.</p>
            <a href="https://abhinav2000-18.github.io/QUIZ-BY-ABHINAV/" target="_blank">View Project</a>
        </div>

        <div class="project-box">
            <div class="icon">📊</div>
            <h3>Project 2: BGT Match Scoreboard</h3>
            <p>Get live updates for the Border-Gavaskar Trophy 2024 with real-time scores.</p>
            <a href="https://abhinav2000-18.github.io/BGT-Match-4-Day-2-Scoreboard/" target="_blank">View Project</a>
        </div>

        <div class="project-box">
            <div class="icon">📈</div>
            <h3>Project 3: Cricket Updates</h3>
            <p>Latest cricket statistics, scores, and news at your fingertips!</p>
            <a href="https://abhinav2000-18.github.io/CRICKET-UPDATES.2/" target="_blank">View Project</a>
        </div>

        <div class="project-box">
            <div class="icon">🏏</div>
            <h3>Project 4: Retired Cricketers 2024</h3>
            <p>A tribute to the cricketers who retired in 2024, showcasing their career statistics.</p>
            <a href="https://abhinav2000-18.github.io/CRICKETS-THAT-RETIRED-THIS-YEARS/" target="_blank">View Project</a>
        </div>
    </div>

    <div class="footer">
        <p>Produced by Abhinav | All Rights Reserved © 2024</p>
        <p>Contact for feedback: <a href="mailto:abhinavsingh262012@gmail.com">abhinavsingh262012@gmail.com</a></p>
    </div>

    <div class="feedback-form" id="feedbackForm">
        <h2>Rate Our Projects</h2>
        <label for="name">Your Name:</label>
        <input type="text" id="name" placeholder="Enter your name" required>
        
        <label for="rating1">Project 1 Rating (0-10):</label>
        <input type="number" id="rating1" min="0" max="10" placeholder="Enter rating for Project 1" required>
        
        <label for="rating2">Project 2 Rating (0-10):</label>
        <input type="number" id="rating2" min="0" max="10" placeholder="Enter rating for Project 2" required>
        
        <label for="rating3">Project 3 Rating (0-10):</label>
        <input type="number" id="rating3" min="0" max="10" placeholder="Enter rating for Project 3" required>
        
        <label for="rating4">Project 4 Rating (0-10):</label>
        <input type="number" id="rating4" min="0" max="10" placeholder="Enter rating for Project 4" required>

        <button onclick="submitFeedback()">Submit Feedback</button>
    </div>

    <script>
        // Show the feedback form after a few seconds
        setTimeout(function() {
            document.getElementById("feedbackForm").style.display = 'block';
        }, 3000);

        function submitFeedback() {
            const name = document.getElementById("name").value;
            const rating1 = document.getElementById("rating1").value;
            const rating2 = document.getElementById("rating2").value;
            const rating3 = document.getElementById("rating3").value;
            const rating4 = document.getElementById("rating4").value;

            if (name && rating1 && rating2 && rating3 && rating4) {
                alert("Thank you for your feedback, " + name + "!");
                document.getElementById("feedbackForm").style.display = 'none';
            } else {
                alert("Please fill in all the fields.");
            }
        }
    </script>
</body>
</html>
