# Day 0: Set up guide
Let me start by recognizing that this isn't going to be fun.\
All of these tools can be a pain to set up and occasionally lead to confusion.\
Put aside your brilliant, inquisitive student minds and follow the instructions, ***one-by-one***.\
This will all become clear soon enough, I promise.

This will walk through the three tools we'll be using
1. GitHub
2. git
3. IntelliJ

### IntelliJ
:question:&nbsp; What is IntelliJ?\
:exclamation:&nbsp; A code editor, sorta like Microsoft Word, but cooler.
###### Sign up for an educational license
- [x] Fill out [this form](https://www.jetbrains.com/shop/eform/students) 
  - Ignore the fact that it says "University email address" you're cool like that
  - Use your Madeira email address
  - Check your email for a message from JetBrains (the folks that make IntelliJ) & follow those instructions
- [x] Download IntelliJ Ultimate Edition

### GitHub
:question:&nbsp; What is GitHub?\
:exclamation:&nbsp; A place to share your code and collaborate with others.
###### Sign up for an account
- [x] Navigate to [GitHub](https://github.com)
- [x] Sign up
  - Make your username firstIntialLastName_Madeira à la: jDoe_Madeira
  - Make sure to use your school email address
  
### `git`
:question:&nbsp; What is `git`?\
:exclamation:&nbsp; A piece of software that allows you to keep track of changes to files (like Google Docs, sort of)\
If you have a Mac, follow below. If you have Windows, skip to the Windows section.

----
:pushpin:&nbsp; If you see `this text` it means enter the command into Terminal (Mac users) or Command Prompt (Windows users). Watch [this]() for what Terminal / Command Prompt is.

-----

###### Mac installation instructions
- [x] See if you have it first
  - `git --version`
  - If you get a response like `git version #.##` skip this section
- [x] Download Homebrew
  - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
    - Answer yes or hit enter when prompted
- [x] Once above finished, `brew install git`
- [x] `git --version`
  - If you get a response like `git version #.##` you're golden&nbsp;:trophy:

###### Windows installation instructions
- [x] See if you have it first
  -  `git --version`
  - If you get a response like `git version #.##` skip this section
- [x] Navigate [here](https://git-scm.com/download/win) and the download will start
- [x]  `git --version`
  - If you get a response like `git version #.##` you're golden&nbsp;:trophy:

### :hand:&nbsp;Stop.
Watch [this](https://www.youtube.com/watch?v=5DqTuWve9t8)


### :link:&nbsp;: Connecting `git` to GitHub
Now we'll connect the git software we just downloaded to the website, GitHub, so that you can share your code.
###### Creating your first repository
- [x] Login to your new GitHub account and navigate to the "My repositories" section under your profile
- [x] Create a new repository named "Mod1Labs" 
  - Make sure it's capitalized the same way as above
  - **Do not** initialize your repository with a README.md
- [x] Keep this tab open, we'll come back here
###### Creating your first IntelliJ project
- [x] Watch [this](https://themadeiraschool.sharepoint.com/sites/IntrotoCS/Shared%20Documents/General/Videos/newIntelliJProject.mov) video & follow the same steps
###### Connecting your IntelliJ project to GitHub
- [x] Mac: `cd Desktop/IntroToCS/Mod1Labs` Windows: `cd Desktop\IntroToCS\Mod1Labs`
- [x] `git init`
- [x] `git add *`
- [x] `git commit -m "my first commit"`
- [x] `git remote add https://github.com/YOUR_GITHUB_USERNAME/Mod1Labs.git`
  - The bit that reads YOUR_GITHUB_USERNAME should be replaced with your username
- [x] Then enter: `git push -u origin master`

:massage:&nbsp;Probably time for [this](https://www.youtube.com/watch?v=5DqTuWve9t8) again


