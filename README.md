Learngit
===


Thank you for attending tonight's [indyrb meetup](http://www.meetup.com/indyrb/).

Tonight's goal is to learn how to contribute to someone's project on GitHub. If you do not already have an account, please sign up.


Thank you everyone who already uses git for sitting through this.

My commands
<pre>
  503  cat ~/.ssh/id_rsa.pub
  504  clear
  505  cd git
  506  git clone git@github.com:ghoneycutt/learngit.git
  507  git remote -v
  508  cd learngit/
  509  git remote -v
  510  git remote add upstream git@github.com:unixmonkey/learngit.git
  511  git remote -v
  512  git pull upstream master
  513  git checkout -b my_awesome_new_feature
  514  git branch
  515  vi stuff.md
  516  vi README.md
  517  git status
  518  git add README.md stuff.md
  519  git status
  520  git commit
  521  git status
  522  git log
  523  git push origin my_awesome_new_feature
  524  git checkout master
  525  git pull upstream master
  526  git branch -d my_awesome_new_feature
  527  git log
</pre>
