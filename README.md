# BIC21203 Lab 4a: Client-Side Scripting (JavaScript)

## Student Information

 **Name:** Fitri Shah Rahmat Shah
 **Student ID:** AI250098
**Course:** BIC21203 Web Development

## Introduction
This lab is about JavaScript functions, events, conditions, loops, and DOM manipulation. The objective is to learn how to create interactive webpages using JavaScript.

## Question 1: Interactive Text Changer
### Description
This program changes a paragraph when the user clicks the Change Message button.

The original message is "Welcome to my website!". After clicking the button, the message changes to "Hello there!".

### Concepts Used

- getElementById()
- JavaScript functions
- addEventListener()
- textContent

### How to Run

1. Open the Q1 folder.
2. Open index.html in a web browser.
3. Click the Change Message button.
4. The message will change to "Hello there!".

### Output Screenshot
<img width="940" height="425" alt="image" src="https://github.com/user-attachments/assets/aeccddaf-caf1-4988-89db-be605d674674" />
<img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/2df4e9df-f596-4901-86e0-fd8412013923" />

## Question 2: Smart Number Validator

### Description
This program allows users to enter a number and checks whether it is lower than, higher than, or equal to 10. It also checks for empty or invalid input.

### Concepts Used

- JavaScript functions
- if...else if...else
- isNaN()
- Number()
- textContent
- addEventListener()

 ### How to Run

1. Open the Q2 folder.
2. Open index.html in a web browser.
3. Enter a number in the input field.
4. Click the Check button.
5. The validation message will appear below the input field.

### Test Cases 

| Input | Expected Output |
|---|---|
| 3 | The number is lower than 10 |
| 10 | The number is equal to 10 |
| 13 | The number is higher than 10 |
| abc | Please enter a valid number! |
| Empty input | Please enter a valid number! |
| 10.5 | The number is higher than 10 |

### Output Screenshot
<img width="940" height="537" alt="image" src="https://github.com/user-attachments/assets/7431c9bf-4fdb-4e0c-997e-38b216f921d6" />
<img width="940" height="486" alt="image" src="https://github.com/user-attachments/assets/fd023313-ffbf-4b93-aaff-c3ca86787a7b" />
<img width="940" height="518" alt="image" src="https://github.com/user-attachments/assets/15df1d9d-39dd-4bec-98f4-a4f8683bfadd" />
<img width="940" height="458" alt="image" src="https://github.com/user-attachments/assets/9533ddaa-9970-4ba3-8f4d-9ba473a4c41c" />
<img width="940" height="484" alt="image" src="https://github.com/user-attachments/assets/432b0d31-f428-44bb-9490-07f2af40efa8" />
<img width="940" height="527" alt="image" src="https://github.com/user-attachments/assets/0af97e7d-8698-4b3e-bd96-d7eec5c803ea" />

## Question 3: Dynamic Number Generator

### Description
This program generates an ordered list of numbers from 1 to 5 when the user clicks the Generate button. The existing list is cleared before generating new items to prevent duplicates.

### Concepts Used

- JavaScript functions
- for loop
- document.createElement()
- textContent
- appendChild()
- addEventListener()

 ### How to Run

1. Open the Q3 folder.
2. Open index.html in a web browser.
3. Click the Generate button.
4. The webpage will display numbers from 1 to 5.
5. Click Generate again to check that duplicate items are not created.

### Expected Output

1. The number is 1
2. The number is 2
3. The number is 3
4. The number is 4
5. The number is 5

### Output Screenshot
<img width="940" height="555" alt="image" src="https://github.com/user-attachments/assets/ce4bba57-7f1d-4aeb-884f-21140cbdb7a6" />
<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/68d2a843-dc9a-4069-b243-c5f72c4b0d0f" />

## Conclusion
Through this lab, I learned how to use JavaScript to make webpages interactive. I learned how to use functions and event listeners to respond to button clicks. I also learned how to validate user input using conditional statements and generate list items using a for loop. This lab improved my understanding of JavaScript and DOM manipulation.
