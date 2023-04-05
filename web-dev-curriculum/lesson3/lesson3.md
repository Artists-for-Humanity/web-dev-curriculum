https://codepip.com/games/

# Creating Your About Me page
Let's create a single-page website about you, this can be used on your final portfolio project or to introducee yourself to the rest of the studio

We will add the following information:

Your name
Your age
Where you go to school
Why you joined Creative Technology
What you're excited to work on
An image of yourself
A link to one of your favorite websites

# Step 1: Set Up Your Project
Create a new folder in the lesson 3 folder name it your name. Inside the folder, create two new files: index.html and style.css.

#  Step 2: HTML Structure
In your index.html file, paste the following code:

```
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
        <p class="excitement">What I'm excited to work on: What you're excited to work on</p>
        <img class="photo" src="your-image.jpg" alt="Your Name">
        <p class="favorite-website">One of my favorite websites: <a href="https://www.example.com" class="website-link">Example Website</a></p>
      </main>
    </div>
  </body>
</html>
```

In the code above, we have created the basic HTML structure for the page. The title tag sets the title of the page, which will be displayed in the browser tab. We have also linked our style.css file to the HTML file.

We then created a container div to hold the content of our page. Inside the container, we added a header and a main section.

In the header, we added an h1 tag with your name and a p tag with your age.

In the main section, we added a series of p tags with information about you, an image of yourself, and a link to one of your favorite websites.


# Step 3: Styling Your Website

Now that we have our HTML structure set up, we can add some styling to our website. Open your style.css file and add the following code:


```
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