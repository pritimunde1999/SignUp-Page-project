# SignUp-Page-project
Deploy link: https://pritimunde1999.github.io/SignUp-Page-project/

1.Handled authentication using local storage.

2.Created a UI, make 2 pages - signup and profile

3.On clicking signup, used local storage to create the state of the user.

4.The state of the user saved in localstorage should contain all the properties of the user, plus should also consist of an access token - let this access token be a random 16-byte string generated randomly.

5.Once there is the state of user in the localstorage, redirect the user to a page called /profile. Displayed user’s details there.

6.On clicking of the logout button, set all the states back to null and also get rid of the access token.

7.Using scripts ensured that when a user manually tries to go to /profile, if the local storage does not contain the accesstoken the user is redirected to the signup page.

8.Similarly if the localstorage has an accesstoken and tries to go to the signup page, using scripts ensures that the user can't do so and is redirected to the profile page.

9.Showed success and errors. All fields are mandatory for signup and similarly on successfully signing up show the message in green text and then redirect to /profile.
