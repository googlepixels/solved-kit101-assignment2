Download Link: https://assignmentchef.com/product/solved-kit101-assignment2
<br>
The purpose of this assignment is to:

Give you experience at:

Reading Java code and identifying the essential components – instance variables, method declarations, local variables

Reading and writing Java code that uses the following concepts:

solving problems by using nesting, looping and branching constructs solving problems by sending messages to objects of suitable classes declaring new classes (declaring methods and instance variables) parameter passing to methods use of return values from methods  Writing appropriate documentation

<strong>The programming task — Find your dogs!</strong>

You have two Yorkshire Terriers, let’s call them Bistol and Poo (to protect their identities). They’re on

https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_1…SessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021&amp;d2l_body_type=3

the run from Deputy Prime-Minister and HiFi store magnate Jarnaby Boyce, and you’ve got to find them before he does!

You will search the states of Australia for your beloved doggies. When you see them you’ll try to catch them so that they’re safe. To do this you have to lure them towards you. But they’re playful and will only come the third time you call. If, however, you encounter Jarnaby while looking for them: you’re in trouble buddy! You’ll be so hurt by his rebuke that you will be dazed for two moves — run into him again while you’re dazed and go home Yankee, go home! You can call the dogs while dazed but you will stay dazed; you must move twice to clear your head. But dazed or not, you can only erroneously call out to the puppies three times — if you shout in the wrong direction three times, you will be found by Jarnaby and deported. And who will look after the puppies then Captain? Game over. Indeed.

When you are not dazed it is possible for you to have some idea of your location, the states around you, and the location of your dogs (because their continuous annoying yapping gives their location away).

<a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">The on-line version of this document has a link to some sample output of both a sta</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">g</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">e 2 and sta</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">g</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">e 4 implementation of this </a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">g</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">ame.</a>

The completed implementation will consist of three files, <em>only one</em> of which must be written by you.

These files are:

<u> </u><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/AssigTwo216.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">AssigTwo216.</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/AssigTwo216.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">j</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/AssigTwo216.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">ava</a> This is the driver program (with a main() method). The code of this is complete and it MUST NOT be changed (unless <em>Stage 4</em> is reached). The code in this file is very simple — it declares and instantiates an object of the PirateDog class and calls its play() method. (The on-line version of this document has a link to the code.)

<u> </u><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/R2JCD2.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">R2JCD2.</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/R2JCD2.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">j</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/R2JCD2.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">ava</a> This is a library class and this file contains resources that you are to use in developing your implementation of the task. The code is complete and MUST NOT be changed.

(The on-line version of this document has a link to the code.)

<u> </u><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/PirateDog.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">PirateDog.</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/PirateDog.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">j</a><a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/PirateDog.java?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">ava</a> This is an organiser class and is the file that you are to write; the on-line version of this document has a link to a ‘skeleton’ version of the code — use this as the starting point for your program.

There will be no main() method in the class, it will contain methods that organise the task.

This will include all the interactions with the user.

You should make sure that you do the following:

Create and use object(s) of the R2JCD2 class. You will LOSE MARKS if you write code in PirateDog.java that duplicates things that could be done using methods of the

R2JCD2 class.

Use the trace() method (provided in the skeleton) to include tracing messages in your program — switch the messages off before submission.

Use separate methods to implement the separate activities within the task. Use instance variables to store data that is used or changed by more than one method and/or needs to persist for the life of the object.

Use local variables to store the data that is used by just one method.

This program (like all programs) should be developed in stages, with each stage fully implemented and tested before the next stage is attempted. To provide you with some guidance about this, the detailed specification below is divided into four stages, you should aim to submit a program that implements at least stage 1.

A program that correctly implements stage 1 and provides all the required external documentation, both to a high standard will be able to score a maximum of 48 of the 60 marks. This is 80% — a high distinction. If you have done all of this in plenty of time and want to try for an even higher mark, then you should begin to implement stage 2, and if you have time stages 3 and 4<em>. Note that you will receive NO marks for your attempts to implement later stages if the marker finds that your implementation of earlier stages does not function as specified in this document.</em>

VERY IMPORTANT: You <em>must</em> state in the header comments of your source code which stage of implementation your program has reached. If you do not do this then the marker may assume that you have only implemented stage 1 and you may not receive any marks for implementation of any other stages.

<h2>Details – Stage 1</h2>

(Note: even within stage 1, you should plan, implement, and test your program in sub-stages. It is part of your task to work these sub-stages out yourself.)

Write code in PirateDog.java to do the following:

“Housekeeping” tasks — PirateDog()

Instantiate the R2JCD2 and Scanner classes.

Switch on the debugging/tracing messages in the PirateDog and R2JCD2 classes. (Switch them off before you submit your program for assessment.)

Introduction — explain()

Provide the user with a general explanation of the game.

Play the game — the user is prompted to make “moves” until the game is over.

The game will end when any one of the following happens:

You try to move to the state occupied by Jarnaby while you are dazed.

You call the dogs when they’re not there three times.

You call the dogs successfully three times.

You choose to quit the game.

Before each move you are provided with information. If you are dazed then you are only reminded that you need to find the dogs, otherwise you are told:

Your current location in Australia.

The numbers of the four connecting states.

The number of times you have called the dogs both successfully and unsuccessfully. Any available information about the location of the dogs — i.e. whether you can hear their barking.

Any available information about the location of Jarnaby — i.e. whether music from JB’s HiFi can be heard.

You will be asked what you want to do for this turn. The options are:

Fly into another state (by number).

You will be asked to enter the number of the state you want to fly into.

If the state is not connected to your current location you will not be able to fly, and should be told so.

Otherwise if the state is connected to you current location, you will enter the new state and if the new state doesn’t contain the dogs or Jarnaby the game will continue (with you becoming slightly less dazed if you were dazed) if the new state does contain Jarnaby and you were already dazed then the game is over, otherwise you become dazed and Jarnaby leaves to give a press conference.

if the new state does contain the dogs then they will run away.

Call into another state (by number).

You will be asked to enter the number of the state you want to shout into.

If the state is not connected to your current location, you will be told this. If the state is connected and contains the dogs then it is noted that they have been called and the game continues. When this occurs for the third time, the dogs come to you and the game ends, otherwise the dogs run away.  If the state is connected but doesn’t contain the dogs then it is noted that you’ve drawn attention to yourself unnecessarily and the game continues. When this occurs three times, the Australian Federal Police will arrest you and deport you and the game ends.

Reset the Game.

If this option is chosen then many game parameters are reset:

your position is changed.

the dogs’ position is changed. Jarnaby’s position is changed. your head is cleared (i.e. you are not dazed) the shouting tallies are reset to 0.

Quit the game.

The game will end.

<h2>Details – Stage 2</h2>

Remember

You should only consider implementing this if you have completed and tested stage 1 and have time to spare.

You must state in the header comments of your source code that you have implemented stage 2.

Extra functionality at this stage:

Before playing, you are asked whether or not you want to play, if not, there is no game played.

After each game is over, you are asked whether you want to play again.

The numbers of the states that the user enters should also be remembered (to a maximum of 20 moves and then the most recent 20 should be remembered). These values (in chronological order) should be displayed at the end of the game. See <a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/ass2sample.pdf?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">sample output</a> for more information. <strong>Details – Stage 3</strong>

Remember

You should only consider implementing this if you have completed and tested stage 2 and have time to spare. There is a lot of extra work in this Stage for very few marks.

You must state in the header comments of your source code that you have implemented stage 3.

Extra functionality at this stage

Design and build a graphical user interface (GUI) for the <em>output</em> of the program (display of messages after each move, and the final messages). The input (including prompts to the user) will be from the console (using methods of the Scanner class) (as in stages 1 and 2).

NOTE: You are <em>not</em> expected to, and should <em>not</em> attempt to write your own code to open, position, arrange, or close the GUI.

Write extra code in PirateDog.java (which should now extend QuickGUI)

“Housekeeping” tasks — PirateDog()

Create the GUI (consisting of Fly, Call, Reset, and Quit buttons, and (perhaps) a read-only text field and two ordinary text fields).

Show the information to the player and present them with their choices — paintComponent() Add the functionality of displaying the user’s status on the GUI within a new method:

paintComponent().

Place calls to repaint() within the program.

You may find some Tutorials helpful.

<h2>Details – Stage 4</h2>

Remember

You should only consider implementing this if you have completed and tested stage 3 and have time to spare. There is a huge amount of extra work in this Stage for very few marks.

You must state in the header comments of your source code that you have implemented stage 4.

Extra functionality at this stage

Make the graphical user interface interactive, that is all interaction between the user and the program should be through the GUI.

NOTE: You are <em>not</em> expected to, and should <em>not</em> attempt to write your own code to open, position, arrange, or close the GUI.

Write code in PirateDog.java (which should now also implement ActionListener) to do the following:

“Housekeeping” tasks — PirateDog()

Ensure ActionEvents will be listened for by the buttons and a text field.

Comment out the call to play() in the AssigTwo216.java file.

Manage the pressing of buttons and typing in the text field — actionPerformed()

If the user has elected to fly, shout, reset, or quit

Manage this appropriately (similar to the play() method).

repaint() the screen.

You may find some Tutorials helpful.

<h1>Planning and Documentation</h1>

The first thing that you need to do is to understand what uses can be made of objects of the R2JCD2 class. To do this:

Read the code carefully, making sure that you can identify instance variables

methods – read the header comments and the code of these and work out what they do (fill in a table like the one shown below as you do this).

Write a driver program to instantiate an object of the R2JCD2 class and call its methods (to check that they behave the way that you think they do).

Complete a table showing what you have deduced about the R2JCD2 class. This table must:

Have the columns shown below.

Have a row for each method in the R2JCD2 class.

Be submitted for assessment.

<a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/R2JCD2Table.doc?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">The on-line version of this document has a link to a word document that can be used for this table.</a>

<table width="730">

 <tbody>

  <tr>

   <td width="122"><strong>method</strong><strong>identifier</strong></td>

   <td width="84"><strong>return type</strong></td>

   <td width="105"><strong>parameters</strong></td>

   <td width="248"><strong>instance variables used by this method</strong></td>

   <td width="172"><strong>what does the method do?</strong></td>

  </tr>

  <tr>

   <td width="122"> </td>

   <td width="84"> </td>

   <td width="105"> </td>

   <td width="248"> </td>

   <td width="172"> </td>

  </tr>

  <tr>

   <td width="122"> </td>

   <td width="84"> </td>

   <td width="105"> </td>

   <td width="248"> </td>

   <td width="172"> </td>

  </tr>

 </tbody>

</table>

Plan how to write code to “organise” the “PirateDog” activity (using object(s) of the R2JCD2 class) Work out the subtasks that will be needed (each of these should be implemented as a method).

Work out the data that will need to be “shared” by more than one method. These will usually be implemented with instance variables.

For each method work out:

the data it will need to have passed in (parameters) the data it will need to pass out (return value) the algorithm for doing the subtask

Implement each step after you have planned it — a little bit at a time — compile and test the implementation as you go.

Complete (as you go) a table documenting your plan and progress. This table must:

Have the columns shown below.

Have a row for each instance variable in your PirateDog class.

Have a row for each method in your PirateDog class.

Be submitted for assessment.

<a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/PirateDogTable.doc?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">The on-line version of this document has a link to a word document that can be used for</a>

<a href="https://mylo.utas.edu.au/content/enforced/169021-AW_EAI_16S2_12577_1_0_0_1_1/Assessment/assignment02/PirateDogTable.doc?_&amp;d2lSessionVal=Eh1HhJ5Ci7WInD9orSTzKEvrp&amp;ou=169021">this table.</a>

<table width="730">

 <tbody>

  <tr>

   <td colspan="4" width="360"><strong>Instance variables</strong></td>

   <td colspan="3" width="371"> </td>

  </tr>

  <tr>

   <td width="86"><strong>identifier</strong></td>

   <td width="65"><strong>type</strong></td>

   <td colspan="2" width="209"><strong>What is this used for?</strong></td>

   <td colspan="3" width="371"><strong>Which methods used this variable?</strong></td>

  </tr>

  <tr>

   <td width="86"> </td>

   <td width="65"> </td>

   <td colspan="2" width="209"> </td>

   <td colspan="3" width="371"> </td>

  </tr>

  <tr>

   <td width="86"> </td>

   <td width="65"> </td>

   <td colspan="2" width="209"> </td>

   <td colspan="3" width="371"> </td>

  </tr>

  <tr>

   <td colspan="4" width="360"><strong>methods</strong></td>

   <td colspan="3" width="371"> </td>

  </tr>

  <tr>

   <td rowspan="2" width="86"><strong>identifier</strong></td>

   <td rowspan="2" width="65"><strong>return type</strong></td>

   <td rowspan="2" width="105"><strong>parameters</strong></td>

   <td rowspan="2" width="104"><strong>what does the method do?</strong></td>

   <td rowspan="2" width="92"><strong>instance variables used</strong></td>

   <td colspan="2" width="278"><strong>Development history for this method</strong></td>

  </tr>

  <tr>

   <td width="155"><strong>implementation</strong><strong>of code (of this method)</strong><strong>date coding completed</strong></td>

   <td width="123"><strong>testing of code (of this method)</strong><strong>date testing completed</strong></td>

  </tr>

  <tr>

   <td width="86"> </td>

   <td width="65"> </td>

   <td width="105"> </td>

   <td width="104"> </td>

   <td width="92"> </td>

   <td width="155"> </td>

   <td width="123"> </td>

  </tr>

  <tr>

   <td width="86"> </td>

   <td width="65"> </td>

   <td width="105"> </td>

   <td width="104"> </td>

   <td width="92"> </td>

   <td width="155"> </td>

   <td width="123"> </td>

  </tr>

 </tbody>

</table>

<h1>Program Style</h1>

The code you write for this assignment must be a single class called PirateDog, with the code in a file called PirateDog.java. This class should <em>not</em> have a main() method, execution of the code will be initiated from the “driver” program AssigTwo216.java (supplied). It is expected that the code in PirateDog.java will instantiate an R2JCD2 object (code supplied) and will call its methods.

Your program should follow the coding conventions introduced in this unit, especially: Variable identifiers should start with a lower case letter final variable identifiers should be written all in upper case and declared before non-final variables

All local variables (with the exception of loop counters in for loops) should be declared at the start of methods and before any other Java statements

Every if-else statement should have a block of code for both the if part and the else part (if used)

Every loop should have a block of code

The program should use final variables as much as possible

Opening and closing braces of a block should be aligned

All code within a block should be aligned and indented 1 tab stop from the braces marking this block

Commenting:

There should be a block of header comment which includes at least  file name, student name and ID, stage of development reached

Each variable declaration should be commented

There should be header comments for each method indicating:

What the method does

The purpose of the parameters (if there are any)

What the return value (if any) is for

<strong>What and how to submit      NOTE: You </strong>