Congratulations!  You are officially being nominated for The Internets first annual dBag Moderator contest! Sir Moddy McModerator, The Internet's chairman of the board has requested that you can prove that you know how to not only moderate, but to moderate in the most biased and unfair way imaginable. In order to do this, he has requested that you build a simple react app that has a few functions, aimed at silencing the worst of opinions on the interwebs.  Here are his demands:

REQUIREMENTS:
  1. Create a react app without the use of local state, and instead, replace it with redux.
  2. Using the data provided, create a list view that can display data in an efficient manner.  
  3. From there, create an action that will:
    3A. Allow you to delete a comment from the list.
    3b. Maintain a record of how many comments you have deleted so far
    3c. BONUS: If you have time, allow a reason to be added as to why you are deleting the comment.
  4. In a seperate view, create a simple vertical bar-chart that shows:
    4a. How many comments you have deleted and are no longer active
    4b. How many comments are still active
    4c. How many comments Sir Moddy McModerator hates
    4d: BONUS: Under said bar chart, create a list of the reasons the comments were deleted, that reference the comment's original id.

KEEP IN MIND:
  1. Make sure there is a way to navigate between the two views.
  2. This app should function properly in at least the latest Firefox, Chrome and Edge Browsers (even though Sir Moddy McModerator hates Edge)
  3. when possible, please push your work up to git, as to establish a historical record of the work that you are completing. For the sake of this challenge, if its been an hour without pushing to git, might as well make another push.
  4. Please do not directly alter the comments.json file.  This should act as your 'database', and the data should be pulled into the app/redux in order to be manipulated.
  5. If you have any questions please reach out and ask. Prior to and during the challenge.  
  6. Sir Moddy McModerator would appreciate you using more plain JS than libraries for this task outside of the normal libraries needed to complete this task (react/redux/thunk/router etc.
