# Friend-Finder


This is an app that is hosted on a local computer and has you complete a survey to help find out which friend is most compatable with you. It takes your score and compares it to a preset score for the friends. 
 This full-stack site will take in results from your users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.
The app uses Express to handle routing and is deployed with Heroku.

In the htmlRoutes.js file this app includes two routes:

A GET Route to /survey which displays the survey page.
A default, catch-all route that leads to home.html which displays the home page.

In the apiRoutes.js file this app contain two routes:

A GET route with the url /api/friends. This is used to display a JSON of all possible friends.
A POST routes /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.
