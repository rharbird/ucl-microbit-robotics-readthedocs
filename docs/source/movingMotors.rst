*************
Moving motors
*************
-----------------
Set up the motors
-----------------
Click on the ``ServoBoard`` menu so that you can see the blocks.

.. image:: pictures/ServoBoardBlocks.png
  :scale: 50%

Now drag out the blocks that will set up the motors and place them in the ``on start`` block so that your code looks like this:

.. image:: pictures/initialiseMotor.png
  :scale: 50%

--------------------
Make the motors move
--------------------
Now we will add some code to move the motor every time that you press the button. First of all we will need to keep a counter, called a variable, in which we will store the current angle of the motor. You can do that by opening the ``Variables`` menu and choosing ``Make a Variable``, name the variable ``angle``.

.. image:: pictures/makeAVariable.png
  :scale: 50%


Now you can add the rest of the code to change the angle of the motor when the button is pressed.

.. image:: pictures/buttonMove.png
  :scale: 50%

What happens when the angle reaches 180°? Try it out.
