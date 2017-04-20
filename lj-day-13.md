# Learning Journal Day 13  

Today was a demo of how our instructor would go about solving the weeks project problem, and it was extremely helpful.  It's crazy how easy he made it seem haha.  But it's understandable how much us students, or just to speak for myself, have struggled.  Like Duncan said when was the last time something was done once and you just straight memorized how to do it....never hah!   

The rest of the day was about localstorage and sessionstorage.  We had to modify the project we have been working on so that the data rendered in the chart would be saved and added to each new rendition/iteration/load of the webpage.  My partner and I honestly made it waaaayyyy more complicated than it needed to be.  Our instructor came over and pushed us in the right direction.  Come to find out we already had everything set up that we needed, it was just a matter of adding a few lines of code to save the array, and just make that saved array the starting point every time the page was loaded.  

One problem we did run into was if localstorage is cleared it will throw a 'null' error.  After a few minutes of scratching our heads we realized of course it's throwing an error.  We cleared the storage and it's looking for saved data.  So we just wrapped the array of all our instances in an if statement and boooya!
