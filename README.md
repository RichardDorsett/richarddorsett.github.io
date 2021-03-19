# richarddorsett.github.io

These are notes for my own use

# Create content
I keep two CSV files - projects and publications.  These can be updated as required.  Each project has a unique identifier.  This project identifier appears in both the projects and publications files, allowing outputs to be linked to projects.

Update the website by editing the CSV files as appropriate.  After updating, run the Julia code that reads the CSV files and writes the pages and posts.

There are some pages that are not updated by this process and need to be edited manually.  These are all Markdown pages:

* research-areas
* methods
* publications
* about

# VS Code
I use VS code for editing CSV files (can also use Excel) and running the Julia code.  I can also run a Ruby session to build a local copy of the website (useful as a check if making a more substantial change).  To do this, simply open one of the Markdown files and enter `ctrl+'`.  After that, issue the command `gem install jekyll bundler` and then `bundle exec jekyll serve` (in fact, `bundle exec jekyll serve --incremental` runs faster when building a local site, although will not cope with changes to the yml file).

I can edit any of the fixed files in the bullet points above in VS Code.  That this can be done with a preview using `ctrl+k v`.

Once all the changes have been made, I can commit and then push to Github.  This is all done within VS Code - I click on the Github icon on the left (or `ctrl+shift+g'), click on the "+" that appears against each change shown in the tree (doing this for the folder will select all) in order to stage the changes, write a commit message, click on the tick to commit the changes, click on the three dots to get more options and select "Push".  That should be it.