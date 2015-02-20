Instructions for how to use the files in this repository.

This serves as a starting point for creating and collecting materials used in a demo. Every new series should start from this template.

Start by downloading the files in the repository by clicking the button on the right. You really won't need a clone of the repository.

Unzip the files and rename the resulting directory according to the naming convention `demo-NAME-DRUPAL_VERSION`. For example: `demo-services-7x`. Make this local directory a local git repository by running `git init`. Then add and commit these files to the local repository.

Example:

````
git add *
git commit -am "Creating new demo repository."
````

Create a corresponding new GitHub repository (https://github.com/organizations/DrupalizeMe/repositories/new), with the same name. And then link the two by adding the GitHub repository as a remote.

Example:

````
git remote add origin git@github.com:DrupalizeMe/demo-services-7x.git
git push origin master
````

As you progress through the various lessons that make up your tutorial you'll need to create a new branch for each lesson. Branch names should be numbered according to the lesson which they apply to.

Example:

`git checkout -b 03-installing-services`

At the conclusuion of each lesson create a new snapshot of the database and place it in the `data/` directory. See the README file there for instructions. Then, create a new commit with any changes you've made during that lesson and the new database snapshot file.

Example:

````
git add -A
git commit -m "End of lesson 3."
````
