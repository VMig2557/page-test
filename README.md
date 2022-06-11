# Page Test

## Clone the project

*  Fork this project into a personal repository.
   * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the new repository.
* Clone the repo from **your account** into the directory on your computer.
* Open the newly cloned project in VSCode.

## Edit the cloned project: HTML

* Enter the index.html file and locate the h1 tag with "greeting" as an attribute
* Change the "Remove this and make your own greeting" text and insert your own

## Edit the cloned project: CSS

* Now move into the project's directory in VSCode and locate the "assets" folder
* Click on the "style.css" file to edit it
* Hover over the RGB square and change it to another color

# Using Live Server to check changes
 
 * From the left side tabs on VSCode, click on the "Extensions" tab
 * Use the search bar to search for "Live Server" and install it
 * Go back to your project folder in VSCode and right click on "index.html"
 * You should see an option to "open with Live Server"
 * You should now be able to see your page

## Pushing the changes

* From the terminal go to the root of the _cloned_ project.
* From the root directory of the project, execute the following commands:
    * `git add .`
        * To add all changes to the staging area
    * `git commit -m 'I have made an edit to a file!'`
        * Save all staged changes to local repository
    * `git push -u origin main`
        * Push changes from local repository to remote repository

* Finally check github for the changes
