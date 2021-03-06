# "Your Pantry" Full-stack Application by Roc Taylor and Cara Phillips

SEI Project 3, March 2022


APP URL: https://yourpantryrecipes.herokuapp.com/
backend data: https://yourpantry.herokuapp.com/yourpantry

GitHub frontend:https://github.com/carablythe/Project3frontend
backend: https://github.com/carablythe/Project3backend

OVERALL APPROACH TAKEN:
An app for people to browse recipes by main ingredients, add their own recipes to the collection (edit, delete, etc.)

TECHNOLOGIES USED:
React, Express, Mongoose, Javascript... There is no seed file because the data is partially generated by us to start with and then mainly user-generated.

SUCCESSES:
The app is really straight-forward, so achieving MVP was easy and an early success.  However, we wanted some added features such as having the edit form allow for partial edits of the recipes and be inside the recipe card, for users to add links to recipes and/or directions, and for the cards to be hidden and reveal upon onClick one at a time. So it took a little longer to achieve these, but we did. Getting the add recipe form to clear upon submission and the edit form to already have the current data in the entry fields to be adjusted accordingly were also challenging, but we managed it!

CHALLENGES:
Getting deployed on Heroku was a lot more complicated this time with both frontend and backend and two apps for each, two GitHub repositories, etc.  The first two days involved getting it all set-up, and we ended up not following the markdowns exactly in order to get everything to work.  After that we could focus more on the app functionality, content and design.

UNSOLVED PROBLEMS:
1. User authentication (registered, log in, log out, profile page, and permission to edit and delete ONLY the recipes they've made)
2. sorting list of recipes alphabetically
3. multi-word search capability

STRETCH/FUTURE GOALS:
1. Above Unsolved Problems + the below:
2. Getting an external API set up for queries
2. Adding likes and comment features
3. CONTENT-WISE: Getting all of my (Cara's) recipes and photos up to share with people when they ask how I made this or that, in both English and Japanese
-----



// failed attempts below at alphabetical Order sorting:

  // const alphabeticalOrder = () => {
  //   axios
  //     .get('https://yourpantry.herokuapp.com/yourpantry')
  //     .then((response) => {
  //       setRecipes(response.data.dish.sort(function(a,b)
  //       {return a.localeCompare(b)}
  //     ))
  //   }
  //  )
  // }
  //
  // useEffect(() => {
  //   allphabeticalOrder()
  // // }, [])
  //
  // const alphabeticalOrder = () => {
  //   axios
  //     .get('https://yourpantry.herokuapp.com/yourpantry').then(response).sort(a,b) =>
  //   return a.response.dish.localeCompare(b.response.dish)
  // }
