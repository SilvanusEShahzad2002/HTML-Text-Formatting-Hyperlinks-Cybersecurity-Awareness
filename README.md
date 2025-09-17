# HTML-Text-Formatting-Hyperlinks-Cybersecurity-Awareness

# HTML Text Formatting & Safe Links

## What’s This About?

This is a basic example showing how to make text look good on a webpage—like making it bold, italic, or underlined—and how to add clickable links. It also includes some easy safety tips so your website stays safe when people click those links.

## What Will You Learn?

* How to make text bold, italic, or underlined using simple HTML tags.
* How to use headings and paragraphs to organize your content.
* How to add links that people can click to visit other pages or websites.
* How to keep links safe by using secure web addresses (https) and special settings that protect your site when links open in new tabs.

## What’s Inside?

* A file called `index.html` with all the example code you can open in your web browser.

## How to Use It

1. Open the `index.html` file on your computer using any web browser (like Chrome, Firefox, or Edge).
2. See how the text looks and try clicking the link to understand how it works.
3. Look at the code to learn how everything is done.

## Why Care About Safety?

When you add links, it’s important to make sure they don’t take your visitors to unsafe or fake websites. Using secure links (`https`) and some extra settings helps keep your visitors safe and stops bad things from happening when links open in new tabs.


Example Code

<!DOCTYPE html>
<html>
<head>
  <title>Intro to CSS & JavaScript</title>
  <style>
    /* CSS: Styling */
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      text-align: center;
      margin-top: 50px;
    }

    h1 {
      color: #333;
    }

    #message {
      font-size: 20px;
      color: blue;
      margin: 20px;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Web Page</h1>
  <p id="message">Click the button to change this text!</p>
  <button onclick="changeText()">Click Me</button>

  <script>
    // JavaScript: Interactivity
    function changeText() {
      const message = document.getElementById("message");
      message.innerHTML = " You clicked the button!";
      message.style.color = "green";
    }
  </script>

</body>
</html>

