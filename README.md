This repository is about a Super Hero API written with ASP.NET Core.

# How does it work

The API allows the user to create, update, delete, get all and get one super hero.

## Using the API

- <b>Creating a Hero</b>: the http method requires a JSON Object like {"name": <code>Hero name</code>, "firstName": <code>Hero real first name</code>, "lastName": <code>Hero real last name</code>};
- <b>Getting a Hero</b>: the url needs an id, passed after the base url, so it'll be something like "https://localhost:7276/api/superhero/<code>Id</code>";
- <b>Get all Heroes</b>: use the get http method with a plain body and it'll return a JSON Object like {"name": <code>Hero name</code>, "firstName": <code>Hero real first name</code>, "lastName": <code>Hero real last name</code>};
- <b>Update a Hero</b>: use the put http method with a JSON Object in the body like {"id": <code>Id</code>, "name": <code>Hero name</code>, "firstName": <code>Hero real first name</code>, "lastName": <code>Hero real last name</code>};
- <b>Deleting a Hero</b>: the url needs an id, passed after the base url, so it'll be something like "https://localhost:7276/api/superhero/<code>Id</code>";

## 💻 Requirements

**Development:**<br>
The API was written with .NET Core 6, so you will need that to run the project locally and to make changes to the code..


### Thank you for reading all of these 🏵️

> “I have not failed. I've just found 10,000 ways that won't work.”  
― Thomas A. Edison

## Note

> This project was created with study purposes, only. There is no future plans for improvements or new functions to be implemented in the project.