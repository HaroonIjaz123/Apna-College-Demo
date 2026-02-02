
<h1>Learning Github</h1>
<h4>Author-Haroon Ijaz</h4>

<hr>

<h2> Cloning a Repository: </h2>
<h6>Syntax:</h6>
<p> git clone link</p>
<h6>Example:</h6>
<p>git clone https://github.com/HaroonIjaz123/Apna-College-Demo.git</p>

<hr>

<h2> Git Status: </h2>
<p>Gives State of the Code <p>
<h6>Example:</h6>
<p>git status</p>
<h6>Types of Status:</h6>
<p><b>Untracked:</b>New files that git doesn't yet track</p>
<p><b>Modified:</b>changes in file</p>
<p><b>UnModified:</b>Unchanged file</p>
<p><b>Staged:</b>File is ready to be committed.<br><img src="Images/staged.png"><figcaption>Figure 1: Files staged and ready to commit</figcaption></p>

<hr>

<h2> Add Command </h2>
<p>Used to add new or modified files in current working directory to the Git staging area. <p>
<h6>Syntax:</h6>
<p>git add fileName.extension</p><p>Note: This adds only single file</p><br>
<p><b> To add all files for staging use the following syntax:</p><br>
<p>git add . </p>

<hr>

<h2> Commit Command </h2>
<p>Keeps record of changes. <p>
<h6>Syntax:</h6>
<p>git commit -m "Any Message"</p>
<h6>Example:</h6>
<p>git commit -m "New folder 'Images' added and 'README.md' is modified"</p><br>
<p>Note: This only commits  on local machine.</p><br>

<hr>

<h2> Push Command </h2>
<p>Uploades Local Repo cotent to the Remote Repo. <p>
<h6>Syntax:</h6>
<p>git push origin main</p>
<br>
<p>In the command git push origin main, origin refers to the remote GitHub repository where your project is stored, and main is the branch you are working on. This command sends the changes from your local main branch to the remote repository on GitHub so that your latest commits become available online.</p><br>






