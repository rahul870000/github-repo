GitHub Repositories Web App

Hey there! 👋 Welcome to my GitHub Repositories Web App! This little project lets you explore GitHub users and their repositories. Let's dive into how it works and how you can use it.


How to Use

Open the App: Just open the web app in your favorite browser.

Enter a GitHub Username: There's a cool input box asking for a GitHub username. Type in the username you want to explore.

Hit the Button: There's this big, friendly "Get Repositories" button. Click on it!

Watch the Magic: The app fetches info about the user and displays it. You'll see the user's avatar, name, bio, Twitter handle (if available), and location.

Repositories Galore: Below the user info, you'll find a list of repositories. Each repo shows its name, description, and the programming language used.

Navigate Repos: If the user has more than 10 repos, don't worry! There are "Older" and "Newer" buttons to explore them all.


Tech I Used

HTML: For the structure of the page.
CSS: For making things look good and stylish.
JavaScript: For all the cool stuff happening behind the scenes.
Bootstrap: I used Bootstrap to make it look fancy without much effort.


Features I'm Proud Of

Responsive Design: It looks good on your computer, tablet, or even your smartphone!
Loading Spinner: You'll see a spinning thing while the app is fetching data - just to keep you entertained.
Pagination: It's got those cool "Older" and "Newer" buttons to explore multiple pages of repositories.


The Code Behind the Scenes

The HTML file (index.html) gives the page structure.
CSS (styles.css) makes everything look awesome.
JavaScript (script.js) is where the real magic happens - fetching data from GitHub, displaying it, and making the app interactive.

API Stuff


To get user info: https://api.github.com/users/{username}
For user repositories: https://api.github.com/users/{username}/repos?per_page=10&page={page}


Wrapping Up
Feel free to play around with the code, make it yours, and learn from it. If you have any questions or ideas, reach out! Happy coding! 🚀