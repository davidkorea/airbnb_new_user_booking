# airbnb_new_user_booking# airbnb_new_user_booking
 
# Iuuse1 - git revert origin/master

if you git wrong things and push origin --- error

you need to go back to the last time you successfully push git submit

- locally reset to before
    ```git reset --hard 2659f94459be19e7f2bf489d6d148bec30a08094```
- push previous local to github again by force
    ```git push origin --force```

$```git log```as below:

```
commit f7c406475e5e9fa2186e97376e4bce7e48594d3a
Author: davidkorea
Date:   Tue May 15 16:53:35 2018 +0900

    session.csv

commit 2659f94459be19e7f2bf489d6d148bec30a08094 (origin/master, origin/HEAD)
Author: davidkorea
Date:   Tue May 15 16:37:14 2018 +0900

    subplot function
```
 
- ```vim .gitignore```
- ```data/sessions.csv```, ```./data/sessions.csv```is wrong
- ```:wq```
