<!--

  There will be different types of tasks for each user story:
    `type: components`
    `type: css`
    `type: logic`
    `type: handlers`
    ...

-->

# 0.- Welcome page - INDEX.HTML

  When the user open the website will see.

## A) HEADER

### HTML

- H1

### CSS

- H1
    - Centered.
    - Font alignment: centered.

## B) MAIN SECTION

### HTML

- CONTAINER (.instructionContainer)
- P.
    - Instructions of the QUIZ's.

### CSS

- .questionContainer
    - BGcolor
    - Width
    - Padding
    - Boxshadow
    - Border radius
    - P
        - text-align: centered.

## C) BOTTOM SECTION

### HTML

- button
    - Hyperlink

### CSS

- BUTTON
    - Center aligned.
    - BGcolor: grey.
    - Border.

        - Hoover: transition fade out.

# 1.- QUESTION'S page - QUESTIONS.HTML

## A) SHOW QUESTIONS

### HTML

- DIV
    - Container for questions.

### CSS

- DIV (QUESTIONS)
    - Container Alignment
        - Centered.
    - Text align
        - Left

### BUSINESS LOGIC

- f(x) 'find the Question' -> Import from data access.
  
### HANDLER

- f(x) 'show the question' -> Import from business logic.

## B) SELECT ANSWER

### HTML

- DIV
    - Container for answers.

### CSS

- DIV (ANSWERS)
    - Container alignment: center.
    - P
        - Text alignment: Left
        - Hoover: border
        - color: gray.
            - Margin.

### BUSINESS LOGIC

- f(x) 'find the Answers' -> Import from data access.
  
### HANDLERS

{
    "MD013": false
}

- f(x) 'show the Answers' -> Import from business logic.
- f(x) 'check the Answer' -> Import from data.
    - "If the answer is correct it the bgcolor will change to green and if it's not it will change to red"

### LISTENER

- f(x) 'check the Answer' -> Import from business logic.
  
## C) RESULT's BAR

### HTML

- DIV
    - Container for results bar.

### CSS

- DIV (RESULTS BAR)
    - width
    - position: bottom left side of the webpage.

### BUSINESS LOGIC

- f(x) 'find the storedAnswer' -> Import from data access -> Import from data.
  
### COMPONENT

- f(X) 'Update status' --> Import Business Logic.
    - Display the currently status:
        - If the there is no result stored in data then the circle will be grey.
        - If the result/answer is correct it will display a green circle.
        - If it is not correct then it will display a red circle.

## D) NEXT QUESTION

## HTML

- DIV
    - Button.
        - Next question button.

## CSS  

- DIV (NEXT QUESTION BUTTON)
    - width
    - position: bottom right side of the webpage.
- Button
    - margin.
    - padding.
    - hover.
    - bgcolor.

### BUSINESS LOGIC

- f(x) 'clear the DOM'
    - remove the previous question.
    - remove the previous answers.
- f(x) 'show the next question'.
- f(x) 'show the next answer'.
- f(x) 'update result's bar'.

### HANDLER

- f(x) 'calling show the next question'.
- f(x) 'calling show answers'.
- f(x) 'showing result's status'.

### LISTENER

- ONCLICK --> Button.

# SCORE's PAGE - SCORE.HTML

New HTML file.-

## Your Score

### HTML

- DIV
    - H1
        - Final Score.

### CSS

- DIV
    - h1
        - alignment: centered.
        - width
        - padding
        - size

### BUSINESS LOGIC

-f(x) 'call show final score'.

### HANDLER

-f(x) 'show final score'.

### DATA ACCESS

-f(x) 'access to the final score storage in data layer'.

## TABLE

### HTML

- DIV
    - Table
        - 3 columns

### CSS

- DIV
    - table
        - alignment: centered.
        - first row: font alignment: centered.
        - 2nd-6th row: font alignment: left.

## BUSINESS LOGIC

- f(x) call 'showing the question'.
- f(x) call 'showing user's answer'.
- f(x) call 'showing the correct answer'.

## DATA ACCESS

- f(x) 'read question'.
- f(x) 'read user's answer'.
- f(x) 'read correct answer'.

## HANDLER f(x)

- f(x) 'showing the question'.
- f(x) 'showing user's answer'.
- f(x) 'showing the correct answer'.
