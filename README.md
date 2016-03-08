# csp
This project aims to update the open problems in Jim Pitman's Combinatorial Stochastic Processes book. 

We are looking for contributors, who are interested in saying a few things about an open problem of their choice.

Each contributor does a mini literature review on the problem, and send in a summary, split into two parts: latex and bib.

The latex file contains the problem description, and perhaps some comments (eg: your own motivation, references to solutions, partial solutions...)

The bib file contains the references.

If you are contributing to a new problem, please submit a latex file containing a mini literature review, and a bib file containing references. 

If you are contributing to an existing latex file substantially (beyond cosmetic edits), please add your name and github ID to the authors list. 

There is a template in
https://github.com/princengoc/csp/tree/master/sampleFormat
Please refer to this template for stylistic and naming conventions.

There are two ways to send in files to the project. The preferred option is that you request to be a contributor to this github. Otherwise, you can send the tex and bib files to Ngoc Tran (@math.utexas), or Jim Pitman (@stat.berkeley).

#I don't know Git...
Here is a quick-start guide to Git tailored for this project:
1/ Install Git on your system: http://git-scm.com/downloads
2/ Obtain a Github account: http://github.com
3/ Tell git who you are: open a terminal and type
<code> git config --global user.email your@email </code>
<code> git config --global user.name 'Your Name' </code>
4/ Go to
http://github.com/princengoc/csp
5/ Click the "Fork" button at the top right
6/ Open a terminal. Type
<code> git clone git@github.com:yourgitusername/csp </code>
You will now have a local copy of *your version* of this repository. 
7/ Go into that directory
<code> cd csp </cd>
8/ Add a connection to the central repository
<code> git remote add central git://github.com/princengoc/csp </code>
9/ Make changes to files. Say you have a .tex file problem1.tex  that you want to contribute. Make sure that it is in the same folder as your local csp folder.
<code>git add problem1.tex </code>
<code>git commit -m 'put a description of your commit here' </code>
<code>git push </code>
You can repeat this step each time you make changes to the file problem1.tex. The command git push will push all these changes to your version of the repository on github. 

Make sure at some point you add your name to contributors.txt by 
- opening contributors.txt (this file exists in the repo when you clone initially)
- Add:
<code>Your Name: your@email</code>
- commit your changes with git like commiting changes with all other files.
<code>git add contributors.txt</code>
<code>git commit -m 'Your Name added as contributor'</code>
<code>git push</code>

10/ When you are ready to contribute to the central csp project:
a/ Go to your version of the repository on github
b/ Click "Pull Request" at the top. The central repository will be on the left, your repository will be on the rght. 
c/ Click the green button "Create pull request". Give informative title, an explanation of the changes, and click the "Create pull request" button again. 

This tutorial is adapted from:
http://kbroman.org/github_tutorial/pages/fork.html

Excellent introduction to git:
http://git-scm.com/docs/gittutorial

Thank you for your interest! Suggestions most welcomed!

