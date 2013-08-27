# Welcome to the Cloud9 Guild!

As members of the Cloud9 guild, you will be working through the challenges of TwilioQuest using the Ruby programming language and the Cloud9 browser-based IDE.  This project is pre-configured to do some interesting Twilio stuff using Ruby and the light-weight Sinatra web framework, and to be easily installable into the Cloud9 environment.

## Setting Up

Now we need to configure Cloud9 IDE to help us write Ruby code for our TwilioQuest.  The awesome part about Cloud9 is there is no software to dowload and install - we just need to sign up for an account and start writing code!

Your first step will be [signing up for a free account with Cloud9](https://c9.io/site/pricing/).  Once you have successfully signed up for an account, you must [go to your account dashboard from the home page](https://c9.io/).  On your dashboard, click "Create New Workspace":

![new workspace](http://demo.kevinwhinnery.com/upload/Dashboard_-_Cloud9-20130827-075733.png)

In the resulting popup, choose "Clone from URL":

![clone from URL](http://demo.kevinwhinnery.com/upload/Fullscreen-20130827-080032.png)

In the modal window, enter the URL for this repository, then click "Create":

![modal](http://demo.kevinwhinnery.com/upload/Dashboard_-_Cloud9-20130827-080236.png)

Cloud9 will take a few seconds to provision a new Ruby development environment for you.  During this time, you will be sent back to your dashboard, and will see your new project in the left-hand navigation with a "processing" indicator under it.  Once it is ready to use, the project name will appear in bold.  Click your new project to select it, and then click "Start Editing":

![new project](http://demo.kevinwhinnery.com/upload/Dashboard_-_Cloud9-20130827-080457.png)

This will bring you to the editor view.  This is where you will select and edit code files in your project, and where you will use the "terminal" to enter commands for Cloud9:

![Cloud9 IDE](http://demo.kevinwhinnery.com/upload/starter-cloud9_-_Cloud9-20130827-081045.png)

Now, let's configure and run your TwilioQuest app!

## Running the Application
Before we can actually run our app, we need to configure our development environment with a few pieces of information.  The first things we will need to configure are our Twilio "Account SID" and "auth token".  These are like our username and password for the Twilio API.  You can find these values [on your Twilio account dashboard](https://www.twilio.com/user/account).  If you haven't already, you will also need to [sign up for a Twilio account](https://www.twilio.com/try-twilio).

To configure your account SID, type the following command into the Terminal:

    export TWILIO_ACCOUNT_SID=your account sid

Which looks like:

![account sid](http://demo.kevinwhinnery.com/upload/starter-cloud9_-_Cloud9-20130827-081747.png)

Next, do the same for your auth token:

    export TWILIO_AUTH_TOKEN=your auth token

Which should look like:

![auth token](http://demo.kevinwhinnery.com/upload/starter-cloud9_-_Cloud9-20130827-081944.png)





## Begin Questing!
This is but your first step into a larger world.  [Return to TwilioQuest](http://quest.twilio.com) to continue your adventure.  Huzzah!
