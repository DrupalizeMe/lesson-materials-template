## What Is This?

This directory contains database snapshots for various points throughout a tutorial. Likely each snapshot will correspond to an individual lesson. Snapshots should be named to that it's easy to figure out what lesson they correspond with.

Example:

`lesson-6.sql.gz`

## How To

From the root directory of your repository:

`mysqldump -q --opt --add-drop-table {DATABASE_NAME} | gzip > docroot/lesson-6.sql.gz`
