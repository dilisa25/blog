
# Debugging

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20190902105053/Debugging-Tips-To-Get-Better-At-It.png" alt="debugging">

Debugging is the process of finding and identifying errors in your code that are preventing it from working, and then making the correct fixes. The term “debugging” actually originated in 1947 when a real bug got stuck inside a computer, which caused issues. The computer had to be physically “debugged,” and the name stuck. Debugging requires patience, observation, attention to detail, logical reasoning, and the willingness to acknowledge possible mistakes.

Most bugs fall into these types of errors:

- **Syntax errors:** The code cannot run because it breaks Python’s rules.
- **Runtime errors:** The program starts but crashes when it hits an error.
- **Logic errors:** The program runs but gives the wrong output.
- **User errors:** The user enters invalid or unexpected input.

When I debug, I start by predicting what the code should do. Usually, the terminal in VS Code shows the error and the line it’s coming from, which helps with syntax or runtime issues. For logic errors, I examine the output closely to see where it goes wrong. From there, I work through each line, identify the mistake, and fix it. 

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
### What It Was Supposed to Do
Count how many spaces are in the given string
### Problem

### My Thought Process and Solution

## Code Snippet 2

```python
print("give me a number")
n = input()

for num in range(1, n):
    if num % 2 < 0:
        print(num, "is even.")
    else:
        print(num, "is odd.")
```
### What It Was Supposed to Do
Determine if numbers 1 to n are even or odd 
### Problem

### My Thought Process and Solution

## Code Snippet 3
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
### What It Was Supposed to Do
Calculate the factorial of a given number
### Problem
### My Thought Process and Solution


## Code Snippet 4
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

### What It Was Supposed to Do
Ask user to enter the correct password but only give them 3 attempts
### Problem

### My Thought Process and Solution


# Conclusion 
Working through these coding challenges made me realize just how many different types of bugs can cause errors in your code. There are small syntax errors that prevent the program from running, runtime errors that only appear when the code is executed, and logic errors that happen when a developer accidentally writes code that returns unintended output. Even errors caused by the user can create issues. 

One important lesson I learned is that debugging isn’t just about fixing the error, it’s about understanding why the error happened. So if it happens again, I know exactly how to address it.

 As I worked through each snippet and read the code line by line, I was able to isolate each issue and apply a structured fix. As my projects grow more complex, my experience with debugging will make it much easier to handle in the real world.
