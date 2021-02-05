
# CineMatch
CineMatch will facilitate users' decisions on which movie to watch, by providing them with movie recommendations. Users are able to search for movies on an online database. They can register for an account, allowing them to add movies to their "Favorites" and "Want a Watch" lists, as well as post and view reviews for movies.
Check out [CineMatch](http://cinematch.s3-website-us-east-1.amazonaws.com/) online! Use FireFox for the best experience.


## TO USE:
- Clone both repos
- Import BackEnd into Spring Boot
- Run on Server
- Enter directory that holds front end
- Run 'npm install' in command line
- Run ' ng serve -o' to run Angular front end
[Front End](https://github.com/2012JavaReston/MovieApp-FrontEnd)
[Back End](https://github.com/2012JavaReston/MovieApp-BackEnd)


## Project Description
CineMatch is a movie database where users can explore new movies, search movies, and get detailed information about movies. Users will be able to login/register, add movies to a “Favorites” and a “Want to Watch” list, and also be able to search for movies and post/view reviews.


## Technologies Used
* Angular - 11.0.6
* Typescript - 4.1.3
* Material - 11.1.0
* Bootstrap - 4.6.0
* HTML5
* CSS3
* Font Awesome
* TMDB API

## Features
User can: 
* login / logout
* Create an account
* Comment on a movie and delete their comment
* Like a movie and view their liked movies
* Add a movie to watch list and view their list
* View list of random movies, tending movies, and movies to explore
* Search a movie by name

## To-do
* Friend List
* Random Movie Filters (Language, rating, genre)
* Profile Pictures
* UI polish
* Trailer playback
* Interface with third party streaming APIs

## Getting Started
   
1. Have your environment [set-up](https://angular.io/guide/setup-local) for Angular development
2. Run `git clone https://github.com/2012JavaReston/MovieApp-FrontEnd.git`
3. Run `npm install`
4. Run `ng serve --open`

To connect to a local database:
1. Navigate to [MovieApp-BackEnd](https://github.com/2012JavaReston/MovieApp-BackEnd) and follow their set 'Getting Started' guide
2. In the MovieApp-FrontEnd, navigate to src/app/services/api.service.ts and change the baseUrl variable to your own local instance of the BackEnd server.
    * Example: private baseUrl = 'http://localhost:8080/MovieApp/api/'

## Usage

Landing: `http://localhost:4200/`

<img style='max-width: 650px' src='https://imgur.com/yJ649VL.png' />

Login: `http://localhost:4200/login`

<img style='max-width: 650px' src='https://imgur.com/48XJZeP.png' />

Register: `http://localhost:4200/register` 

<img style='max-width: 650px' src='https://imgur.com/TswRz4E.png' />

Home: `http://localhost:4200/home`

<img style='max-width: 650px' src='https://imgur.com/OH3ZZ8I.png' />

Search: `http://localhost:4200/search/:movie`

<img style='max-width: 650px' src='https://imgur.com/rIGtYa8.png' />

Liked: `http://localhost:4200/liked`

<img style='max-width: 650px' src='https://imgur.com/7QyAQrR.png' />

Movie Info: `http://localhost:4200/movieInfo/:id`

<img style='max-width: 650px' src='https://imgur.com/OCjg0wa.png' />

Profile: `http://localhost:4200/profile/:username`

<img style='max-width: 650px' src='https://imgur.com/8ccyfuz.png' />

Watch List: `http://localhost:4200/watch`

<img style='max-width: 650px' src='https://imgur.com/oZ5DORL.png' />

## Contributors

Lester Young, Andrew Gee, Jeff Enriquez, Alec Sherlock, Ryan Murray

