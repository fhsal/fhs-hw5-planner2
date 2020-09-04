# fhs-hw5-planner
Single day planner 

Summary:  this is a single day planner page which has several interactive attributes as specified in the instructions for the assignment.  Functionally, they are:

(1) Upon loading the page for the first time user is presented with a blank planner page with time-of-day on the left, calendar entry blocks in the center and a save icon/block to the right.
(2) the user can make entries into the center calendar entry blocks and then save those entries by clicking on the save icon.  Doing so shows an alert to confirm that the entry was saved. Saved entries persist even when page is reloaded as they are kept in local storage. 
(3) Visually, the current day is displayed in the header and the calendar blocks are color-coded to match the time-of-day; grey being before current time, blue being current hour and teal in the future. 

There app uses an index.html, style.css, script.js and image files.  The html page loads the header, has the eight time blocks - one for each hour, and refreshes the calendar for content and time-of-day when loaded. It also loads moment.js, jquery and the script file.   The script file contains calArray which holds the calendar entries and the functions to get time from moment.js, refresh the calendar entries, update the color of the time rows, retrieve and store the calendar entries in local storage and listen to the save button for click action by the user. 

I did not auto-generate the planner time blocks since there are only eight and the requirement was for a single day, rather than multiple.  But, that would be interesting to try and if I have time I will experiment with that. 

Comments are in the code as well. 


![img](https://github.com/fhsal/fhs-hw5-planner/blob/master/fhs-planner-screenshot.jpg)





