# Introduction #

This Tutorial will walk you through the basics of editing and running a Processing Project in Eclipse.  It will show you the basics of opening up your project, editing it, and running it.


# Details #

You will see a folder on the left window of your screen with the name of project.  This window is called the "**Package Explorer**."  It will contain list all of your eclipse projects in your current _workspace_ (for more detailed explaination of "workspaces" and packages see advanced documentation: TODO).  Proclipsing has created an Eclipse project for you, with Processing _jar_ files, _Native Libraries_, a _package_ for containing your code, and skeleton _Java Object_ for writing Processing Code in.

<img src='http://12.media.tumblr.com/tumblr_kr234uMeGp1qzqc80o1_500.png' />

  * open the folder with your project name
  * open the folder with name "**src**."  This folder will contain all of the packages for your project.
  * open the the package with a similar name to your project.
  * double click the Java file (in this case "MyProcessingProject.java").

Notice that the file is opened in the center window of Eclipse.  This is called the "Java Editor" window.  Proclipsing has prepopulated this class with a "setup" and "draw" functions.  You can write standard Processing functions in these.

To run your code:

  * **Right-click** (or cntrl-click on an Apple), on the class you want to run.
  * Scroll down in the menu to where it says "**Run as...**"
  * Select "**Java Applet**" or "**Java Application**," depending on whether your project type

You will see a window open up with your project running in it.

To run this project again, click the green **play** button at the top.