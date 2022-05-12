
#Chapter 1- Github Flow of commands
![github-flowchart](https://user-images.githubusercontent.com/11883023/119141875-8756ad80-ba65-11eb-94e1-9810bf54e158.jpg)
--
the sequence in ant-walk diagram. is to be referenced only when we are using git remotes. However, when using github, it provides GUI buttons itself of what action to do next .github-ian little needs to remember this ant-walk chain of commands.
 --
so, in real scenario, in stick fig diagram, if base worker has to write in bash aka terminal aka cmd prompt, he has to write in below seq:
`git push origin master`
WHY? because he is pushing that new version created by adding README.md in his localmachine (ie MASTER repo) to origin.
So he is PUSHING new version to ORIGIN (my github repo) from MASTER.

PS: orgin and master are default names pegged to respective directories in my github repo and localmachine repo ,and can be customized by github remote add origin url
---
In a way, in stick diagram, two stickfigs. can be misleading. the stick-figure at top need not have to be there because it can be entirely me (stick-figure at base) pushing to my github repo from my localmachine.
---
Now lets make it so that Bob sees my github repo. He has forked it to github_com/Bob/BibeksPrj and testedOKmerged some graphics feature ,and submits me PULL REQUEST (he is REQUESTING me to PULL his work on my repo)
so to pull it to my Graphics repo, which is localhosted in my browse, I write in my bash
`git pull Bob Graphics`
which means PULLING from Bob's repo to not my master but GRAPHICS branch on my localmachine
This above tut was from [this coding train V at 7:05](https://www.youtube.com/watch?v=lR_hYwCAaH4)
ok, I love the result output in my broswer.
THEN,  `git commit -m`
THEN, `git checkout master` TO switch from GRAPHICS branch to my MASTER
THEN, `git merge graphics` SO it merges to my master in localmachine

THEN, `git push origin master` TO reflect it finally on my github repo also.
--
*I always thought I should install that seperate git CLIs. I was wrong. 
All i have to do: goto Terminal in Vstudio , then in its terminal, point directory to ...xampp/htdocs so that I can clone git remote urls docs inside htdocs. So, now I can change it to see its compilation result in browser, at the same time, can change, commit etc to reflect changes in git ready docs.*
