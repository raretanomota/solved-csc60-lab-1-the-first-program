Download Link: https://assignmentchef.com/product/solved-csc60-lab-1-the-first-program
<br>
<strong><u>GOAL</u></strong>:  Learn the procedure to enter a program, compile and build it, and get it to work.  Most of this will be needed ALL semester for almost every assignment.

<strong><u> STEP 1:  GETTING STARTED  </u></strong><u>– get an account<strong> . </strong></u>

You may need to turn the screen on. Log on with your ECS account.  If you do not have one yet:

<ol>

 <li>Open a browser</li>

 <li>Go to <a href="http://www.ecs.csus.edu/index.php?content=accounts">http://www.ecs.csus.edu/index.php?content=accounts</a></li>

 <li>Under Section <em>Request or Modify, </em>click on <em>Apply for a new ECS account (Windows/Unix)</em></li>

 <li>Follow the directions.</li>

</ol>

You will receive an email when the account is ready. You (with your One Card) can pick up the paperwork from the lab assistant in RVR-2011.

<strong><u>LOGGING ON TO Athena:</u></strong>

<strong><u> STEP 2a:  Turn on an ECS computer &amp; log in to  <em>athena</em> . </u></strong>

Labs:  RVR-2011, RVR-2013 (when it has no class in it), SCL-1208, SCL-1234.

Log in with your account.  Lots of windows will scroll by. Wait for them to clear.

Click on the Start Button in the lower left of the screen.

In the Search box, type PuTTY.

Click on PuTTY (in the Programs list).

The PuTTY window will open.

In the box labeled Host Name, type <strong>athena.ecs.csus.edu </strong>Click on Open (lower right of the window).

You will get a window to <strong>athena</strong> with a prompt to “Log in as”.

Enter your User Name.

Enter your Password. (Nothing will show on the screen as you type it.) You will now have a prompt such as the one I got<strong>:  [<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f2909b979e80b293869a979c93">[email protected]</a> ~]&gt;</strong>

<strong><u>STEP 2b: Logging in from home on a Windows machine.</u></strong>

Download PuTTY or another terminal program to your computer.

Open PuTTY.

In the box labeled Host Name, type <strong>athena.ecs.csus.edu </strong>Click on Open (lower right of the window).

You will get a window to <strong>athena</strong> with a prompt to “Log in as”.

Enter your User Name.

Enter your Password. (Nothing will show on the screen as you type it.) You will now have a prompt similar to the one I got<strong>:  [<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f3919a969f81b392879b969d92">[email protected]</a> ~]&gt;</strong>

<strong><u>STEP 2c: Logging in from home on a Mac machine.</u></strong>

Open up a terminal/console window and type one of the following:             ssh <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="1d6472686f585e4e737c70785d7c697578737c33787e6e337e6e686e33787968">[email protected]</a> Press Enter.

When prompted, type “yes” to accept the server’s key.

Then enter your password. (Nothing will show on the screen as you type it.)

<strong><u>STEP 2d: Using hydra</u></strong>

Log into hydra from <strong>Windows</strong> home computer and pretend like you are on campus From Windows, bring up the Remote Desktop Connection software. In the box labeled “computer”, enter:  <strong>hydra.esc.csus.edu </strong>Refer to Step 2a above to get to <em>athena.</em>

Log into hydra from <strong>MAC</strong> home computer and pretend like you are on campus. There is information of the ECS website that explains how to find hydra on your mac. Below are two choices for getting to the same information. Refer to Step 2a above to get to <em>athena.</em>

Use the following link for directions for the software and its use:

<a href="https://www.ecs.csus.edu/computing/help_docs/Connecting_to_Hydra-Mac.pdf">https://www.ecs.csus.edu/computing/help_docs/Connecting_to_Hydra-Mac.pdf</a>

<strong><u>STEP 3:  GETTING SET UP TO START </u></strong>You should now be logged into <em>athena</em>.

Create a directory (subfolder) for this class by typing:  <strong>mkdir csc60</strong>

Change to the new folder by typing:  <strong>cd csc60</strong>

Create a directory for this assignment by typing:  <strong>mkdir lab1 </strong>Change to the new folder by typing:  <strong>cd lab1</strong>

<strong><u>STEP 4:  START ENTERING YOUR PROGRAM.</u></strong>

At the prompt “&gt;”, type <strong>vim lab1.c</strong>

Go into insert mode by typing:  <strong>i     </strong>

Start typing in your program in this window.

For this Lab1, enter in the program that appears below <em>inside the box</em> below.

(PS: You <strong>don’t</strong> have to create the box.)

Type your own full name (both first and last) in all the places needed.

Start typing at the left edge of the screen.

Use the indentation style as shown.

Attribution for the quote is <u>required</u>. You may print  the quote &amp; attribution in one <em>printf</em> or two.

<strong> more on next page</strong>

<strong><em><u>Teacher Comments</u></em></strong><em>:</em>




<em>Don’t count the dashes. Approximate.</em>

<em>Put Your-Name here, both <u> first &amp; last   </u></em>

<em>“/*    */” = comment symbol</em>

<em>{Preprocessing directives for</em>

<em>{the compiler.</em>

<em>Line required in each program.</em>




<em>Be sure to indent for clarity </em>           <em>Put your First &amp; Last name here!</em>

<strong><em>Put your quote here</em></strong><em> instead of the word “quote”</em>

<table width="232">

 <tbody>

  <tr>

   <td width="232"><strong>/*————————-*/ </strong><strong>/* Your Name Here   */        </strong><strong>/* Lab 1                       */</strong> <strong>#include &lt;stdio.h&gt;</strong><strong>#include &lt;stdlib.h&gt;</strong> <strong>int main (void)</strong><strong>{</strong><strong>printf(“
Lab 1. 

”);</strong>           <strong>printf(“Hello World.
”);</strong>                <strong>printf(“Hi, Your Name. 

”); </strong>        <strong>printf(“quote 

”);</strong><strong>return EXIT_SUCCESS;</strong><strong>} </strong><strong>/*————————-*/</strong></td>

  </tr>

 </tbody>

</table>

Attribution for the quote is <u>required</u>.

<em>Capitalize EXIT_SUCCESS</em>







<strong><u>5:  SAVE YOUR WORK, COMPILE IT, AND SEE THE RESULTS.</u></strong>

Get out of insert mode by typing:  <strong>Esc </strong>  (escape key) To save your work and quit, type:  <strong>:wq </strong>The shell prompt returns.

Type:  <strong>gcc lab1.c   </strong>(This compiles the program and sends the output to a file called <strong>a.out</strong>) If you have compile errors, they will appear, and they will need to be fixed. The prompt returns.

<u>If you have no errors</u>, type <strong>a.out</strong> and the output of your program will display. The results of my program appear below.

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="ed8f8488819fad8c998588838c">[email protected]</a> ~/csc60]34&gt; a.out

Lab 1.

Hello World.

Hi, Ruthann Biel.

Be yourself; everyone else is already taken.

– Oscar Wilde                                                                NOTICE the attribution for the quote is                                                                                         required.

[<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="bfddd6dad3cdffdecbd7dad1de">[email protected]</a> ~/csc60]35&gt;

<strong><u>Comments</u></strong>:  Your instructor is picky about presentation.  There should be an empty line between <em>a.out</em> and <em>Lab 1, </em>and again at the end before the prompt returns.  I expect your output to have empty lines where they show above.  Use proper English and proper punctuation in your quote. Save your creativity for the quote.

<strong><u>To show your line numbers in VIM:</u></strong>

<ol>

 <li>Press the <strong>Esc</strong> key if you are currently in insert or append mode.</li>

 <li>Type the <strong>:</strong> (colon). The cursor should reappear at the lower left corner of the screen next to a colon (:) prompt.</li>

 <li>After the colon, enter the following command: <strong>set number</strong></li>

 <li>A column of sequential line numbers will then appear at the left side of the screen.</li>

</ol>

<strong><u>If you have Errors:</u></strong>

<em>If you have errors</em>, it is OK, a normal course of events.  Examine the Error Message list.  Sometimes the second or third message makes more sense than the first error message.  One code error can cause SEVERAL error messages.




Fix your errors, and save your changes.  Go back to the top of STEP 5. Repeat until you have NO ERRORS.

<table width="636">

 <tbody>

  <tr>

   <td width="636"><strong>                                                             </strong><strong>MAJOR REMINDER</strong>.Every time you change the code, you must <strong>redo</strong> the COMPILE (which is the <strong>gcc</strong>       line) before you run the program, or you will NOT see any changes when you       run the program. !!!</td>

  </tr>

 </tbody>

</table>

<strong><u>STEP 6.  PREPARE YOUR FILE FOR GRADING.</u></strong>

When all is well and correct, and you are still on <em>athena</em>,

<ul>

 <li>type: <strong>script StudentName_lab1.txt       </strong>Script will keep a log of your session.</li>

</ul>

Please use Your name instead of “StudentName”     Use your first and last name.

<ul>

 <li>At the prompt, type: <strong>gcc lab1.c   </strong>To compile the program.</li>

 <li>At the prompt, type: <strong>out          </strong>To run the program.</li>

 <li>After the program run is complete, type: <strong>exit </strong>To leave the session.</li>

</ul>

NOTE:  If you forget to type <strong>exit</strong> to leave <em>script</em>, your script file will be <u>empty</u>!!!

<strong><u>STEP 7:  Move your files to be accessible to your browser.</u></strong>

Go to Power Point File <em>1-Unix Start</em>, slide #6 for solutions to this situation.

<strong><u>STEP 8:  Turn in your work.</u></strong>

Go to Canvas and turn in two files:

<ol>

 <li><strong>c </strong>…the code file</li>

 <li><strong>txt </strong>…the script file</li>

</ol>

<strong><u>STEP 9:  LOG OFF EVERYTHING.</u></strong>

Type “<strong>exit</strong>” when you are ready to leave athena.

Close as much as necessary for safety, depending on your location.