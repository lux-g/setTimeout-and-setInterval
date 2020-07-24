- setTimeout() will only run once, for this example I added an arrow function inside setTimeout which adds a classlist called .show which will display the image and I have the timer to 3000 which is 3 seconds. So after 3 seconds when the page is loaded the image will display and also the text will disappear.

see it here --> https://codepen.io/Nnx0/pen/rNxRZLq


- setInterval() will keep running for every second that you set it to. I am using the same example as above except i set the classlist to toggle and i created a variable for the h1 tag and also created a class to remove it and set it to toggle...the text will appear and then the image appears and text disappears....and this will keep looping forever.
- a way to get it to stop looping is by using clearInterval(). So what we can do is add a variable called count and set it to 0 then use an if statment that says if count === the length of the h1 tag innerHTML then run clearInterval(timer). So this will run 31 times which is the length of the innerHTML of the h1 tag. Next i wanted to display the length in an h2 tag with a class of .show-count. SO then i created a variable in out javascript called showCount. Underneath the clearInterval() in our if statement i will display the showCount innerHTML to the value of count using back ticks so i can display....`the total lenght is ${count}`. I set the interval time to 100th of a second so it will go quick.

see it here --> https://codepen.io/Nnx0/pen/VweREJd
