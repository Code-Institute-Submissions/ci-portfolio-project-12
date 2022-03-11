# **Milestone Project 2 - Simon Game**
## Javascript Game - <a href="https://chrotesque.github.io/ci-portfolio-project-2/" target="_blank">View deployed site here.</a>

![AmIResponsive](assets/images/readme/amiresponsive.jpg) 

<br>

# Table of Contents

1. [Overview](#overview-)
2. [UX](#ux-)
3. [Features](#features-)
4. [Technologies Used](#technologies-used-)
5. [Validation and Testing](#validation-and-testing-)
6. [Bugs](#bugs-)
7. [Deployment](#deployment-)
8. [Credits](#credits-)
9. [Statistics](#statistics-)
10. [Acknowledgements](#acknowledgements-)

<br>

# **Overview** ([^](#table-of-contents))

Simon Game is a simple game about memorizing and replicating a sequence of button presses by the computer. The project consists of a single page with all necessary elements already in place, dynamic information is then being placed by Javascript which also runs the games logic.  

# **UX** ([^](#table-of-contents))

* ## **Strategy**

    This project was made specifically for the Full Stack Development course by Code Institute as 2nd milestone project. 
    This particular game was chosen as basis for the work as it seemed the most complex of the ideas I prepared for the first Mentor meeting, my Mentor also remarked that he hadn't seen this particular game done previously by others. 

    ### **User Stories**
    As a first time user ...
    1. I want to be able to understand what the game is about and how it is played.
    2. I don't want to spend much time on setting the game up but rather jump right into it.

    <br>

    As a returning user ...
    1. I want to be able to change up my experience through different difficulty settings. 
    2. I also want to be able to further increase the difficulty later down the line or change the game to my specific needs. 

    <br>

* ## **Scope**

    The project offers:
    - the base game experience that most people are experienced with
    - a help menu to explain all necessary details of the game including the modifications / options I provided
    - a settings menu to customize the experience
    - an arbitrary score amount chosen me attached to various successful actions within the game and displayed to the user
    - a very compact design

    <br>

* ## **Structure**

    The structure of the project is relatively simple and divided into:
    - a game area where user interactions occur
    - menus in which text is either simply being displayed or more user interaction is possible
    - a small social link collection of the developer

    <br>

* ## **Skeleton**

    The project offers 3 paths to take portrayed by 3 distinct and commonly understood buttons:
    - a start icon to start the game, changing to a stop icon to stop the game manually
    - a gear icon to open the settings menu
    - a question mark icon to open the help menu

        ![All game icons in a row](assets/images/readme/game_icons.png)
    
    The game offers clear and unambigious information about the state of the game in the middle of the screen as to what's going on or what just happened, ie: "Game Over", "Game Stopped", "Your Turn", etc. 

    ### **Wireframes**
    <details>
    <summary>Mobile Only Wireframes: Difficulty Selection, Mid Game / Game Over & Help Screen</summary>

    ![Balsamiq - Difficulty Selection](assets/images/readme/wireframe_difficulty.jpg)
    ![Balsamiq - Mid Gameover Help](assets/images/readme/wireframe_midgameoverhelp.jpg)
    </details>

    - Note: I believed the game was called Simon Says. I later learned it's generally known as Simon Game instead.

    <details>
    <summary>Hand-made Sketches from MS OneNote: Settings Menu & Middle Display</summary>

    ![OneNote - Settings Menu](assets/images/readme/sketch_settings.jpg)
    ![OneNote - Middle Display](assets/images/readme/sketch_middle.jpg)
    </details>

    - Due to size contraints I later opted out of the middle display of ingame information such as the exact speed percentage currently in effect, etc.
    
    <br>

* ## **Surface**

    I employed a desktop first approach which later turned out to be a mistake, one I found rather hard to remedy. As such the game went through a variety of styles. While I developed a portion of the Javascript without a real GUI, I later invested a great deal of time towards a main feature of the game, offering multiple button configurations (3, 4, 5 or 6).

    The iteration I stuck with uses SVGs for unlimited scaling in theory to also avoid artifacts when using .jpg/.png image files or similar formats and additionally to improve performance on mobile, to avoid the download of big files which would undoubtably be required to make the game look good at bigger resolutions.
    
    The game in it's latest iteration is rather compact and all required elements are gathered around the center of the screen. The name and the score (not visible at first) are part of the surrounding frame: 

    ![Game Design](assets/images/readme/active_script.jpg)

    This is the game during gameplay, now with score visible:

    ![Game Design](assets/images/readme/active_running.jpg)

    This is what remains with Javascript turned off:

    ![Game without Javascript](assets/images/readme/no_script.jpg)

    The menus were initially designed to be speech bubbles (as a direct hint towards the name of the game "Simon Says", that idea was then dropped when I realized the actual name of the game) and ended up in more of a pop up design with an easy to understand close icon in the top right:

    ![Game Menus](assets/images/readme/menus.png)

    ## Color scheme & Font choice

    I based this project on a recommendation listed in <a href="https://www.pagecloud.com/blog/best-google-fonts-pairings" target="_blank">this article</a> but made modifications along the way. 
    Nunito is the only font used in the entire project.

    ## Graphics

    Instead of rasterized images I created vector graphics and use them as svgs within the html which were created using [Adobe Photoshop](#technologies-used-).


# **Features** ([^](#table-of-contents))

TBD

# Technologies Used ([^](#table-of-contents))
- Main languages: <a href="https://en.wikipedia.org/wiki/HTML5" target="_blank">HTML5</a>, <a href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets" target="_blank">CSS3</a> & <a href="https://en.wikipedia.org/wiki/JavaScript" target="_blank">Javascript</a>
- <a href="https://fonts.google.com/" target="_blank">Google Fonts</a> used for fonts throughout the whole site
- <a href="https://fontawesome.com/" target="_blank">Font Awesome</a> used for a few select icons to be able to style them as font/text
- <a href="https://git-scm.com/" target="_blank">Git</a> used for version control through the Gitpod terminal for deployment onto Github
- <a href="https://github.com/" target="_blank">GitHub</a> used as host and for deployment of the site
- <a href="http://gitpod.com" target="_blank">Gitpod</a> used as IDE
- <a href="https://validator.w3.org/" target="_blank">W3C Markup Validation Service</a> used to validate HTML code
- <a href="https://jigsaw.w3.org/css-validator/" target="_blank">W3c CSS Validation Service</a> used to validate CSS code
- <a href="https://jshint.com/" target="_blank">JSHint</a> used to analyze and error correct the Javascript code
- <a href="https://color.a11y.com/" target="_blank">a11y Color Contrast Accessibility Validator</a> used to validate contrast accessibility
- <a href="http://clickup.com" target="_blank">ClickUp</a> used for project management
- <a href="https://wakatime.com" target="_blank">WakaTime</a> used as time tracking tool
- <a href="https://www.adobe.com/products/photoshop.html" target="_blank">Adobe Photoshop 2021</a> used for the creation of vector graphics
- <a href="https://tinypng.com/" target="_blank">TinyPNG</a> used to optimize JPG and PNG file sizes for this readme
- <a href="https://lettercounter.github.io/" target="_blank">Lettercounter</a> used to keep commit messages below or at 50 characters
- <a href="http://ami.responsivedesign.is/" target="_blank">Am I Responsive?</a> used to create responsive preview of the site used at the top of this readme
- <a href="https://coolors.co/" target="_blank">Coolors</a> used to create a color palette for this project
- <a href="https://balsamiq.com/" target="_blank">Balsamiq</a> used to create the wireframes during the initial design stage

<br>

# **Validation and Testing** ([^](#table-of-contents))

TBD

# **Bugs** ([^](#table-of-contents))

TBD

# Deployment ([^](#table-of-contents))
This project was developed using Gitpod through which it was committed and pushed to the repository on Github as host:
1. Visit <a href="https://github.com/" target="_blank">GitHub</a> and login
2. Open the <a href="https://github.com/Chrotesque/ci-portfolio-project-1" target="_blank">respository</a>

## Github pages
Github pages were used to deploy the project as follows:
1. Open the **Settings** on the repository specific navigation marked with a gear icon
2. Navigate to the **Pages** subnavigation on the left
3. Select the master branch under **Source** and click **Save**
4. The page refreshes automatically and displays the published site URL at the top next to an exclamation mark
5. It will take a couple of minutes for the site to become available initially

## Making a Local Clone
Once the project has been accessed on Github:
1. Underneath the repository specific navigartion you'll find the button **Code** on the right side above the file listing
2. Upon click, the pop-up will offer the option to copy the repository's git-URL with HTTPS selected at the top within the pop-up
4. Open a Git Bash terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type **git clone**, and then paste the URL you copied in Step 3 and hit Enter; your local clone will now be created

<br>

# Credits ([^](#table-of-contents))
## Content & Media
- All content was written by the developer
- Vector graphics contained within the index.html were created by the developer
- The color palette was created by the developer himself, based off of <a href="https://www.pagecloud.com/blog/best-google-fonts-pairings" target="_blank">this article</a>
- The font Nunito is being provided by <a href="https://fonts.google.com/" target="_blank">Google Fonts</a>
- Icons from <a href="https://fontawesome.com/" target="_blank">Font Awesome</a>

## Code
- The sleep function used in my javascript file came from <a href="https://www.sitepoint.com/delay-sleep-pause-wait/" target="_blank">this article</a>

## Readme
- I copied various portions of my previously created <a href="https://github.com/Chrotesque/ci-portfolio-project-1/blob/main/README.md" target="_blank">my previously created README</a> for my milestone project 1
- I took inspiration from <a href="https://github.com/code-institute-solutions/samplereadme" target="_blank">the SampleReadme from Code Institute</a>.

<br>

# **Statistics** ([^](#table-of-contents))

TBD

# **Acknowledgements** ([^](#table-of-contents))

TBD