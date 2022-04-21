# portfolio-static_node_and_express

## Note that this site runs on localhost:3000


## Installation

run `npm install` to install all dependencies.  Then run `npm start` to start the server.


## Development

* The images for each project page are 1200 X 550 pixels.
* The images for the portfolio page are  550 X 550 pixels.

* All project data is stored in `data.json`  It is a JSON file that has a `"projects"` array.  Each item in the array is a project containing the following keys: 
    * id - manually assigned unique id for each project
    * project_name - name of the project
    * description- description of the project
    * technologies - array of technologies used in the project
    * main_image - image of the main page of the project
    * live_link - link to the live version of the project
    * github_link - link to the github repo of the project
    * image_urls - array of the filepaths for each image for the project