tinyFilter-chrome
=================

A content filter for Google Chrome.
(redirect to local html file to Autoclose blocked site windows or tabs after 10 seconds)
-----------------------------------------------------------------------------------------------------------------------
NOTE:
No difference from Hunter Paolini's script!

(ADDED killit.html)

I just got tired of closing lots of blocked tabs all day so I've added:

- A single and simple html/javascript file that users can redirect to from tinyfilter that will Autoclose blocked sites after 10 seconds.

-----------------------------------------------------------------------------------------------------------------------

The redirect lets you close immediately if you want, or to stop the countdown along with the auto-close. 

If you want to change the time after which the tab/window closes, change this line:

var counter = 10;

-----------------------------------------------------------------------------------------------------------------------
INSTALLATION:

1) Place the 'killit.html' somewhere on your computer.

example: C:/GUI/killit.html  


2) Go to tinyFilter's options >> CONTENT FILTER >> ADVANCED SETTINGS and put the file url in the field >> Redirect blocked pages to:

example: file:///C:/GUI/killit.html

3) ( optional maybe- WINDOWS only ) - If the script does not work or chrome asks permission to use javascript locally, try locating the file, and giving all permissions to user group EVERYONE in the security tab. Don't worry, this script is 100% safe and simple.

That's it!

- Aleks Berland 
http://karmakat.ca
