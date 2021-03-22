# wbdv-sp21-01-movie-reviewer-app

**Team Members: Eshwari Bhide, Mubaris Khan, Osman Subasi**


1. State the problem you are trying to solve
- Include a description of at least two types of users that would use your Web application
  - For each of the types of users, provide two goals the user would like to achieve with your Web application
We want to make a movie review website where you can find information about movies and provide a textual review of the movie. Users can also rate the movies. Movie producers and audience members / reviewers would be the two different types of users. 
     - Goals for Producers:
Provide an easy way for producers to manage their movies
See how their movies are performing, in terms of viewer satisfaction, based on the reviews that will be added
     - Goals for Audience members / reviewers:
View information about their favorite movies
Add reviews to describe how much they liked / disliked the movies

2. State the overall strategy of how you intend to solve the problem
- We will use the “The Movie DB” API (https://developers.themoviedb.org/) to fetch data about movies, such as their title, origin, release data, vote average, vote count, popularity, etc. Audience members / reviewers will be able to search for movies based on the title and get this information. Then, these users will also be able to add reviews and also view the reviews of other users and will be able to add a rating for the movie. Producers will be able to also search for movies based on title and view reviews, but we don’t want them to add reviews for their own movie. Users have to first sign up for the website, and when they are verified, only then they can start reviewing. We will store this user information, along with local review and rating information in a SQL database.
 
3. One of the main requirements is to work with data available from some public, free, Web API. Provide a brief description of the Web API you intend to use.
- We will use the “The Movie DB” API (https://developers.themoviedb.org/). This data, when queried, provides numerous details about movies, such as their title, origin, release data, vote average, vote count, popularity, etc. 
