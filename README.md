# Rest-Android

![Travis](https://api.travis-ci.org/jboss-outreach/rest-android.svg)
[![Gitter chat](https://badges.gitter.im/gitterHQ/services.png)](https://gitter.im/jboss-outreach)

This is a Android Client for testing Rest HTTP calls.

## Contents
* [Setting up the project](#setup)
* [Working on the App](#work)
* [Contributing](#contributing)
* [Additional Learning](#additional)


## <a id = "setup"></a> Setting Up the project

1. Download [Java 8 JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html) for your Operating System!
2. Make sure you have declared the `JAVA_HOME` environment variable to the directory where JDK was installed. 
3. Download and install [Android Studio](https://developer.android.com/studio/index.html), an IDE for android application development.
4. You will also need to download the Android SDK from the IDE itself.
5. Fork the repository by clicking on the *Fork* icon at the top right corner of this page.

![](https://steemit-production-imageproxy-upload.s3.amazonaws.com/DQmZHFQ5NvaKXG7rrLoYzCwbHyEyCjhbZjY3uP5tMvy2H84)

6. Clone the repository to your local machine by running the following commands on git:

            `git clone https://github.com/[YOUR-USERNAME]/rest-android.git`

 If you need help, refer [Forking and Cloning in git](https://help.github.com/articles/fork-a-repo/)
 
### Configure remotes

Note: When a repository is cloned, it has a default remote called origin that points to your fork on GitHub, not the original repository it was forked from. To keep track of the original repository, you should add another remote named upstream:

1. Set the upstream:

`$ git remote add upstream https://github.com/jboss-outreach/rest-android.git`

2. Run `$ git remote -v` to check the status, you should see something like the following:

``` 
origin https://github.com/YOUR_USERNAME/rest-android.git (fetch)

origin https://github.com/YOUR_USERNAME/rest-android.git (push)

upstream https://github.com/jboss-outreach/rest-android.git (fetch)

upstream https://github.com/jboss-outreach/rest-android.git (push) 
```

3. To update your local copy with remote changes, run the following:

`$ git fetch upstream`

`$ git merge upstream/master`

4. This will give you an exact copy of the current remote. Make sure you don't have any local changes. 

## <a id="work"></a>Working on the app:
* Open android studio.
* Import your recently cloned IDE into android studio.

### Running the Application
***Via your own android smartphone.***

   - Enable [USB Debugging](https://www.howtogeek.com/129728/how-to-access-the-developer-options-menu-and-enable-usb-debugging-on-android-4.2/) on your phone.    
   - Click **Run** on the Android Studio tool bar, or **Shift + F10** to [run the app](https://developer.android.com/studio/run/device.html).

***By running a virtual device.***
   - Setup a [Android Virtual Device](https://developer.android.com/studio/run/managing-avds.html) in the IDE. 
   - Then running the application by clicking on **Run** on the Android Studio tool bar, or **Shift + F10** and then choose the newly created virtual device to run the app.
	 
	 
## <a id = "contributing"> </a>Contributing to the project and developing a feature

* Make your intended changes to the working directory.
* Make sure you are in the master branch `$ git checkout master`
* Sync your copy with `$ git pull`
* Create a new branch with a meaningful name `$ git checkout -b branch_name
* Develop your feature on Android Studio and run it using the emulator or connecting your own Android device.
* Clean your project from Android Studio > Build/Clean project.
* Finalize your changes made and then you need to make a [**pull request**](#pull) the changes to working directory.

#### <a id = "push"></a> Pushing your changes 

1. Add the files you changed `$ git add file_name` (avoid using git add .)

2. Commit your changes `$ git commit -m "Message briefly explaining the feature"`

3. Keep one commit per feature. If you forgot to add changes, you can edit the previous commit `$ git commit --amend`

4. Push to your forked repository `$ git push origin branch-name`

#### <a id = "pull"> </a> Making a Pull Request

1. Go into the Github repository and create a pull request by clicking on **"New Pull Request"** Do explain your changes, write a very conscise but informative pull request message. Remember to use your words wisely!

2. If you are requested to make changes, update your commit using `$ git commit --amend`, push again and the pull request will edit automatically.


## <a id = "additional"> </a> Additional Learning

* [Understanding the Github Flow](https://guides.github.com/introduction/flow)
* [Getting started with Git](https://git-scm.com/book/en/v1/Getting-Started)
* [Practice git and have fun!](https://try.github.io)
* [Getting Started with Android Studio](https://developer.android.com/training/index.html)
* [Android Studio Documentation](https://developer.android.com/guide/index.html)
* [Need further help? Chat with us!](https://gitter.im/jboss-outreach/gci)
