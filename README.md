# richarddorsett.github.io

These are notes for my own use.

# Create content
I keep two CSV files - projects and publications.  These can be updated to incorporate new projects/outputs.  Each project has a unique identifier which appears in both the projects and publications files, allowing outputs to be linked to projects.

Update the website by editing the CSV files as appropriate.  After updating, run the Julia code (mkposts.jl) that reads the CSV files and writes the pages and posts for the website.

There are some pages that are not updated by this process and need to be edited manually.  These are all Markdown pages:

* research-areas
* methods
* publications
* about.

Also, all the pages within the following folders 
* _pages/methods
* _pages/research-areas.

# VS Code
I use VS code for editing CSV files (can also use Excel - that is a bit easier for the projects.csv file), running the Julia code and building the website with Jekyll.  The workflow is as follows:
* update CSV file(s)
* run mkposts.jl
* make any manual edits to the Markdown files.  This can be done with a preview using `cmd + k v`.
* open the terminal (shift + ctrl + `)
  * navigate to RichardDorsett.github.io (not necessary if the terminal is already in the correct location, eg by adding folder to workspace)
  * run the following commands
    * bundle install
    * bundle exec jekyll serve
  * inspect http://127.0.0.1:4000/
  * if happy with the changes, commit and push to Github (all within VS Code)
    * click on the Github icon on the left
    * click on the "+" that appears against each change shown in the tree (doing this for the folder will select all) in order to stage the changes, write a commit message
    * on the "Commit" box, select "Commit & Push".  That should be it.

# How I used to do this with a Windows machine
In the past (using Windows) I would run a Ruby session to build a local copy of the website (useful as a check if making a more substantial change).  To do this, simply open one of the Markdown files and enter `ctrl+'`.  After that, issue the command `gem install jekyll bundler` and then `bundle exec jekyll serve` (in fact, `bundle exec jekyll serve --incremental` runs faster when building a local site, although will not cope with changes to the yml file).  If this doesn't work, try `bundle add webrick` and then `bundle exec jekyll serve` again.

I can edit any of the fixed files in the bullet points above in VS Code.  This can be done with a preview using `ctrl+k v`.

Once all the changes have been made, I can commit and then push to Github.  This is all done within VS Code - I click on the Github icon on the left (or `ctrl+shift+g`), click on the "+" that appears against each change shown in the tree (doing this for the folder will select all) in order to stage the changes, write a commit message, click on the tick to commit the changes, click on the three dots to get more options and select "Push".  That should be it.