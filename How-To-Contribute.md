We welcome anyone to contribute to this Open Source Project. For any further questions, please reach out to us on our slack channel.

# Setup for Developers

1. Download Xcode IDE for software development for iOS
2. For cloning the repo, go to https://github.com/systers/PowerUp/ and click on "Clone on Desktop". Make sure you have Github Desktop(for Mac) so that you can use the saved copy of project in that. Advisable to make a local copy of project on your system and then make changes. After testing them, copy changes to the original repo and push the changes on GitHub.
3. Include SQLite dynamic library(libsqlite3.dylib) during the link phase of the build process.
4. Install SQLite manager add-on plugin of Firefox browser. CSV files can be imported/exported directly through this.
5. Include database files(.sqlite files) into the project by dragging and dropping the file to the navigator area of the project.

# Contributing and developing a feature

1. Create an issue and/or assign yourself to an issue on Github
2. Make sure you are in the master branch git checkout master
3. Sync your copy git pull
4. Create a new branch with a meaningful name git checkout -b branch_name
5. Develop your feature on Android Studio and run it using the emulator or connecting your own Android device
6. Clean your project from Android Studio Build/Clean project
7. Add the files you changed git add file_name (avoid using git add .)
8. Commit your changes git commit -m "Message briefly explaining the feature"
9. Keep one commit per feature. If you forgot to add changes, you can edit the previous commit git commit --amend
10. Push to your repo git push origin branch-name
11. Go into the Github repo and create a pull request explaining your changes
12. If you are requested to make changes, edit your commit using git commit --amend, push again and the pull request will edit automatically
13. You will need to add a message on the pull request notifying your changes to your reviewer