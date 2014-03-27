tinyFilter-chrome
=================

A content filter for Google Chrome.
(redirect to local html file to Autoclose blocked site windows or tabs after 10 seconds)
-----------------------------------------------------------------------------------------------------------------------
NOTE:
No difference to hpaolini's script!

(ADDED killit.html)

I just got tired of closing lots of blocked tabs all day so I've added:

- A single and simple html/javascript file that users can redirect to from tinyfilter that will Autoclose blocked sites after 10 seconds.

-----------------------------------------------------------------------------------------------------------------------

The redirect lets you close immediately if you want, or to stop the countdown and close. 

If you want to change the time after which the tab/window closes, change this line:

var counter = 10;

-----------------------------------------------------------------------------------------------------------------------
INSTALLATION:

1. Place the 'killit.html' somewhere on your computer.

example: C:/GUI/killit.html  

2. Go to tinyFilter's options >> CONTENT FILTER >> ADVANCED SETTINGS and put the file url in the field >> Redirect blocked pages to: 

example: file:///C:/GUI/killit.html

That's it!
