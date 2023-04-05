https://codepip.com/games/


# 🏆  **Goals:** 
- ⭐️ create your first personal project

<br>

# Creating Your About Me page
Let's create a single-page website about you, this can be used on your final portfolio project or to introducee yourself to the rest of the studio

We will add the following information:

- Your name
- Your age
-  Where you go to school
- Why you joined Creative Technology
- What you're excited to work on
- An image of yourself
- A link to one of your favorite websites

# Step 1: Set Up Your Project
Create a new folder in the lesson 3 folder name it your name. Inside the folder, create two new files: index.html and style.css.

#  Step 2: HTML Structure
In your index.html file, paste the following code:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Personal Website</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="container">
      <header>
        <h1 class="name">Your Name</h1>
        <p class="age">Your Age</p>
      </header>
      <main>
        <h2 class="section-title">About Me</h2>
        <p class="school">School: Where you go to school</p>
        <p class="why">Why I joined Creative Technology: Why you joined Creative Technology</p>
        <p class="excitement">What I am excited to work on: What you are excited to work on</p>
        <img class="photo" src="your-image.jpg" alt="Your Name">
        <p class="favorite-website">One of my favorite websites: <a href="https://www.example.com" class="website-link">Example Website</a></p>
      </main>
    </div>
  </body>
</html>
```

We have now created the basic HTML structure for the page. The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">title</span> tag sets the title of the page, which will be displayed in the browser tab. We have also linked our <span style="color:black; background-color:lightblue ;padding:2px; border-radius:4px; ">style.css</span> file to the HTML file.

We then created a container <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">div</span> to hold the content of our page. Inside the container, we added a <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">header</span> and a <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">main</span> section.

In the header, we added an <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">h1</span> tag with your name and a <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">p</span> tag with your age.

In the main section, we added a series of <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">p</span> tags with information about you, an <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">image</span> of yourself, and a <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">link</span> to one of your favorite websites.


# Step 3: Styling Your Website

Now that we have our HTML structure set up, we can add some styling to our website. Open your style.css file and add the following code:


``` css
/* Global styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #F5F5F5;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #FFFFFF;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

/* Header styles */
header {
  text-align: center;
  margin-bottom: 20px;
}

.name {
  font-size: 48px;
  color: #212121;
  margin-bottom: 5px;
}

.age {
  font-size: 24px;
  color: #757575;
  margin: 0;
}

/* Main styles */
main {
  text-align: center;
}

.section-title {
  font-size: 36px;
  color: #212121;
  margin-bottom: 20px;
}

.school, .why, .excitement {
  font-size: 24px;
  color: #757575;
  line-height: 1.5;
  margin-bottom: 10px;
}

.photo {
  max-width: 100%;
  height: auto;
  margin-bottom: 20px;
}

.favorite-website {
  font-size: 24px;
  color: #757575;
  margin-bottom: 10px;
}

.website-link {
  color: #1976D2;
  text-decoration: none;
  border-bottom: 2px solid #1976D2;
}

.website-link:hover {
  color: #156
}
```

You'll find exmaples from your mentors in the folder with their names (also located in the lesson 3 folder)
- to access them open up the folder with the person's name
- naviagate to the HTML file within the folder
- click the go live button

⭐️ Hint: do this before beginning your own. you'll find some helpful games / links in the mentors ID cards