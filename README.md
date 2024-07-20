# Primary Class a

![image](https://github.com/sbibek086/Git-and-Github-Guides/assets/11883023/b2a6be3a-f182-4d2c-91b9-129f0d6381cd)

https://www.youtube.com/watch?v=_C5AHaS1mOA 

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
 • <a href="/github/PULL%20REQUEST.md">PULL REQUEST TEMPLATE</a> • <a href="/github/ISSUE_FOR_FEATURE_U_MORE_WANT_.md">ISSUE TEMPLATE FOR FEATURE YOU MORE WANT</a> • <a href="/github/ISSUE_FOR_BUG_U_FIND.md.md">ISSUE TEMPLATE FOR BUG YOU FIND</a>
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

Contributions of any kind welcome!

## License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, sbibek086 has waived all copyright and related or neighboring rights to this work.


फुल क्लास प्याकेज शुल्क - रु ५००० मात्रै

समय: बेलुका ६ देखि ७ बजेसम्म

८ कक्षा भन्दा माथि देखि SLC, +2 दिएर  बसेका हरुलाई उपयुक्त

अवधि: १५ वटा क्लास

शनि, सोम, बुध र शुक्रबार

रोजगारको प्लेसमेन्ट पनि गरिनेछ, पर्फमेन्स उत्कृष्ट गर्नसक्नु भएमा ।

 # Chapter 1- Github Flow of commands

![About Git](https://user-images.githubusercontent.com/11883023/150847281-192341a7-7ad3-49e4-beb5-0c7934c8eebf.png)

![image](https://github.com/user-attachments/assets/fb5696f3-7839-40ce-8de1-dacb29aa2113)

![image](https://github.com/user-attachments/assets/ff7d7d47-79a2-4fd9-9a48-59a97aafc0bd)

माथिको चित्रमा रहेको कमान्डको सिक्वेन्स केवल git remote प्रयोग गर्दा मात्र गर्ने हो। यद्यपि, जब तपाइले github प्रयोग गर्दा, githubमा GUI बटनहरू हुन्छन् जसले तपाइलाई कुन पछि कुन गर्ने भनेर देखाउँदै जान्छ। त्यसैले github प्रयोगकर्ताले कमान्डको सिक्वेन्स सम्झनु पर्दैन।

त्यसैले, वास्तविक कामको अवस्थामा, स्टिक फिगर चित्रमा देखाए जस्तो, तल रहेको वर्कर A ले माथिको worker B लाइ नया संस्करण पठाउनु पर्दा,  bash अर्थात् टर्मिनल अर्थात् command promptमा यसरी लेख्नुपर्ने हुन्छ:

`git add .`

`git commit`

`git push origin master`

किन? किनकि उसले आफ्नो लोकल मेसिन या नी की आफ्नो कम्प्युटरमा (अर्थात् MASTER repo या नी की File मा) README.md थपेर बनाएको नयाँ संस्करणलाई originमा push गरिरहेको छ।
सरल भाषामा भन्दा, उसले MASTER बाट ORIGIN (मेरो github repo) मा नयाँ संस्करण धकेलिरहेको छ।

PS: orgin मेरो-मेसिन म या नी की यो प्रसंगमा worker B र र master नाम उसको स्थानिय मेसिन रिपो या नी की worker B को लागि पूर्वनिर्धारित नामहरू हुन् र यसलाई github remote add origin url द्वारा अन्गय नाममा भने change गर्न सकिन्छ।

![image](https://github.com/user-attachments/assets/ff7d7d47-79a2-4fd9-9a48-59a97aafc0bd)

_माथिको चित्रमा, सधै दुई जना चित्रित व्यक्तिहरू, रियलमा दुइजना नहुन सक्छन्। - जस्तो की म आफैं (तलको Worker A)ले मेरो स्थानिय मेसिनबाट, (माथिको Worker B)मेरो गिटहब रेपोमा push गरिरहेको हुन सक्छु।_

अब यसलाई यस्तो परिस्थितिमा हेरौं कि Bob ले मेरो github रेपो देख्छ। उसले यसलाई github . com/Bob/BibeksPrj मा github fork गरेको छ र graphics feature परीक्षण गरी मर्ज या नी की थप्न खोजेको छ भनेि (उसले मलाई आफ्नो थपेको काम, मेरो रेपोमा PULL गर्न अनुरोध गरिरहेको छ) उसले मलाई PULL REQUEST submit गर्छ।

त्यसैले मेरो graphics repo मा, उसले थपेको संस्करण पुल गर्न या नी की ल्याउन, मैले मेरो command prompt मा लेख्नुपर्छ:
`git pull Bob Graphics`

माथिको कमान्डको मतलब, Bob को रिपोबाट, मेरो मास्टरमा नभई, मेरो मेसिनको GRAPHICS branchमा मैले PULL गर्दैछु।

उसले थपेर दिएको कामको रिजल्ट मैले मेरो google chrome browser मा कम्पाइल भएर खुल्दा रिजल्ट भनेजस्तै ok छ भने मैले -

`git commit -m`

त्यसपछि, `git checkout master`  - यसले GRAPHICS शाखाबाट मेरो MASTER शाखामा स्विच गर्न

त्यसपछि, `git merge graphics`  - यसले GRAPHICS शाखाबाट परिवर्तनहरू मेरो स्थानिय मेसिनको मास्टर शाखामा मर्ज गर्छ

त्यसपछि, `git push origin master` - यसले अन्तत मेरो गिटहब रेपोमा परिवर्तनहरु प्रतिबिम्बित गर्नेछ

सम्झिन सजिल'री चाहनुहुन्छ भने PUSH TO, PULL FROM भनेर सम्झिनुस् है, जसको मतलब 

git push origin master means push TO origin from master

git pull A B means pull from A to B [.](https://youtu.be/lR_hYwCAaH4?si=JIZ2LMIt-VZwJeKr&t=425)

![image](https://github.com/user-attachments/assets/24eb0c28-ff86-42c6-a732-556fee8871af)

---
---
अबको तलको लेखाइ, मैले IT कम्पनी -YIlab मा परीक्षणकर्ता या नि की 'टेस्टर'को रूपमा काम गर्न थालेपछि लेखें। त्यसैले, यो टेस्टरको दृषटिबाट तल अनुसार गर्नुपर्छ:

अब म परीक्षणकर्ता हुँ। 

_अर्थात्, माथिको कथा पुसर अर्थात् विकासकर्ताको दृष्टिकोणबाट थियो, जसले केही सुविधाहरू थप्छ र मर्जर अर्थात् Chief Technical Officer CTOलाई production अर्थात् लाइभ सर्भरमा मर्ज गर्नका लागि बुझाउँछ।)_

तर, अब म परीक्षणकर्ता हुँ, जसले विकासकर्ता या नि की 'डेभलोपर'बाट, सबैभन्दा पछिल्लो संसोधित काम मात्र आफ्नो कम्प्युटरमा तान्छ या नी की pull** गर्छ र परीक्षण गर्छ, ता की CTOले त्यो काम मर्ज गरोस् ।

_**म टेस्टरले आफ्नो कम्युटरमा, pull command गर्दा,  ( मास्टर branch या नि की tested-Ok-feature-branch-मर्ज-गरिएको branch मात्र pullभएको हुन्छ भन्ने गलत बुझाइ मेरो थियो ) तर पुरै भएभरका branchहरू पुल भएका हुन्छन्_ 

अब निम्न अनुसार गर्छु:

**पहिला:** `git pull` (git pull प्रत्येक दिन गर्नु पर्छ किनभने प्रत्येक अघिल्लो दिन, CTOले विभिन्न शाखाहरूबाट नयाँ परीक्षण पास भएका 'फिचर'हरू - जस्तै अपडेटेड .env  मर्ज गरेको हुनसक्छ अघिल्लो दिन)

सामान्य दैनिक काममा यो नबुझे पनि चल्छ तर कहिलेकाहीँ यो नबुझे ठुलो दुर्घटना झंझट हुनसक्छ।

`git pull` लाई डिफल्ट रूपमा git pull origin develop(<- remote) which means transfer from Master aka remote branch to Main aka local branch बुझिन्छ ।
 
**दोस्रो:** `git checkout -b "feature/ translationToEnglish"` (यहाँ म त्यस ब्रान्चमा स्विच गर्दैछु {हो, मेरो लोकल मेसिनमा भएको translationToEnglish शाखा, जहाँ translationToEng काम थपिएको छ 

त्यसपछि, म यसलाई स्थानिय रूपमा डिप्लोय गर्छु (npm run या yarn dev आदि आदि) ताकि उसको काम - translationToEng सही छ कि छैन हेर्न। मैले जाँच गर्दा काम ठिक छ भन्ने पाएपछि म यसलाई push 
गर्न चाहन्छु

**तेस्रो:** `git add --all` (यहाँ हामी git add --all गर्छौं र मात्र git add . गर्दैनौं । यसको कारण छ, जुन मैले मेरो ब्लगमा लेखेको छु)

**चौथो:** `git commit -m "feat: added static translation"`  // यदि सबै ठीक छ भने, यसले दिन्छ - WORKING TREE CLEAN

**पाचौं:** `git push`


‍‍‍‍‍‍===after being employed as tester in YI===

origin---v0.0.1 ---v0. 0.2 ---if after this coming one patch fixed makes it stable in live, then v0. 1.0

AlexWorkingOnNewFeatureBranch--v0. 0.1--v0. 0.2 of this branch

BobWorkingOnTranslationBranch-----

etc etc.

now if I pull from origin, then not only origin branch but also with AlexWorking.. Branch IE. whole tree comes to my local.

now, git pull just pulls latest v of branch I am in, which known by git status

but git fetch --all pulls latest v of all branches, which and also 'pull' should be preceeded by yarn or npm or.. depending on situation because packages dependencies might have been pushed to origin by Origin-er, which might be gitignored and we should in local also install and its info paths etc already in package.json and /or package-lock.json

I m repeating myself I know just to reinforce memory but I can't stress to self how important it is.

git stash is 'chhupake rakhna' means you neither commit n push nor u save it in ur repo publicly. it's just there for u to see, n this change won't be committed either, when u commit push this repo.

=========
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
# Chapter 4 - Permission levels of different Roles in Personal repo (Organization Repo not covered)
[Here is its official docu](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-user-account-settings/permission-levels-for-a-user-account-repository#further-reading). We hope to convey this information little easier

![Permission-different-roles](https://user-images.githubusercontent.com/11883023/168208559-2db54797-73b2-4228-bc56-fbb8713090e3.png)

---
# Chapter 5 - Developer Settings in Github
Here, we are not talking about plain GUI settings like how your github profile theme would look -dark or white? ,or what your SSH or GPG keys of your github account should be
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
[Boilerplate repos](https://github.com/sbibek086/boilerplate) are great way to speed up dev process - lot faster than w sdk ways but it can be difficult to learn.

Stuck with this Host key verification failed error

**Problems:** I was quite lost with whether github username password that I have passed in my machine is still stored in cache an thats creating trouble as i have changed github.com password ever since between.
`git config --global username.password <>` do not seem to be much of rescue tho. My intention was to so that I could feed my newly github password to my machine.

Above, I was doing the way of git clone <https://> way but SSH way is better

Solutions:
github has stopped supporting acc passwords. Now it requires token-based authentication (for eg, a personal access, OAuth, or GitHub App installation token) for all authenticated Git operations. Excerpt from:https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/
[https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token](this) says what we should do.

But when we visit this, 
`we see it says to update iCloud Keychain's github pws, WHY? 

because brave lets u store pws for online accs, NOT for localmachine pws like in this case pw stored aka cached in localmachine that for github- its assuming user is Mac-er & hence iCloud should be there by default but since for Asian windower like me, closest thing we can get is install 'iCloud For Windows' in Windows.`

and after installing iCloud App, it says to setup Windows Hello Pin and hence below screenshot 
![1645122243461](https://user-images.githubusercontent.com/11883023/168464424-50d7d58d-32b6-441d-a936-8042b294c431.jpg)

[https://support.apple.com/guide/icloud-windows/set-up-icloud-passwords-icw2babf5e03/icloud](This)seems to answer this above issue.

---
# Chapter 8- This repo itself is Template repository 
*Have I solved Chapter 7 issue with this method. I dont know for now, and I dont want to del Chapter 7 quickly. But this is Template repo itself as you can see 'Use this Template in upper belt navigation, which doesnt come for normal repo'
Just use it as template- the root layer file structure will be duplicated in your new github repo. 

---
#Chapter 9 - Environments, while you go to settings in repo. What are they?

https://youtu.be/nI6pRfH7VTc

---
#Chapter 10 - Which open source license to use when?
https://choosealicense.com/

---
#Chapter 11 -
[what to do with submitted issues in project board](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/creating-a-project-board)

---
#Chapter A about VScode continues to B,C.., AA
![image](https://user-images.githubusercontent.com/11883023/195427838-0e3d1c71-c7d7-4f85-af5b-d27de505d535.png)

