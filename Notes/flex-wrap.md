Imagine you make a parent tip and then inside that you create two child divs. You give them certain height and width. (child divs having same h and w).
Now you give display flex to the parent and align items center and justify content space around.

Now when you minimize your screen from the right side. You will see that both the child box which are between of the screen. They will start to shrink as you shrink your window or your screen.

So in order to get over this issue we give the parent div flex-wrap:wrap.

This do what?When you shrink the window, the child divs will first get close, but when the screen starts to cut them, they will not shrink, they will get one over the other on the cross axis leaving main axis in order to occupy the space available and not to shrink.

**GPT:-**

When you write:-  flex-wrap: wrap;
You're telling the flex container to allow its flex items to wrap onto multiple lines if there's not enough space on one line.