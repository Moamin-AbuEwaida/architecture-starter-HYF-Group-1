<!--

  There will be different types of tasks for each user story:
    `type: components`
    `type: css`
    `type: logic`
    `type: handlers`
    ...

-->
# 0.- Welcome page
  When the user open the website will see.
  ##  A) HEADER 
  ### HTML
  - H1
  ### CSS
  - H1
       - Centered.
       - Font alignment: centered.

## B) MAIN SECTION
  ### HTML
  -  CONTAINER (.instructionContainer)
  -   <P>
    - Instructions of the QUIZ's.
  ### CSS
- .questionContainer
     - BGcolor
     - Width
     - Padding
     - Boxshadow
     - Border radious
    - P
      - textalign: centered.

## C) BOTTOM SECTION.
  ### HTML
   - button
     - Hiperlink 
     
  ### CSS
   - BUTTON
     - Center aligned.
     - BGcolor: grey.
     - Border.
    - Hoover: transition fade out.


# 1.- QUESTION'S page
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
  - f(x) 'show the question' -> Import from bussiness logic.
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
  
  ### HANDLER
  - f(x) 'show the Answers' -> Import from business logic.
  - f(x) 'check the Answer' -> Import from data.
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
  - f(x) 'find the storagedAnswer' -> Import from data access -> Import from data.
  
  ### HANDLER
  - f(x) 'show the results' -> Import from business logic.

## D) NEXT QUESTION
## HTML
  - DIV
    - Next question button.

## CSS  
  - DIV (NEXT QUESTION BUTTON)
    - width
    - positon: bottom right side of the webpage.

### BUSINESS LOGIC
- f(x) 'clear the DOM'
- f(x) 'calling Show Question'
- f(x) 'calling show answers'
- f(x) 'calling 
### HANDLER
-
### LISTENER f(x)
-
# SCORE's PAGE

## HTML
  - H1 
    - Final Score.
  - Table
    - 3 columns
## CSS
  - h1
    - alignment: centered.

  - table
    - alignment: centered.
    - firs row: font alignment: centered.
    - 2nd-6th row: font alignment: left.
## DATA ACCESS

## HANDLER f(x)


## LISTENER f(x)