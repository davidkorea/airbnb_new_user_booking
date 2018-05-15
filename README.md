# airbnb_new_user_booking# airbnb_new_user_booking
 
# Iuuse1 - git revert origin/master

if you git wrong things and push origin --- error

you need to git revert origin/master to go back to the last time you successfully push git submit

- locally reset to before, ```git reset --hard 2659f94459be19e7f2bf489d6d148bec30a08094```
- push previous local to github again by force, ```git push origin --force```

$```git log```as below

```
commit 0c86a88e52668d5b1092694d082a86653de00582 (HEAD -> master)
Author: davidkorea
Date:   Tue May 15 17:06:43 2018 +0900

    revert dut to big size csv

    Revert "subplot function"

    This reverts commit 2659f94459be19e7f2bf489d6d148bec30a08094.

commit df8a7d4c669595ba83be13c5402e7b1ccfa339a6
Author: davidkorea
Date:   Tue May 15 17:01:46 2018 +0900

    gitignore

commit ad86cdbede40d55d481746cedfa8a7e784ba8924
Author: davidkorea
Date:   Tue May 15 17:00:38 2018 +0900

    remove session.csv

commit d9d0942274342d99554012ff298c5e1b3df2b0c4
Author: davidkorea
Date:   Tue May 15 17:00:09 2018 +0900

    ??reset

commit f7c406475e5e9fa2186e97376e4bce7e48594d3a
Author: davidkorea
Date:   Tue May 15 16:53:35 2018 +0900

    session.csv

commit 2659f94459be19e7f2bf489d6d148bec30a08094 (origin/master, origin/HEAD)
Author: davidkorea
Date:   Tue May 15 16:37:14 2018 +0900

    subplot function
```
