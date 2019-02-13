# PetMii
![Screenshot of app](https://github.com/THE-group-project/project2/blob/master/public/images/preview.png)

How to get started?

   * Since the project is deployed on heroku you can visit it by 
    [CLICKING HERE](https://petmii.herokuapp.com/)
    
    Deployed link last updated 02/8/2019 @9:31pm
   
   * Bugs/Issues: Favorite link, Search after authentication
   * Nice to have in update: 404 Page remove "restricted" plain page
    
# How this project came to be…
  * Eric suggested that we create a shelter or safe house informational site for young adults similarly to a mobile app found on the app     store that was very basic and we felt that we could add further improvements to it. However one thing we wanted to utilize in our         website was an API and we felt that there were no API available to use for shelters/safe houses. We were going to utilize Google         map’s API for search query of shelters/safe house nearby but we felt it would be too similar to our previous project so we      scrapped that idea. We got our project idea from the search results bringing back "animal shelters" and so here we are.
  
# What is the purpose of this project?
   * The purpose of this project is allow users to search for pets to adopt nearby.
   * Goal is to develop a functioning site for the community.
   
# What are the benefits of pet adoption?

  * Adopting a pet comes with numerous advantages including:

  * You’re saving a life. Millions of healthy, adoptable pets are euthanized every year simply for a lack of a home. When you adopt your        pet from a shelter or rescue group, you’re giving a deserving pet a loving home.
  * Many adoptable pets are already trained.
  * When you adopt an older pet, you will often get a sense of their personality and temperament. You also already know their full grown       size!
  * An adoption fee can save you money! Adoption fees often include vaccinations, spay/neutering, microchips and other veterinary costs         to help prepare the pet for a new home.
 
  # Project usage:
   * New technology: Bcrypt (password hashing function)
   * API Usage: Petfinder 
   * GET: Logout, rendering homepage and search pages, favorite information
     Ex: User logs out close session, handlebar rendering of home, contact, signup, login, search, favorites
   * POST: Signup, login, Search, Favorites
     Ex: Post route for signing up new users, log in in existing users, searching" the api, adding favorites
   * MySQL Database with a Sequelize
      User models: ID with primary key, name, username, password, email, zip, animal, age, gender
      Favorite models: animalID, UserId
