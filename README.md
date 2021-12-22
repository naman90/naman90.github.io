# README #

Undo file checked in by mistake

https://www.youtube.com/watch?v=msUDPYsbABY&ab_channel=GitGuardian


1. git reset --soft HEAD~1. - This will open up last commit and add back file to stage
2. Now unstage wrong file individually using - git reset filepath(src/main...)
3. git commit -m  "New commit with correct file"
4. git push --force -  This will force remote to be exactly as local 

Git Rebase

git rebase -i HEAD~10
https://www.youtube.com/watch?v=gXCkYkLQ3To&ab_channel=BigBinary

A simple blog template for <a href="http://jekyllrb.com" target="_blank">Jekyll</a>.

Uses:
* Twitter Bootstrap 3.2.0
* Font Awesome 4.2.0


Here is a <a href="http://itsrifat.github.io/rifyll/" target="_blank">Demo</a>

To get started:
* Fork this repo
* Edit [_config.yml](_config.yml):
  * Change logo_location
* Edit [_data/menu.yml](_data/menu.yml) to edit menu
* Edit [_data/personal.yml](_data/personal.yml) to edit persnoal info to show in about me page.

To create a post:
* Create a **.md** or **.markdown** file in the _post directory. Add a thumbnail image for the post in the yml front matter, its shown as the post thumbnail in the homepage


Splunk Commands 

to see all values of fields in side list - <base search > | top limit=0 hosts
