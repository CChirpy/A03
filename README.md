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
