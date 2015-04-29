# Introduction #

dvd-slideshow-editor is a wxPython-based GUI editor for [dvd-slideshow](http://dvd-slideshow.sourceforge.net/wiki/Main_Page) script. dvd-slideshow is a cool program, very flexible and produces high-quality slideshow video. However, it is text-based, and so it is painful to edit and make sure that your crop or kenburns effect is just right.

This program allows you to see visually where you are cropping or how the kenburns effect are going to look like in the final product.

# Screenshots #

![http://dvd-slideshow-editor.googlecode.com/files/shot1.jpg](http://dvd-slideshow-editor.googlecode.com/files/shot1.jpg)

![http://dvd-slideshow-editor.googlecode.com/files/shot2.jpg](http://dvd-slideshow-editor.googlecode.com/files/shot2.jpg)

![http://dvd-slideshow-editor.googlecode.com/files/shot3.jpg](http://dvd-slideshow-editor.googlecode.com/files/shot3.jpg)

# Details #

The program window is divided into 2:
  * Left pane contains the raw script, but images are parsed out and displayed
  * Right pane contains the preview of the picture with effect's bounding box

You can edit the script directly on the left pane and type it out, or using the right pane window by moving/resizing the effect's bounding box.

On the left pane, you can select multiple lines, and right-click to:
  * add random kenburns effect on all the selected lines that contain images that does not have any effect yet
  * add crop effect on all the selected lines that contain images that does not have any effect yet
  * remove all effect from the selected lines that contain images
  * preview selected lines
  * launch a text editor to edit the script directly