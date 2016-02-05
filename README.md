What
----

JWPlayer Input Filter is a small Drupal 7 input filter that aids in embedding a video into the JWPlayer and thumbnail inside the WYSIWYG editor

How
----
Install the module and enable it. Be sure to give the input filter your JW key and path to the jwplayer.js file by
configuring the input filter.  Inside your WYSIWYG do something like this in a node's body field.


Preferred Style.

[JW:/sites/default/files/Intro.mp4|/sites/default/files/introvideostill.jpg|{"width":600,"height":338,"mediaid":"xxbbaa"}]


Preferred with radio

[JW:/sites/default/files/Intro.mp4|/sites/default/files/introvideostill.jpg|{"width":"98%","ratio":"16:9"}]


Old style

[JW:/sites/default/files/Intro.mp4|/sites/default/files/introvideostill.jpg|600x338]

Warranty, Gotchas and Assumptions
-----------------------
There is no warranty made here. Assumes that you have the JW Player installed on your instance of D7. You have to
go into the input filter's settings to let Drupal know where your JW Player instance lives.
