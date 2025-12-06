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

<div class="container">

# Debugging

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20190902105053/Debugging-Tips-To-Get-Better-At-It.png" alt="debugging">

Debugging is the process of finding and identifying errors in your code that are preventing it from working, and then making the correct fixes. The term “debugging” actually originated in 1947 when a real bug got stuck inside a computer, which caused issues. The computer had to be physically “debugged,” and the name stuck. Debugging requires patience, observation, attention to detail, logical reasoning, and the willingness to acknowledge possible mistakes.

Most bugs fall into these types of errors:

- **Syntax errors:** The code cannot run because it breaks Python’s rules.
- **Runtime errors:** The program starts but crashes when it hits an error.
- **Logic errors:** The program runs but gives the wrong output.
- **User errors:** The user enters invalid or unexpected input.

When I debug, I start by predicting what the code should do. Usually, the terminal in VS Code shows the error and the line it’s coming from, which helps with syntax or runtime issues. For logic errors, I examine the output closely to see where it goes wrong. From there, I work through each line, identify the mistake, and fix it. It's important not just to fix the bug, but understand why it happened so I can avoid similar issues in the future.

For this debugging exercise, I worked through four code snippets, each with different types of errors. Below is a breakdown of each snippet, the problems I found, the reasoning behind my fixes, and what I learned from debugging them.

---

## Code Snippet 1

```python
text = "Hello, world, my name is"
count = 0

for char in text:
    if char == "":
       count += 1

print(count)

```
Expected Purpose

(Explanation goes here…)

Problem

(Explanation goes here…)

Solution

(Explanation goes here…)

``` python
print("give me a number")
n = input()

for num in range(1, n):
    if num % 2 < 0:
        print(num, "is even.")
    else:
        print(num, "is odd.")

```

Expected Purpose

(Explanation goes here…)

Problem

(Explanation goes here…)

Solution

(Expanation goes here…)

```python
num = int(input("Enter an integer: "))

if num < -1:
  print("No negative numbers.")
else:
  result = 1
  for i in range(1, num):
    result *= i   

  print("Factorial of " + num + "is" + result)

```
Expected Purpose

(Explanation goes here…)

Problem

(Explanation goes here…)

Solution

(Expanation goes here…)

```python
attempts = 0
correct_password = "secret"

while True:
    password = input("Enter your password: ")
    attempts += 1

    if password == "incorrect_password":
        print("Correct password!")
    else:
        print("Incorrect password")

    if attempts > 3:
        print("Too many attempts")
        break

```
Expected Purpose

(Explanation goes here…)

Problem

(Explanation goes here…)

Solution

(Expanation goes here…)

## Conclusion




</div>


    
      

    