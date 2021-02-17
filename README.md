# A03

Today we are going to talk version control on <b>GitHub</b>.  We will go over <b>Git</b>, <b>GitHub</b>, and how to set up your IDE (In this case, JetBrains Webstorm) to use version control via <b>Git</b>.

<h2>Lets go over <b>Git</b>.</h2>

<b>Git</b> is an open source project that is made for version control.  What is version control?  Simply put, if I make a change on one device, all the other devices get an update.  For instance, I'm working on the code for a brand new website.  I would like to keep my work documented and backed up.  This is how <b>Git</b> can help.  It takes any file changes and logs them under compartmentalized modifications that it labels as <b>Commits</b>.  Every <b>Commit</b> saves the time and date it is made, and the specialized message the user assigns to it.  For an example of this, Check the second <b>commit</b> on this <b>repository</b>.  As you can see it shows that I made the introduction to <b>git</b>.  <b>Git</b> can also be used as a way to collaborate.  If me and my friend want to work on the same bit of code, I only need to give that friend access to the <b>repository</b>.  But where are these <b>repositories</b> hosted?  This is where <b>GitHub</b> comes in.

<h2>What is <b>Github</b>?</h2>

<b>Github</b> is a <b>Git</b> hosting service which is currently run and maintained by Microsoft.  What makes it special?  Other than keeping all of your code and work safe and secure on a completely free hosting service, there is also in depth version control.  Using the power of <b>Git</b> you can see every little change shown on a clean web UI.  Every <b>push</b>, every <b>pull</b>, every <b>merge</b>, and every <b>clone</b> that is made on a <b>repository</b> is logged and documented.  It allows for a clean work flow and an extremely versatile update delivery service.  But how do we use <b>Git</b>?

<h1>First Lets talk how to use <b>GitHub</b>.</h1>

In reality there are many ways to access <b>Git</b>.  The two most common ways are via GitBash and GitGUI.  We will be going over GitBash today.  GitBash is a command-line based <b>Git</b> control system.  First step is installing the program itself.

<h3>Step One: Installing GitBash</h3>

Use your favorite browser to navigate to: https://git-scm.com/downloads.
From there you want to choose which Operating System you are running.  Follow the on screen instructions there until you have completed install.
Now we go over how to set up your very first <b>Repository</b>.

<h3>Step Two: Setting up a Repo</h3>

Congratulations! You've installed GitBash.  Now we are going to make our first <b>Repository</b>.

<ul>
  <li>First create a directory to make your <b>Repository</b> in.</li>
  <li>Next you want to actually go into that new directory.</li>
  <li>At this point you should navigate your Git Bash Client to the directory using the <code>CD</code> command<br/></li>
and example of this is <code>CD C:/Users/Sherwin/Documents/GITHUBREPO</code>
  <li>Once you are navigated you can type in <code>git init</code> (This initializes the <b>repository</b>)</li>
  <li>Go ahead an make a text file in the directory you just made.</li>
  <li>Now, back in Git Bash type in <code>git add</code> and the name of your file following a space.</br>
This should mark the file for Git's retrieval</li>
  <li>Finally you want to type in <code>git commit</code></br>
This should move the file to a <b>commit</b></br>
If you do <code>git commit -m "My message here"</code> You can modify the commit message.</li>
</ul>

With that you have made your First <b>Repository</b>  This Repo is only on your machine however, you have not yet hosted it on <b>GitHub</b>.  Now we go over how to send your <b>Git</b> to a <b>remote</b>.

<h3>Step Three: Linking <b>GitHub</b> to your Repo</h3>

Lets link that <b>Repository</b> to a <b>GitHub</b> repo.

<ul>
  <li>First Thing you want to do is navigate to http://github.com</li>
  <li>Login to a GitHub account or make a new one for free.</li>
  <li>On the top right corner there will be a plus.  Click the plus and click "New Repository"</li>
  <li>Modify your settings as required and click "Create Repository"</li>
  <li>Now, on your Git Bash you will type <code>git remote add origin http://github.com/yourusername/yourrepo</code></br>
  This means that your <b>repository</b> now has a <b>remote</b> access to <b>GitHub</b></li>
  <li>Finally, perform <code>git push -u origin master</code></br>
  This means you are <b>pushing</b> the update to your Origin which we defined in our <b>remote</b> in the master <b>branch</b>.</li>
</ul>

<h3>Step Four: Dealing with <b>Merges</b> and <b>Merge Conflicts</b></h3>

I won't pretend that this is easy.  Whenever a <b>Merge Conflict</b> occurs, there is many ways to deal with it.  Atlassian wrote a great article on it here:https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts.

<h3>Webstorm integration with GitHub</h3>

If you are using Jetbrains Webstorm there is a dedicated Git Tab for the program.  Using this you can use the above tutorial to set up version control within your IDE.

<h1>Glossary</h1>

<ul>
  <li><b>Branch</b>- A branch is a divergence from the main development path.  Most Gits have a master branch where the final product is.  Some also have a testing branch</li>
  <li><b>Clone</b>- A command in Git that allows you to completely copy the repository specified to a new repo.</li>
  <li><b>Commit</b>- Making changes which stages onto the current branch ready to be pushed. </li>
  <li><b>Fetch</b>- Download Specific files and references from other repos.</li>
  <li><b>GIT</b>- Git is the opensource version control system.</li>
  <li><b>GitHub</b>- A place where Git repositories are hosted.</li>
  <li><b>Merge</b>- To take the contents of code from one repository and append them and add them to another.</li>
  <li><b>Merge Conflict</b>- An error that occurs when trying to put two repos together.</li>
  <li><b>Push</b>- Moving the change from staging to the branch specified in the repo specified from your computer.</li>
  <li><b>Pull</b>- Pulling the latest files from the branch specified in the repo specified to your computer.</li>
  <li><b>Remote</b>- A destination that is decided to send data to, usually the Github repo link.</li>
  <li><b>Repository</b>- A place where all data and changes are stored and documented. </li>
</ul>

<h3>References</h3>
<ul>
  <li>https://blog.axosoft.com/learning-git-repository/</li>
  <li>https://git-scm.com/</li>
  <li>https://www.jetbrains.com/help/webstorm/meet-webstorm.html</li>
  <li>https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts</li>
  <li>My own routine and knowledge</li>
 </ul>
 
 This Project was created by Sherwin Rahimi (sr844@njit.edu)
