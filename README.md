# HacksuHacktoberfest
Make 5 pull requests in this repo to get a free shirt!

# Steps
Before you do anything, you will need to sign up for Hacktoberfest here: https://hacktoberfest.digitalocean.com/

To get started on making pull requests, click that fork button on the top right to create your own version of this repo.\

Next, you're going to be redirected to your own version of the repo and you're going to want to click on that green clone button and copy the link provided.\

Open up Powershell if you're a Windows user or open Terminal if you're a Mac user.\

In Powershell or Terminal, go to where you want to save your repo on your local machine and type the command `git clone [your repo url]` then `cd HacksuHacktoberfest` to get into that file.\

To make a connection back to the original repo, run the command `git remote add upstream https://github.com/hacksu/HacksuHacktoberfest.git` and check if it's properly there by running `git remote -v`\

Now that you can communicate with the original repo, create your own branch by typing `git checkout -b [your branch name]`. This command will make your branch and automatically move you there too. You can check all branches by running `git branch`!\

Last thing you need to do is run `git push upstream [your new branch name]` which creates new branch on the original repo that you can now make changes to.

Now for the fun stuff! Open up a text editor and repeat these steps 5 times:
 * Edit something on the html page, anything, even 1 character!!
 * Run `git add *` - the `*` character means you want to add all files, you can change this to only add certain files
 * Run `git commit -m "your own message"` - try to tell other people what you did in this commit message.
 * Run `git push` - this pushes all of your changes to GitHub! The first time you run this, it will prompt you to run another command, type it in exactly how it wants you to.
 * Go to https://github.com/hacksu/HacksuHacktoberfest/pulls and click on that `New Pull Request` button!
   * Specify the base fork to be `hacksu/HacksuHacktoberfest`, the branch `[Your branch name]`, the head fork be your own fork, and the branch `[Your branch name]`
   * Hit create pull request and you're all done!
 * Wait for us to approve your pull request and repeat!!

Once you're done making 5 pull requests, you can delete your branch by running `git checkout master` and `git branch -d [your branch name]`\
Then to clean up the original repo, run `git push upstream :[your branch name]` and on your repo `git push origin :[your branch name]`\
You're all set!! Wait for an email from GitHub about your shirt and enjoy another free shirt to add to your collection!
