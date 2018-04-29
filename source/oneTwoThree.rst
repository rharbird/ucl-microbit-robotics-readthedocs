****************
Forward and Back
****************
Well done, you have got the motor moving and you can see that it moves from 0° to 180° as you press the button. Now we need to change the code so that the motor moves without human intervention so that our caterpillar can crawl.
-----------------------
New code
-----------------------
We are going to move the code that we have in the ``on button A pressed`` loop into the ``forever`` loop. Any code that you put in the ``forever`` loop will keep repeating over and over, as its name suggests. Modify your code using these two steps.

Step 1:
^^^^^^
Move the code to the ``forever`` loop and delete the ``on button A pressed`` loop. Your code should now look like this:

.. image:: pictures/forever.png
  :scale: 60%


Step 2:
^^^^^^
Now add a pause of 20 milliseconds at the end of the loop to give the motor a chance to move in time with the instructions it receives from the micro:bit.


.. image:: pictures/pause.png
  :scale: 60%

Step 3:
^^^^^^

Try it out. Upload your code to the micro:bit. Did it work? Keep experimenting until you are satisfied with how it is working.
