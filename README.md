# rest-android

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6630ae765ffe4f2893b13d2ac21b10ac)](https://www.codacy.com/app/jboss-outreach/rest-android?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jboss-outreach/rest-android&amp;utm_campaign=Badge_Grade)
![Travis](https://api.travis-ci.org/jboss-outreach/rest-android.svg)

This is a Android Client for testing Rest HTTP calls.

### Setup for Developers

1. Make sure you have downloaded the latest version of Android Studio. It works on Linux, Windows and Mac. Download the correct version for your OS.

2. Go to the project repository and fork it by clicking "Fork" on the top right of the page.

3. If you are working on Windows, download Git Bash for Windows to get a full Unix bash with Git functionality.

4. Clone the forked project.

5. Open the project with Android Studio.

### Configure remotes

Note: When a repository is cloned, it has a default remote called origin that points to your fork on GitHub, not the original repository it was forked from. To keep track of the original repository, you should add another remote named upstream:

1. Open terminal or git bash in your local repository and clone the repository:

`$ git clone https://github.com/YOUR_USERNAME/rest-android.git`

2. Set the upstream:

`$ git remote add upstream https://github.com/jboss-outreach/rest-android.git`

3. Run `$ git remote -v` to check the status, you should see something like the following:

``` 
origin https://github.com/YOUR_USERNAME/powerup-android.git (fetch)

origin https://github.com/YOUR_USERNAME/powerup-android.git (push)

upstream https://github.com/systers/powerup-android.git (fetch)

upstream https://github.com/systers/powerup-android.git (push) 
```

4. To update your local copy with remote changes, run the following:

`$ git fetch upstream`

`$ git merge upstream/master`

5. This will give you an exact copy of the current remote. Make sure you don't have any local changes.

### Contributing and developing a feature

1. Make sure you are in the master branch `$ git checkout master`

2. Sync your copy with `$ git pull`

3. Create a new branch with a meaningful name `$ git checkout -b branch_name`

4. Develop your feature on Android Studio and run it using the emulator or connecting your own Android device.

5. Clean your project from Android Studio > Build/Clean project.

6. Add the files you changed `$ git add file_name` (avoid using git add .)

7. Commit your changes `$ git commit -m "Message briefly explaining the feature"`

8. Keep one commit per feature. If you forgot to add changes, you can edit the previous commit `$ git commit --amend`

9. Push to your forked repository `$ git push origin branch-name`

10. Go into the Github repo and create a pull request explaining your changes.

11. If you are requested to make changes, update your commit using `$ git commit --amend`, push again and the pull request will edit automatically.

12. You need to add a [commit message](https://github.com/jboss-outreach/gci/wiki/Commit-style-guidelines.) to your commit for letting the reviewer know that changes are made.
