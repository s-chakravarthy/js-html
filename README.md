# PS Documentation Project

## Front End
A static website hosted on Github pages acts as the front end of the tool. The website is designed using HTML and CSS and Javascript is used to interact with the Github Rest API.\
Users will interact with this front end to choose the required files from an existing templates repository.

## Back End
A repository of template files in the markdown format make up the back end of the website. All content is derived from this repository.

## Github Rest API
The API allows reading of file names and contents from a repository, as well as the creation of new repositories and files in it. The website utilises this ability to create the required files based on the user's choices and populates them with content from the existing files. 

# Step by Step Working of the Tool
1. The website displays the names of the files in the template repository using dropdowns and the necessary hierarchy.
2. The user makes selections based on the project they are working on.
3. A new repository is created for the user.
4. The Javascript code uses the filenames selected by the user to interact with the API to create the required files in the new repository and populate them with all the information from the existing files.






