# Friend-Finder_Express-Node-Javascript


![screen shot 2019-01-20 at 9 27 01 pm](https://user-images.githubusercontent.com/41619692/51454574-3f3ee900-1cfa-11e9-984f-a3fa993fe36e.png)

![](ezgif.com-crop.gif)

![Uploading ezgif.com-crop.gif…]()


This project is a friend finder app that takes in the name, photo link,
and selection data of the user.

If any of the forms or selections are left unfilled, an alert message will be displayed
informing the user to complete all forms and selections.

Upon hitting the submit button with all the forms and selectors filled out,
the corresponding data will be submitted to the api/friends route. In addition,
the current data of the friends.js JSON will be stored within a variable and parsed through
to tell the closest match to the current user input.

The friends.js JSON data will be joined with the score differences (compared to current user scores),
sorted from lowest score to highest score, and the first object literal within the JSON array will be
defined on a variable that is an object literal and that variable data will be displayed on a modal pop-up.

Upon hitting close on the modal pop-up, the app resets for the next user form.



My deployed project can be seen on Heroku at the link below:
https://friend-finder-zuckermann.herokuapp.com/
