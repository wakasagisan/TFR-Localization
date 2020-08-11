# TFR-Localization  [![Join our Discord!](https://img.shields.io/discord/449966345665249290.svg?color=blue&label=Discord&logo=discord&style=flat-square)](https://discord.gg/97Mj6vK) [![Support the devs!](https://img.shields.io/badge/Patreon-Support-orange.svg?style=flat-square)](https://www.patreon.com/TeamMoeg)

Localization Port for Terra Firma Rescue Modpack. All contributers will be on the [SupporterList](https://github.com/TerraFirmaRescue/TerraFirma-Rescue-Modpack/blob/master/supporterlist.txt). 

1. [CURSEFORGE](https://www.curseforge.com/minecraft/modpacks/terrafirma-rescue)
2. [MCBBS](https://www.mcbbs.net/thread-977365-1-1.html)
3. [OFFICIAL WIKI](http://www.terrafirmarescue.com:11004/)
4. [SOURCE](https://github.com/TerraFirmaRescue/TerraFirma-Rescue-Modpack)
5. [ISSUES](https://github.com/TerraFirmaRescue/TerraFirma-Rescue-Modpack/issues)
6. [LICENSE](https://github.com/TerraFirmaRescue/TerraFirma-Rescue-Modpack/blob/master/LICENSE)

## How to Contribute

The primary localization target are the quests in the modpack. Currently, Chinese is fully supported and English is partly supported by Machine Translation through my script. 

### 1. Understand to localization

BetterQuesting localization is done by creating a .lang file that contains mappings of translationKeys and translated result. Example of a mapping in the en_US.lang file is:

tfr.quest0.name=The Stone Age

Each mapping should start with a different line and the translated results should not contain '=', '/', or some vague letters that may cause complie issues.

The unlocalized keys should either be 

tfr.quest<non-negative integer>.name or tfr.line<non-negative integer>.name

Check for them in DefaultQuests_Unlocalized.json

### 2. How to edit

Change the current translated results of the mappings that you think have grammatical mistakes or unclear meaning. Or you can create another language file of your own language following the format I mentioned above.

Do not change DefaultQuests.json or DefaultQuests_Unlocalized.json , they are here just for reference. 

### 3. How to submit your edit

Before you can do anything, you need to be able to make changes to the code. Follow the steps below to clone this test repo and create a new branch.


Go to this GitHub repo. If you haven't setup Git on your computer yet, follow [these instructions](https://help.github.com/articles/set-up-git) first.

Click the Fork button on the upper right-hand corner. This will save the repo to your GitHub account


You now have a copy of the repo you just forked, available in your GitHub account

Clone the repo locally by running git clone https://github.com/TerraFirmaRescue/TFR-Localization.git in your terminal

Open this repo in your terminal and run the following command to create a new branch: git checkout -b add-your-name


Tadaa! You're now working on a new branch, on a repo that you can commit to

Note: If you're new to the GitHub workflow, you may find [this guide](https://guides.github.com/introduction/flow/index.html) useful.

Now make your changes on the language files. 

Commit them by first use

git add <filename>

Then use 

git commit -m "Commit Message(I suggest you write what you have changed, such as 'Added Japanese Localization file')"

Now push these changes to the repo by running git push origin add-your-name. You're now ready to send your pull request!


Here's how you can open your first pull request:

Go to the shared repo on GitHub and click on the green compare & pull request button

Click on 'create pull request'


Congrats on the successful pull request, and you just have to wait for the team to check and merge your changes into the master branch.

Normally, the changes will be added in the following major update of the modpack. 
