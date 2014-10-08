Instructions for how to use the files in this repository.

This serves as a starting point for creating and collecting materials used in a demo. Every new series should start from this template.

Start by downloading the files in the repository by clicking the button on the right. You really won't need a clone of the repository.

Unzip the files and rename the resulting directory according to the naming convention `demo-NAME-DRUPAL_VERSION`. For exmaple: `demo-services-7x`. Create a corresponding new GitHub repository, with the same name. And then link the two.

Example:

````
git remote add origin git@github.com:DrupalizeMe/demo-services-7x.git
git push origin master
````

As you progress through the various lessons that make up your tutorial you'll want to create a new branch of reach lesson. Branch names should be numbered according to the lesson which they apply to.

Example:

`git checkout -b 03-installing-services`

At the conclusuion of each lesson you'll want to create a new snapshot of the database and place it into the `data/` directory. See the README file there for instructions. Then, create a new commit with any changes you've made during that lesson and the new database snapshot file.

Example:

````
git add -A
git commit -m "End of lesson 3."
````
