# smart-brain App
Full stack JavaScript App, done with React.js, Node.js, PostgreSQL, using Clarify API and deployed on Heroku.

Test the app here:
https://smart-brain-app-rc.herokuapp.com/

Features:

- User register or sign in.

- Face recognition: Once the profile is displayed, the user can enter the url of an image. If the image contains human faces, the user entries are incremented by the number of the recognized faces. In case the url is not valid, an error message is displayed. Face detection is done using Clarifai API.
