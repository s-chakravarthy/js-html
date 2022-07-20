# PS Documentation Project

## Front End
A static website hosted on Github pages acts as the front end of the tool. The website is designed using HTML and CSS and Javascript is used to interact with the Github Rest API.\
Users will interact with this front end to choose the required files from an existing templates repository.

## Back End
A repository of template files in the markdown format make up the back end of the website. All content is derived from this repository.

## Github Rest API
The API allows reading of file names and contents from a repository, as well as the creation of new repositories and files in it. The website utilises this ability to create the required files based on the user's choices and populates them with content from the existing files. 

## Step by Step Working of the Tool
1. The website displays the names of the files in the template repository using dropdowns and the necessary hierarchy.
3. The user makes selections based on the project they are working on and clicks submit.
4. A new repository is created for the user.
5. The Javascript code interacts with the API and uses the filenames selected by the user to create the required files in the new repository. It then matches the selected filenames with the existing filenames to get the content from the template repository and writes the content into the equivalent files in the new repository.

## Limitations
Static websites only allow for a single page website with the same content being displayed for all users. If dynamic features such as a login portal or multi-page websites are required, dynamic website hosted using services such as Azure WebApps is required.






