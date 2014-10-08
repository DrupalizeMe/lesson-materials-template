## What Is This?

This directory should contain Drupal, and all the code that makes up the site used in a tutorial.

## Getting Started

Ready to start a new series? Copy Drupal's code into this directory and make a first commit.

From the root of this repository:

````
drush dl drupal
cp -R drupal-7.31/. docroot/.
rm -r drupal-7.31
git add -A .
git commit -m "Initial commit of Drupal"
````
