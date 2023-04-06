


# 🏆  **Goals:** 
- ⭐️ create an original personality quiz

<br>

# Creating Your Personality Quiz
Let's create an original personality quiz. This project can also be used to add to your final portfolio site. Thinks of an original concept and line out some questions.

You're required to have the following:

- A Title
- Short Description of Personlaity quiz
- At least 6 questions
- Final Results Displayed
- A "Take Again" / repeat button

<br>

<br>

# 🗂 Step 1: Set Up Your Project
Create a new folder in the lesson 6 folder name it the title of your portfolio. Inside the folder, create two new files: index.html, styles.css, scripts.js

#  🧱 Step 2: HTML Structure
In your index.html file, paste the following code:

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Personality Quiz</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <!-- import the webpage's stylesheet -->
    <link rel="stylesheet" href="/style.css">
    
    
    <!-- import the webpage's javascript file -->
    <script src="/script.js" defer></script>
  </head>  
  <body>
  <h1>Title</h1>
  
    <h2>Question 1:</h2>
    <div class="question">
      <div class="answer-choice">
        <button id="q1a1">answer1</button>
      </div>
      <div class="answer-choice">
        <button id="q1a2">answer 2</button>
      </div>
      <div class="answer-choice">
        <button id="q1a3">answer 3</button>
      </div>
      <div class="answer-choice">
        <button id="q1a4">answer 4</button>
      </div>
    </div> 
    
    
    <div class="result">
      <h3 id="result"></h3>
    </div>
    
    <div class="restart">
      <button id="restart">Take It Again</button>
    </div>

  </body>
</html>


```



# 🎨 Step 3: Styling Your Website

Now that we have our HTML structure set up, we can add some styling to our website. Open your style.css file and add the following code:


``` css

/* CSS files add styling rules to your content */

body {
  background: gray;
  margin: 2em;
  font-family: sans-serif;
}

h1 { 

}

h2 { 

}
 
/* answers */
h3 { 

}



/* makes sure images are all the same size */
img {

}


.question {

}

.answer-choice { 

}


/* Button Styles */
button{}

.restart {

}


```

# ⚙️ Step 3: Adding Functionaility

Now that we have our HTML and CSS set up, we can add some functionaility to our website. Open your scripts.js file and add the following code:


``` javascript

// Create four variables to track each possible quiz outcome
var questionCount = 0;

var result_1_score = 0;
var result_2_score = 0;
var result_3_score = 0;
var result_4_score = 0;

//grab result via DOM
var result = document.getElementById("result");
var resultpic = document.getElementById("resultpic");

//create variables
//question 1
var q1a1 = document.getElementById("q1a1");
var q1a2 = document.getElementById("q1a2");
var q1a3 = document.getElementById("q1a3");
var q1a4 = document.getElementById("q1a4");


```

You'll find exmaples from your mentors in the folder with their names (also located in the lesson 3 folder)
- to access them open up the folder with the person's name
- naviagate to the HTML file within the folder
- click the go live button

⭐️ Hint: You'll find some intersting functionality and features in these you may want to try and add to your own site