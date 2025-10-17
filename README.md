<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Interactive Web Page with JavaScript</h1>

    <!-- Part 1: Event Handling -->
    <section id="events">
        <h2>Event Handling</h2>
        <button id="clickBtn">Click Me!</button>
        <p id="clickMsg"></p>
        <div id="hoverBox">Hover over me!</div>
        <p id="hoverMsg"></p>
    </section>

    <!-- Part 2: Interactive Features -->
    <section id="interactive">
        <h2>Interactive Features</h2>
        <!-- Light/Dark Mode -->
        <button id="themeToggle">Toggle Light/Dark Mode</button>
        <p id="themeStatus">Current Mode: Light</p>

        <!-- Counter -->
        <div>
            <button id="decrease">-</button>
            <span id="counter">0</span>
            <button id="increase">+</button>
        </div>

        <!-- Collapsible FAQ -->
        <h3>FAQ Section</h3>
        <div class="faq">
            <p class="question">What is JavaScript?</p>
            <p class="answer">JavaScript is a programming language for web development.</p>
            <p class="question">What is the DOM?</p>
            <p class="answer">DOM stands for Document Object Model, it represents HTML as objects.</p>
        </div>
    </section>

    <!-- Part 3: Form Validation -->
    <section id="form-section">
        <h2>Form Validation</h2>
        <form id="myForm">
            <label>Name:</label>
            <input type="text" id="name" placeholder="Enter your name">
            <span class="error" id="nameError"></span>
            <br>

            <label>Email:</label>
            <input type="email" id="email" placeholder="Enter your email">
            <span class="error" id="emailError"></span>
            <br>

            <label>Password:</label>
            <input type="password" id="password" placeholder="Enter your password">
            <span class="error" id="passwordError"></span>
            <br>

            <button type="submit">Submit</button>
            <p id="formMsg"></p>
        </form>
    </section>

    <script src="script.js"></script>
</body>
</html>



