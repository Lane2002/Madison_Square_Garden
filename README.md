# Madison_Square_Garden JQUERY
LEARN JQUERY
Madison Square Market
Madison Square Market wants to use jQuery to make drop-down menus appear and disappear on its home page.

The steps below outline how to write jQuery code that provides the following interactivity:

A menu appears when a user clicks on a specific menu header
The menu disappears when the user’s mouse exits the menu
If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

Tasks
5/5 Complete
Mark the tasks as complete by checking them off
1.
Look at index.html:

Note that the jQuery library has already been loaded for you at the bottom of the file.

In the header, there are three <div class="dropdown"> elements with the following ids: #cart, #account, and #help.

When a dropdown is moused over, we want its corresponding <ul class="dropdown-menu"> element to appear, then disappear when the mouse leaves the .dropdown-menu.

In main.js, start by using jQuery to add a ready method call to the document.

2.
In the .ready() callback function, add click event handlers to '#cart', '#account', and '#help'.

Add an empty callback function to each event.


Stuck? Get a hint
3.
Inside of each header’s callback function, use a jQuery method to make the corresponding drop-down menu appear.


Stuck? Get a hint
4.
Under the click event handlers, add a mouseleave event handler to each of the '.dropdown-menu's. Add an empty callback function.

Try targeting by class this time.


Stuck? Get a hint
5.
Inside of the callback function, use a jQuery method to make the drop-down menu disappear.
