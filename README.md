<link rel="stylesheet" type="text/css" media="all" href="css/styles.css" />

# Joseph Ross
Welcome to my e-Portfolio.  I recently graduated from Southern New Hampshire University with a Bachelor's degree in Computer Science.  This page has descriptions and links to a number of projects that I have completed for school or as personal projects over the last couple years.  I am currently working as a web developer and have a few years of experience in the field both educationally and professionally.  I have worked on full stack projects using a number of different platforms and tools. I have included a list of my useful skills at the bottom of the portfolio.  If you would like more information about my skills and experience check out my [LinkedIn profile](https://www.linkedin.com/in/joeross999/).  I am currently looking for work as a full stack web developer but intend to go back to school to pursue graduate education in the near future.

### Table of Contents

[Southern New Hampshire University Projects](#southern-new-hampshire-university-projects)

[Personal Projects](#personal-projects)

[Udacity Projects](#udacity-projects)

[School Projects from UMass Amherst Honors College](#umass-amherst-projects)

[Skills](#skills)

## Southern New Hampshire University Projects

### Distributed Artificial Intelligence Simulation
This is a project that I completed for my Capstone Project for my Computer Science Degree from The University Of Southern New Hampshire.  The project is a web based simulation of distributed artificial intelligence for self assembling robots.  All of the robots (the colored dots on the screen) have no knowledge of any other bots in the world but they can communicate through a simulated wireless communication system with a set range.  The bots than think on their own, using target acquisition and pathfinding algorithms to assemble themself into specified patterns. Every step, the browser sends a request to the Node.js server to complete the computational work.  The server then uses user's session information and a database to retrieve the correct bots for the current user and performs the computational work.  Once the computation is complete the results are sent to the browser where they are rendered for the user to see.  Check out the project repo [here](https://github.com/joeross999/Distributed-Intelligence-Experiment)

![Distributed Artificial intelligence Simulation][die-simulation]

As this is currently an ongoing project I have included a roadmap for features that I would like to add to the project.

- Roming pattern (We are currently removing bugs from this feature and will be adding it to the main code base soon)
- More patterns (There are currently 2 patterns, we hope to add more as time goes on)
- Get it up on my website. ([thelifeofcode.com](#the-life-of-code))
- More customization options (Ability for user to change patterns, coloring, and other options)
- Better target acquisition system (Currently bots do not cooridinate their target acquisition work with the other bots, this means that sometimes multiple bots choose the same target resulting in some wasted time when bots move towards a target that will be filled before they reach it.)
- Collaborative pathfinding (Currently the bots do not coordinate their movements and often cross paths causing one of the bots to recalculate its path)

``` 
Note: This project is currently on hold as I look into reworking the project in a faster language.  I am currently learning Rust and discussing rebuilding the project using Rust rather than JavaScript.
```
Usually as part of the capstone project, students are required to improve three school projects to demonstrate enhancements in three categories: Software Design and Engineering, Algorithm and Data Structures, and Databases.  Rather than simply improve school projects, I decided, after receiving approval from my instructor, to create one project, from scratch that would demonstrate my knowledge in all three categories.  The result was the Distributed Artificial Intelligence Simulation.  The requirements are fulfilled as follows.  The simulation, including the web server, the browser rendering system, and the world setup fulfills the Software Design and Engineering requirements.  The AI used for the bots to organize into the patterns fulfills the Algorithm and Data Structures requirements. Then Finally the project has been connected to a database to allow for multiple simultaneous users, fulfilling the database requirements.

I also Completed a Code Review for one of the early steps in the process.  [View the code review](https://www.youtube.com/playlist?list=PL0Dhu-pZ6JPHKndhZWyd7ojdCWxedM57L)


## Personal Projects

### Snake 
![Snake][Snake]
For this project I attempted to recreate the classic game "Snake" using vanilla javascript.  It was a fun project to test out some of my coding skills using the Model-View-Controller Pattern.  [Check out the code here](https://github.com/joeross999/Snake)

### The Life Of Code
This is my personal website that is currently in development.  I had to put the project on hold during the last few months due to an increase in school work load, and other personal reasons. I hope to continue to improve the site and start to upload content soon.  [Take a look at what I have so far...](http://thelifeofcode.com)

### A collection of my earlier projects
This website has a number of my early projects.  Feel free to explore.
[spiker.neocities.org](https://spiker.neocities.org/)

## Udacity Projects
I have completed the Udacity Front-End Developer Nanodegree so these are just a few of the projects that I developed during that program.

### Frogger Web Game
![Frogger Web Game][frogger-sim]
This is a simple frogger clone rendered in the browser using the HTML 5 canvas.  This project was entirely developed as part of the Nanodegree program.

### New Zealand National Parks Weather Project
![New Zealand National Parks Weather Projec][New-Zealand-Weather-Project]
I developed this project on my own for an assignment during the nanodegree.  This project uses the Google Maps API for the map data and APIXU for retrieving weather data for National Parks in New Zealand.  I used the Knockout.ks framework to implement a Model-View-View-model pattern.  The project renders on both desktop and mobile (although this was one of my first mobile responsive sites so the mobile experience isn't perfect). The code is located [here](https://github.com/joeross999/New-Zealand-National-Parks-Weather-Project). [Checkout the project here!](https://spiker.neocities.org/NewZealandWeatherProject/index.html)


### Udacity Feed Reader Jasmine Testing Exercise
This was a simple project to learn how to use Jasmine.  I am now using Jasmine as the testing framework for [Distributed Artificial intelligence Simulation](#distributed-artificial-intelligence-simulation).  [View the repo](https://github.com/joeross999/frontend-nanodegree-feedreader)

### RoboND Rover Project
This was a project that I completed as part of a Udacity robotics class.  It uses python to control a robot to navigate an unknown terrain using a virtual camera as an input device.  [View the Code](https://github.com/joeross999/RoboND-Rover-Project)

## UMass Amherst Projects
Both of these projects were developed during my freshman year at UMass Amherst.

### Binary Search Tree
[See the code here](https://github.com/joeross999/Binary-Search-Tree)

### Sorting Algorithms
[See the code here](https://github.com/joeross999/Sorting-Algorithms)

## Skills
Here are a list of skills that I have and tools that I have experience with.  This is not an exhaustive list of every experience that I may have had but it does give a good idea as to my experience.

General Skills
- Full Stack Web Development
- Responsive Design
- Object Oriented Programming
- Browser Developer Tools (Chrome)
- Development Team Experience (Agile)

Languages
- JavaScript (Advanced)
- CSS (Experienced)
- HTML (Experienced)
- Python (Experienced)
- Linux Command Line and Scripts (Experienced)
- Java (Educational Experience)
- C++ (Beginner)

Development Tools and Libraries
- Git (Advanced)
- Node.js (Advanced)
- AJAX (Experienced)
- Bootstrap (Experienced)
- Ember.js (Experienced)
- Gulp.js (Experienced)
- jQuery (Experienced)
- MongoDB (Experienced)
- Photoshop / GIMP (Experienced)
- Wordpress (Experienced)
- SQL (Beginner)
- React (Beginner)

[die-simulation]: https://raw.githubusercontent.com/joeross999/joeross999.github.io/master/images/DIE-Simulation.PNG
[frogger-sim]:https://raw.githubusercontent.com/joeross999/joeross999.github.io/master/images/frogger.png
[New-Zealand-Weather-Project]:https://raw.githubusercontent.com/joeross999/joeross999.github.io/master/images/New-Zealand-Weather-Project.png
[Snake]:https://raw.githubusercontent.com/joeross999/joeross999.github.io/master/images/Snake.png