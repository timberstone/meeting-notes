---
layout: post
title:  "GitHub Push Start"
date:   2014-11-04 00:45:48
categories: github
---

In this exercise, you will add your name to a website hosted on GitHub, using only your browser.  The current list is at http://codeforkc.org/coders.html

This workflow is used by many open source projects to allow multiple people to contribute to one project.



# Login to your github.com account
If you don't already have a GitHub account you will need to create one at http://github.com




# Fork the KC Brigade Website

When you are editing a page, always work in a repository forked to your account. Whenever you fork a repository you will do it from the repositories page.

1. Go to the KC Brigade Website’s repository page by browsing to https://github.com/luminopolis/codeforkc.org

2. Click the Fork Button in the upper right hand corner of the page.  If you are a member of more than one organization, you will be asked where to fork it to.  

   There may be a small delay as it forks the repository.
   When the page refreshes you should be at your fork of the repository.
   
3. Take a look around your copy of the repository.

# View your fork in a browser

codeforkc.org uses GitHub Pages to host its site.  When you forked the code over to your account, that setup came with it.  

To view your version, just go to http://username.github.io/codeforkc.org, replacing username with your GitHub login.

If you are interested in hosting pages on GitHub go to https://pages.github.com/.

# Add your name to the list of coders

To see the current page go to http://username.github.io/codeforkc.org/coders.html.

To add your name to coders.html:  

1. Go to your fork of the site if you are not already there.

   https://github.com/username/codeforkc.org

2. Find coders.html in the list of files and click coders.html. The code screen appears.

3. Click the pencil just above the upper right of the code. The edit screen appears.

4. Add a line below the last ending `</li>` tag and type a new beginning `<li>` tag. The ending tag appears automatically.

5. Type your name between the list tags.  

   ```<li>Your Name</li>```

6. To see the changes, click the Preview Changes tab at the top of the edit box.

7. If you need to fix something, click the Edit File tab at the top of the edit box, and make the change.

#Commit your changes
1. Commit your changes so you can see them in your browser by filling out the Commit Changes section of the page below the Edit box.

2. Replace Update coders.html with Added your name to coders.html

3. Then press the Commit Changes button

4. To see your name on the coders.html page browse to http://username.github.io/codeforkc.org/coders.html

# Issue a Pull Request

A pull request asks the owners of originating repository to review and merge your changes into the repository, in this case http://codeforkc.org

1. Navigate back to the list of files in the repository. This should be at https://github.com/username/codeforkc.org. 

2. Click the green button above the list of files to the left.  This is a pull request link. The Create Pull Request page appears.

3. Enter a title and description.  An example title for this would be “Added Your Name to the coders list.” There is no need to fill in the description.

4.  Click the Create Pull Request button.
5.  If you are at a meeting, inform someone of the pull request.


