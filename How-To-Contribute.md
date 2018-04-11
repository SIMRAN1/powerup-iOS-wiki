# Welcome to PowerUp iOS Project.
* You can subscribe to our [systers-dev](http://systers.org/mailman/listinfo/systers-dev) mailing list and shoot an introductory email.
* You can join our [slack channel](http://systers.io/slack-systers-opensource/) and navigate to #powerup channel

## Contribution Guidelines
* Pick an open issue from the [issue list](https://github.com/systers/powerup-iOS/issues), claim it in the comments,after approval fix the issue and send us a pull request.
* Create a new issue,a community member will get back to you and once approved send the PR for the same
* Please go through our issue list first(open as well as closed) and make sure the issues you are reporting  do not replicate the issues already reported. If you have issues on multiple pages, report them separately. Do not combine them into a single issue.
* All the PR’s need to be sent to the develop branch

## Avoid doing the following mistakes
1. Fix a new issue and submit a PR without reporting and getting it approved at first.
2. Fix an issue assigned to somebody else and submit a PR before the assignee does.
3. Report issues which are previously reported by others. (Please check the closed issues too before you report an issue).
4. Suggest completely new developments in the issue list. (Please use the mailing list/slack channel for this kind of suggestions. Use issue list to suggest bugs/features in the already implemented sections.)

## Setup for Developers
1. Make sure you have Xcode IDE downloaded on your machine for software development for iOS.
2. Fork the systers project. Go to [Powerup-iOS](https://github.com/systers/powerup-iOS) and click on Fork in the top right corner. Fork the repo on your Github id. Make sure that you don’t have any existing repo with the same name in your profile else there will be conflicts.
3. Make sure you have installed [Github Desktop(for Mac)](https://desktop.github.com/).
4. Open Github Desktop, click on Clone Repository in File Menu. Clone the forked repo to get a local copy on your system.
5.Fetch the latest version of code from branch "develop".


## Contributing and developing a feature
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
