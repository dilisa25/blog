<style>
    body {
      font-family: 'Times New Roman', sans-serif;
      background-color: #fafafa;
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.7;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    }

    h2 {
      text-align: center;
      color: #6c5ce7;
      font-size: 2em;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.05em;
      margin: 18px 0;
    }

    strong {
      color: #6c5ce7;
    }

    img {
      width: 100%;
      border-radius: 12px;
      margin: 20px 0;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    .quote {
      background-color: #f3f0ff;
      border-left: 4px solid #6c5ce7;
      padding: 15px 20px;
      font-style: italic;
      border-radius: 8px;
      margin: 25px 0;
    }

    footer {
      text-align: center;
      font-size: 0.9em;
      color: #777;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      .container {
        margin: 20px;
        padding: 15px;
      }
      h2 {
        font-size: 1.6em;
      }
    }
  </style>
<body>

  <div class="container">
    <h2>Debugging</h2>
    <br>
    <br>
    <p>Debugging is the process of finding and identifying errors in your code that are preventing it from working, and then making the correct fixes. The term “debugging” actually originated in 1947 when a real bug got stuck inside a computer, which caused issues. The computer had to be physically “debugged,” and the name stuck. Debugging requires patience, observation, attention to detail, logical reasoning, and the willingness to acknowledge possible mistakes.</p>

Most bugs fall into these types of errors:

Syntax errors: the code literally cannot run because it breaks Python’s rules.

Runtime errors: the program starts but crashes while running when it hits an error.

Logic errors: the program runs without crashing but gives the wrong output.

User errors: the user enters an invalid or unexpected input.

<p>When I debug, I start by predicting what the code should do. Usually, the terminal in VS Code shows the error and the line it’s coming from, which helps with syntax or runtime issues. If it’s a logic error, it’s important to look closely at what the code is actually producing. From there, I go through each line, figure out where things go wrong, and fix it. It important not just to fix the bug, but to understand why it happened so I can avoid similar mistakes in the future.</p>
    
<br>
<p>For this debugging exercise, I worked through four code snippets, each with with types of errors.Below is a breakdown of each snippet, the problems I found, the reasoning behind my fixes, and what I learned from debugging them
<p>
```python
temperature = 75

if temperature > 80:
    print("It's hot")
elif temperature > 50:
    print("It's temperate")
elif temperature < 0:
    print("It's cold")

```
</body>



    
      

    