We welcome anyone to contribute to this Open Source Project. For any further questions, please reach out to us on our slack channel.

# Setup for Developers

1. Download Xcode IDE for software development for iOS
2. For cloning the repo, go to https://github.com/systers/PowerUp/ and click on "Clone on Desktop". Make sure you have Github Desktop(for Mac) so that you can use the saved copy of project in that. Advisable to make a local copy of project on your system and then make changes. After testing them, copy changes to the original repo and push the changes on GitHub.
3. Include SQLite dynamic library(libsqlite3.dylib) during the link phase of the build process.
4. Install SQLite manager add-on plugin of Firefox browser. CSV files can be imported/exported directly through this.
5. Include database files(.sqlite files) into the project by dragging and dropping the file to the navigator area of the project.

# Contributing and developing a feature

1. Make sure you are in the develop branch `git checkout develop`
2. Sync your copy `git pull --rebase upstream develop`
3. Create a new branch with a meaningful name `git checkout -b branch_name`
4. Develop your feature on Xcode IDE  and run it using the simulator or connecting your own iphone.
5. Build your project in Xcode IDE by pressing Build or using shortcut Command+B.
6. Add the files you changed `git add file_name` (avoid using `git add .`)
7. Commit your changes `git commit -m "Message briefly explaining the feature"`
8. Keep one commit per feature. If you forgot to add changes, you can edit the previous commit `git commit --amend`
9. Push to your repo `git push origin branch-name`
10. Go into [the Github repo](https://github.com/systers/powerup-iOS/) and create a pull request explaining your changes
11. If you are requested to make changes, edit your commit using `git commit --amend`, push again and the pull request will edit automatically.
12.If you have more commits try squashing them into one commit.
13.git rebase -i origin/master~n master(having n number of commits).
14.Force push with command git push origin +branchname.
15. You need to follow specific pull request template and then create a descriptive pull request mentioning your changes and notifying it to your reviewer.
