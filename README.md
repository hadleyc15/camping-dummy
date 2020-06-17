**Your project should fulfill the following requirements:
<br>
**Use a CSS framework other than Bootstrap.
<br>
**Be deployed to GitHub Pages.
<br>
**Be interactive (i.e., accept and respond to user input).
<br>
**Use at least two server-side APIs.
<br>
**Does not use alerts, confirms, or prompts (use modals).
<br>
**Use client-side storage to store persistent data.
<br>
**Be responsive.
<br>
**Have a polished UI.
<br>
**Have a clean repository that meets quality coding standards (file structure, naming conventions, follows best practices for class/id naming conventions, indentation, quality comments, etc.).
<br>
**Have a quality README (with unique name, description, technologies used, screenshot, and link to deployed application).
<br>
**Finally, you must add your project to the portfolio that you created in Module 2.
<br>
USER STORY:
As a user, I want an application to be able to search for existing campgrounds.  I want to be able to search and state in the United States as well as any province in Canada (just in case I want to camp anywhere in canada...).  Given my input, I am shown existing campgrounds.  I also want to be able to see current weather in the area of each campground to better influence my decision on a campground.  
<br>
MOTIVATION FOR DEVELOPMENT:
Big into camping and tired of having to google search campgrounds and getting results that don't pertain to my search.  Also wanted all results to show weather which doesn't always happen when searching through other search engines.
<br>
PROCESS:
<br>
For our project we decided to create an application for a user to be able to search for campgrounds based off of State or Canadian Province input.
We also wanted to be able to display current weather data for each individual campground so that the user has more information that could help them in their decision on where they would like to go.
<br>
We started the project by creating a simple HTML and CSS framework with a background image that related to the project.  We then added drop down menus for user input to select the State or Province.  The api would only accept abbreviations for input so we decided dropdown menus were the easiest way to force the input to be what it needed to be.  This way we would avoid any unacceptable input from the user.
<br>
<img src="/assets/images/Screenshot%20(47).png" />
<img src="/assets/images/Screenshot%20(48).png" />
<img src="/assets/images/Screenshot%20(49).png" />
<br>
We programmed the JS to fire upon a change in the dropdown so that the user does not have to hit a search button after making their selection.  
<br>
<img src="/assets/images/Screenshot%20(50).png" />
<br>
Upon selection of a state or province, cards are generated that show the results of campgrounds in the selected area.  The name of the campground is displayed as well as an image of the campground (if available throught the api).  Current weather is then displayed through another api call.  
<br>
<img src="/assets/images/Screenshot%20(37).png" />
<br>
Local storage is then used to store the last search so if the screen is refreshed the last search is not lost.
<br>
<img src="/assets/images/Screenshot%20(37).png" />
 <br> 
**The two api's that were used for this project can be found at:
<br>
  https://developer.active.com/docs/read/Campground_APIs
<br>
  https://openweathermap.org/guide
<br>
Link to deployed application:
<br>

<br>
Link to Github Repository:
<br>
https://github.com/sgtratchet/campground-finder
