 # Chapter 0 - Template for README.md, you can use in your repo.
``Originally, README.md was just for letting know, what's in your project. Now, people have found its new use case just for chapter compilation, like what we are doing in Chapter 1 and ahead ``

<img src="project-logo.png" align="left" width="192px" height="192px"/>
<img align="left" width="0" height="192px" hspace="10"/>

> Template files for writing maintanable GitHub projects. Make your repo pretty!

[![Under Development](https://img.shields.io/badge/under-development-orange.svg)](https://github.com/cezaraugusto/github-template-guidelines) [![Public Domain](https://img.shields.io/badge/public-domain-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/) [![Travis](https://img.shields.io/travis/cezaraugusto/github-template-guidelines.svg)](http://github.com/cezaraugusto/github-template-guidelines)

So you had an idea and developed the next world's industry-changing application. You decided to open-source it because you're way cool. Now you need to educate people about your project and need some docs to get started. You write that here. :alien:

<br>
<p align="center">
<strong>Templates included:</strong>
• <a href="/.github/CONTRIBUTING.md">CONTRIBUTING </a> • <a href="/.github/PULL_REQUEST_TEMPLATE.md">PULL REQUEST</a> • <a href="/.github/ISSUE_TEMPLATE.md">ISSUE TEMPLATE</a> • <a href="/.github/CONTRIBUTORS.md">CONTRIBUTORS</a>
</p>
<br>

**Installing**

Clone this project and name it accordingly:

``git clone git@github.com:sbibek086/Git-and-Github-Guides.git MY-PROJECT-NAME && cd MY-PROJECT-NAME``

**Getting Started**

This project is a collection of boilerplates with `CONTRIBUTING` and `CONTRIBUTORS` documentation. It also includes a basic `ISSUE_TEMPLATE` and `PULL_REQUEST_TEMPLATE`. All templates are filled under `.github/` folder. 

**Usage**
1. After installing, remove this file `rm README.md`.
2. Move the `README` template file located under `.github/` to the main directory `mv .github/README.md .` :cool:
3. Follow the basic usage guidelines in each file or make it your way. *The world is yours*.

> `CHANGELOG` References

> This boilerplate intentionally did not provide any `CHANGELOG` file as example, since [this tool](https://github.com/skywinder/github-changelog-generator) could make it automatically, fulfilling the file's objective.
> `CONTRIBUTORS` References

* [All Contributors](https://github.com/kentcdodds/all-contributors/)
* [All Contributors (CLI)](https://github.com/jfmengels/all-contributors-cli)

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification.
Contributions of any kind welcome!

## License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, sbibek086 has waived all copyright and related or neighboring rights to this work.




 # Chapter 1- Github Flow of commands

![About Git](https://user-images.githubusercontent.com/11883023/150847281-192341a7-7ad3-49e4-beb5-0c7934c8eebf.png)

the sequence in ant-walk diagram. is to be referenced only when we are using git remotes. However, when using github, it provides GUI buttons itself of what action to do next .github-ian little needs to remember this ant-walk chain of commands.

So, in real scenario, in stick fig diagram, if base worker has to write in bash aka terminal aka cmd prompt, he has to write in below seq:
`git push origin master`

WHY? because he is pushing that new version created by adding README.md in his localmachine (ie MASTER repo) to origin.
So he is PUSHING new version to ORIGIN (my github repo) from MASTER.

PS: orgin and master are default names pegged to respective directories in my github repo and localmachine repo ,and can be customized by github remote add origin url

In a way, in stick diagram, two stickfigures can be misleading. the stick-figure at top need not have to be there because it can be entirely me (stick-figure at base) pushing to my github repo from my localmachine.

Now lets make it so that Bob sees my github repo. He has forked it to github_com/Bob/BibeksPrj and testedOKmerged some graphics feature ,and submits me PULL REQUEST (he is REQUESTING me to PULL his work on my repo)

so to pull it to my Graphics repo, which is localhosted in my browser, I write in my bash
`git pull Bob Graphics`
which means PULLING from Bob's repo to not my master but GRAPHICS branch on my localmachine

Ok, I love the result output in my broswer.
THEN,  `git commit -m`
THEN, `git checkout master` TO switch from GRAPHICS branch to my MASTER
THEN, `git merge graphics` SO it merges to my master in localmachine

THEN, `git push origin master` TO reflect it finally on my github repo also.

*PUSH TO, PULL FROM is easy way to remember, which means git push origin master means push TO origin from master ,and similar for git pull.. *

[this tutorial was based on coding train V at 7:05](https://www.youtube.com/watch?v=lR_hYwCAaH4)

---
*I always thought I should install that seperate git CLIs. I was wrong. 
All i have to do: goto Terminal in Vstudio , then in its terminal, point directory to ...xampp/htdocs so that I can clone git remote urls docs inside htdocs. So, now I can change it to see its compilation result in browser, at the same time, can change, commit etc to reflect changes in git ready docs.*

---
# Chapter 2 - Breaking down Settings Panel of each Github repo

![Github Settings Panel](https://user-images.githubusercontent.com/11883023/119841559-a3ef5b80-bf25-11eb-9522-363562522f78.jpg)

---
# Chapter 3 - Assets aka output files of Github repo
![Assets-File-Of-Github](https://user-images.githubusercontent.com/11883023/168144371-a71e2dca-50c7-4704-ae2a-bbf2416bb7d6.jpg)
Most of the assets in Github repo are either in .tar or .Linux or .mvcc.zip or gnu.zip.  
- mvcc stands for Microsoft Visual C++ compiler ,and is native in typical Windows OS. Also, If I unzip mvcc.zip, there's SHA256 file inside it.  
- Gnu.zip works in Windows OS that has GNU compiler.  

 `Did you know that UNIX OS are designed to do just one thing better. Windows OS revolted against such specific purpose but were proprietary locked but LINUX also revolted against such UNIX style specific purpose and were Open source..`
 
 ---
# Chapter 4 - Permission levels of different Roles in Personal repo (Organization Repo not covered) tried to be Venn-Diagram simplified 
[Here is its official docu](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-user-account-settings/permission-levels-for-a-user-account-repository#further-reading). We hope to convey this information little easier

![Permission-different-roles](https://user-images.githubusercontent.com/11883023/168208559-2db54797-73b2-4228-bc56-fbb8713090e3.png)

---
# Chapter 5 - Developer Settings in Github
Here, we are not talking about plain GUI settings like how your github profile theme would look -dark or white? ,or what your SSH or GPG keys of your github account should be *(I know, SSH GPG keys sound alien now, and will cover below in suitable day)*
But for now, we are talking about settings that you can adjust lot wholesome way like with scripts, rightly called Developer Settings, for which we have to go github_com/settings/apps | developers | tokens for github apps, OAuth *stands for Open Authorization* and Personal Access tokens respectively.
Let's start with Personal Access tokens:
![image](https://user-images.githubusercontent.com/11883023/168462058-c3739a7f-ab5e-4e83-b38e-720e0b928b79.png)
[This Video](https://www.youtube.com/watch?v=kHkQnuYzwoo) would help too. 

---
# Chapter 6 - Setting up Public template as new repo template, Speed vs Inflexibility, which to opt for?
![image](https://user-images.githubusercontent.com/11883023/168464154-02c86efc-26a0-4c70-9e35-e6838d2b3571.png)

Now, it gives me question of what exactly is difference between public template and boilerplate? 
Currently, my understanding is: boilerplates are like templates which already has Layer 0 folders required for adding up next layer application logic folders.

---
# Chapter 7 - Working with Boilerplates - Problems faced and its solutions:
[Boilerplate repos](https://github.com/sbibek086/boilerplate) are great way to speed up dev process - lot faster than w the sdk ways in my still novice opinion. Still is unchartered territory to me.
Stuck with this Host key verification failed error

**Problems:** I was quite lost with whether github username password that I have passed in my machine is still stored in cache an thats creating trouble as i have changed github.com password ever since between.
`git config --global username.password <>` do not seem to be much of rescue tho. //My intention was to so that I could feed my newly github password to my machine.

I was doing the way of git clone <https://> way
but SSHing is another way I could locally transfer ,and havent tried it tho.

Solutions:
github has stopped supporting acc passwords. Now it requires token-based authentication (for example, a personal access, OAuth, or GitHub App installation token) for all authenticated Git operations. Excerpt from:https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/
what we should do: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

But when we visit this, 
`we see it says to update iCloud Keychain's github pws, WHY? because brave lets u store pws for onlne accs NOT for localmachine pws like in this case pw stored aka cached in localmachine that for github- its assuming user is Mac-er & hence iCloud should be there by default but since for Asian windower like me, closest thing we can get is install 'iCloud For Windows' in Windows.`
and after installing iCloud App, it says to setup Windows Hello Pin and hence below screenshost 
![1645122243461](https://user-images.githubusercontent.com/11883023/168464424-50d7d58d-32b6-441d-a936-8042b294c431.jpg)

https://support.apple.com/guide/icloud-windows/set-up-icloud-passwords-icw2babf5e03/icloud seems to answer this above issue.
---
# Chapter 8- This repo itself is Template repository 
*Have I solved Chapter 7 issue with this method. I dont know for now, and I dont want to del Chapter 7 quickly. But this is Template repo itself as you can see 'Use this Template in upper belt navigation, which doesnt come for normal repo*
Just use it as template- the root layer file structure will be duplicated in your new github repo. 

---
#Chapter 9 - Environments, while you go to settings in repo. What are they?
<iframe width="560" height="315" src="https://www.youtube.com/embed/nI6pRfH7VTc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
