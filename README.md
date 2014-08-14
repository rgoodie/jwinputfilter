JWPlayer Input Filter
=============

A small Drupal 7 input filter that aids in embedding a video into the JWPlayer and thunbnail inside the WYSIWYG editor

Usage
=====

Inside your WYSIWYG, after turning on and configuring the filter, do something like this. 

`[JW:/sites/default/files/videos/myvideo.mp4|/sites/default/files/images/MyThumbnail.jpg]`

Also be sure to give the input filter your JW key and path to the jwplayer.js file. 

Warranty, Gotchas and Assumptions
-----------------------
There is no warranty made here. Assumes that you have the JW Player installed on your instance of D7. You have to go into the input filter's settings to let Drupal know where your JW Player instance lives. 
