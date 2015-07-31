Learngit
===

The goal of this project is to help YOU learn how to contribute to someone's project on GitHub.

This is a playground, and an educational tool.

Feel free to send pull requests and open issues.

If you do not already have an account with [GitHub](https://github.com), please sign up.

Add the output of this (your SSH public key) to Github under "Account Settings" -> "SSH Keys'
<pre>
  cat ~/.ssh/id_rsa.pub
</pre>

Fork the other project to your own Github account and clone to work with locally
<pre>
  git clone git@github.com:YOUR_GITHUB_NAME/learngit.git
  git remote -v
  cd learngit/
</pre>

Add a git remote for the upstream repository
<pre>
  git remote -v
  git remote add upstream git@github.com:unixmonkey/learngit.git
  git remote -v
  git pull upstream master
</pre>

Create a topic/feature branch (so you aren't working off of master)
<pre>
  git checkout -b my_awesome_new_feature
  git branch
</pre>

Edit some stuff and commit
<pre>
  vi stuff.md
  vi README.md
  git status
  git add README.md stuff.md
  git status
  git commit
  git status
  git log
</pre>

Push your changes to your Github fork
<pre>
  git push origin my_awesome_new_feature
</pre>

Go to Github and create a pull request from your commit

Wait for change to be merged in by original maintainer

Pull in merged changes
<pre>
  git checkout master
  git pull upstream master
</pre>

Delete your local topic branch
<pre>
  git branch -d my_awesome_new_feature
  git log
</pre>



Contributor:
`exodusftw`
