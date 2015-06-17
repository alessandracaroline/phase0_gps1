# phase0_gps1
~ :> git clone https://github.com/alessandracaroline/phase0_gps1.git
Cloning into 'phase0_gps1'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Checking connectivity... done.

Clone the repo to local computer

~ :> cd phase0_gps1/

go into new repo directory

phase0_gps1 [master] :> touch awesome_page.md

create new file awesome_page.md

phase0_gps1 [master] :> git add .

add new file to staging to be commited

phase0_gps1 [master] :> git commit -m "add file awesome"
[master c216c9a] add file awesome
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 awesome_page.md
phase0_gps1 [master] :> git push origin master
Username for 'https://github.com': alessandracaroline
Password for 'https://alessandracaroline@github.com':
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/alessandracaroline/phase0_gps1.git
   907495d..c216c9a  master -> master

commit file

phase0_gps1 [master] :> git co -b "add-command-log"
Switched to a new branch 'add-command-log'

create new feature branch
