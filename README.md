Download Link: https://assignmentchef.com/product/solved-comp1400-lab5-programming-with-loops
<br>
<strong>HI-LO game: </strong>A random number will be generated. Then, the program prompts for guesses until the user is correct, or has made 10 wrong guesses. After each guess, the program indicates whether the guess was too high, too low, or correct. Once the round has ended, either by a correct guess or by using up the 10 guesses, the program displays the current status. Assuming the random number is 48 (a number between 1 and 50), a sample interaction is shown below

Enter your guess (between 1 and 50): <strong><u>30</u></strong>

Too low …

Enter your guess (between 1 and 50): <strong><u>50</u></strong>

Too high …

Enter your guess (between 1 and 50): <strong><u>48</u></strong> Correct, the number was 48.




If the user entered more than 10 wrong guesses:




Sorry, the number was 48.




<strong>Part A: RAPTOR Exercise </strong>

<ol>

 <li>Understand more about RAPTOR by watching the video clip about <em><u>how to work</u></em><em> <u>with loops</u></em><u>.</u></li>

 <li>Start RAPTOR and create the flowchart of HI-LO game.</li>

 <li>Save the flowchart to a file named “guessGame.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the guessGame.rap file to GA/TAs and run with different input values.</li>

</ol>

<strong>Hint:</strong> To generate a random number between 1 and 50 using Raptor, use the following assignment statement




<strong>goal </strong>ß<strong> floor((Random*50)+1) </strong>

<strong> </strong>

For more information, watch the video clip about <em><u>how to generate a random number</u></em><em> <u>Using Raptor</u></em>

<strong> </strong>

<strong>Part B: C Programming Exercise </strong>




<ol>

 <li>Implement the algorithm as represented by “guessGame.rap”, and write an equivalent C program that accomplishes what the flowchart does.</li>

 <li>Save your program to a file named “guessGame.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the guessGame.c file to GA/TAs and run with different input values.</li>

</ol>




<strong>Hint: </strong>To generate a random number between 1 and 50 in C, first, add  <strong>#include &lt;stdlib.h&gt;</strong> to your code and then use the following statement:

<strong>int goal = rand( ) % 50 + 1; </strong>

<strong> </strong>

<strong> </strong>

<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.




<strong> </strong>

<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:




<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable? Is the code run properly?</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>

<strong>IMPORTANT: </strong>DO YOUR OWN CODE. ANY CODE SUSPECTED TO BE SIMILAR TO ANOTHER SUBMISSION WILL CAUSE BOTH SUBMISSIONS TO RECEIVE A ZERO MARK ON ALL LABS AND BE REPORTED FOR PLAGIARISM.


