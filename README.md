---
title: "Fun Fact Stats"
author: Mehtap Hisarciklilar 
date: September, 2024
---
<style>
green { color: green }
red { color: red }
</style>

<red> Information sources to the organised and presented in the final version </red>

<green> Notes to myself - to be deleted in final submission</yellow>

![](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Fun Fact Stats Page

## Fonts

Text-based fonts used in this project are downloaded from [Google Fonts](http://fonts.google.com). The social media symbols used are from [Font Awesome](https://fontawesome.com/). 

The following fonts are used:  

- "Lexend" for the body and footer text. "Lexend" is chosen for the main text because a small scale study has shown that people can read and understand more easily when this font style is used. I have been using this font in documents that I produce for my students (in my professional role). 

- "Happy Monkey" for headings level 2 and higher. I found this font after a search on keywords "smile", "fun", and "happy" on Google Fonts. Since the page is aiming to the "fun", a font style that would give that effect was preferred. Like "Lexend", "Happy Monkey" is also easy to read, and it is  "fun". It also matches the font style I use for the header ("Rock Salt") 

- "Rock Salt" for heading level 1 (which is the main header of the wage). Choosing the font style for header was the most difficult. Since it serves as the logo to the page, it takes an important role. <green> I wanted .... it to read easily...  </green>

A few alternative options were consired for the header. 

### Fonts for the Header

<green> I have tried alternative logos and fonts for the header. Because the page targets students and aims to help them get familiar with Statistics *help them like statistics), I wanted the header to be fun. (Check  the notes you wrote on notebook) </green>

Below, I provide screenshots of some alternatives considered. 

- Google Fonts 

![](./media_readme/FFS_Unkempt.png)

![](./media_readme/FFS_GreatVibes.png)

![](./media_readme/FFS_GloriaHallelujah.png)

![](./media_readme/FFS_RockSalt.png)




![](./media_readme/FFS_Smile.png)

<green>
- The webpage that I used
The webpage did in fact produce something very close to what I wanted. Also, I managed to align the fonts so that they resemble (to follow) a normal distribution. But I dis not use this in the end, because the text was created as a link to an image, which was not as practical as working with fonts and text.  
</green>

## Problems faced

- (8 September 2024) I created my project repository on 7 September 2024. I worked on the `index.html`, `style.css` and  did a few commits locally, but when I attempted to push all these changes to GitHub, I realized that there was an issue with the file locations. I kept receiving error messages and failed to push my changes to GitHub. To my understanding, this happened because when I was cloning the GitHub repository initially, I did it wrong. I initially created a folder in the same name as the repository and then attempted a clone, which created a directory within the directory, both with the same name. Seeing this, I moved files around so that I do not have folder within a folder locally, but all files are located under the main folder. I think this  change in file structures created the issue. To ensure that I do not  have similar issues, I created a trial repository from scratch, did a few changes and pushes. After seeing that it works, I deleted my initial project repository from my workspace and then re-started everything again.

- In the new repository, I managed to push changes at start but then started to have problems when committing. The commits did not go through. In some cases, I could see the commit but the `index.html` file appeared as "empty" while in some other cases, the commit did not show at all! I created one new repository after another, thinking restarting from scratch would help. It did not. I think various things were going wrong at the same time, which led me to fail over and over. I think one of these problems is me, not fully understanding the terminal connection to GitHub well enough. I was wrongly assuming that the terminal connection to alternative repositories change automatiocally when I change the local folder, where I cloned these repositories. 

- Another issue is that, the changes I make on the file locally do not appear in `git status` as changes unless I save them. I am working with VS Code. It would save my changes automatically, and the setting is still set for an automatic save. But for some reason, the automatic save is not working. Because I did not realise this, I could not see any changes to commit, even when I made changes in the files. This resulted with me not being able to update my repository. I now manually save the files (rather than relying on automatic save), which allows git to see the changes and commit. 




## Steps that were followed during the creation of this website

#### 7 September 2024
- Used the CI template to create a new repository: fun-fact-stats
- Created the assets folder and then css and images folders in workspace
- Created the boilerplate using the VS Code shortcut
- Added meta tags for search engines 
- Linked the document to stylesheet
- Created the sections of the body: header, main and footer

## Things to work on before submission
- Add the favicon. 

## Things to get back to, time allowing



## Credits

- The following fonts are obtained from [Google Fonts](https://fonts.google.com). 
- The icons used for Social media links <green> and the arrow key on page xx are </green> obtianed from [Font Awesome](https://fontawesome.com/).


This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **June 18, 2024**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py` if your Python file is named `app.py`, of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

By Default, Gitpod gives you superuser security privileges. Therefore, you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you, so do not share it. If you accidentally make it public, you can create a new one with _Regenerate API Key_.

### Connecting your Mongo database

- **Connect to Mongo CLI on a IDE**
- navigate to your MongoDB Clusters Sandbox
- click **"Connect"** button
- select **"Connect with the MongoDB shell"**
- select **"I have the mongo shell installed"**
- choose **mongosh (2.0 or later)** for : **"Select your mongo shell version"**
- choose option: **"Run your connection string in your command line"**
- in the terminal, paste the copied code `mongo "mongodb+srv://<CLUSTER-NAME>.mongodb.net/<DBname>" --apiVersion 1 --username <USERNAME>`
  - replace all `<angle-bracket>` keys with your own data
- enter password _(will not echo **\*\*\*\*** on screen)_

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**June 18, 2024,** Add Mongo back into template

**June 14, 2024,** Temporarily remove Mongo until the key issue is resolved

**May 28 2024:** Fix Mongo and Links installs

**April 26 2024:** Update node version to 16

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
