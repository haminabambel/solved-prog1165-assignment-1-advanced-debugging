Download Link: https://assignmentchef.com/product/solved-prog1165-assignment-1-advanced-debugging
<br>
Well-designed applications should never “crash”; they should deal with exception or error scenarios in a clean and controlled manner. However, there are times when these exception conditions (even in production) should be noted and reviewed by the development team. A “logger” is often used to record key data when a problem occurs in your code. In the Windows environment, the Event Log is an example of a repository for logged information. Often, a simple text file can be used as well.

In this assignment, you will be implementing a simple logging facility.

REQUIREMENTS

Here are the requirements for error logging:

<ul>

 <li>A function called <em>LogError</em> must write an error message to a text file, to the debug console, or to the program console. This message must contain the following information:

  <ul>

   <li>Date and time of occurrence</li>

   <li>Error message (passed to the function as a parameter) – Use #define statements to identify: o The output mechanism for the errors (text file, debug console or program console) o The file path for the text file for the error log</li>

  </ul></li>

 <li>Use conditional compile statements in the <em>LogError</em> function to determine where the error message output should go</li>

</ul>

Write a test program that demonstrates the use of the<em> LogError</em> function. Initially, write a program that does the following <strong><em>WITHOUT</em></strong> the error logging:

<ul>

 <li>Ask for the user’s age</li>

 <li>If the input is non-numeric, you should give the user a friendly message stating that the input is nonnumeric</li>

 <li>If the input is null (empty string), you should give the user a friendly message stating that the input cannot be blank</li>

 <li>If the input is less than 1 or greater than 110, you should give the user a friendly message stating that the input is out of range</li>

 <li>If the age is valid (positive integer), simply say “Thank You” and end the program</li>

 <li>If there is any error in the age, the age should be asked for again</li>

</ul>

Once the program works, add error logging function calls in appropriate places to record where users make errors.

Often, multiple groups will name their assignment files assignment1.zip (or some other common combination) which results in confusion and complications when downloading and unzipping submitted electronic files.

Please follow the following guidelines for all submissions this term. Failure to follow the electronic submission guidelines may result in <em>a 10% penalty per infraction</em>.

As long as other file naming conventions are followed, you may choose to append an assignment identifier (i.e. “_a1” or something else as appropriate) as the <strong>LAST</strong> element before the file extension.

<h1>ZIPPED SOURCE CODE</h1>

Unless otherwise requested, you should only ever submit a single zip file containing the source code as specified. Your source code must always be contained <strong>WITHIN</strong> a top level folder named correctly, so that when it is extracted, it does not lose naming information.

The top level directory should be named with the usernames of all team members as follows:

<ul>

 <li>Individual assignments: username_src.zip (i.e. jsmith_src.zip)</li>

 <li>When working alone: username_src_alone.zip (i.e. jsmith_src_alone.zip)</li>

 <li>When working with a partner: username1_username2_src.zip (i.e. jsmith_bjones_src.zip)</li>

 <li>When working as a team: username_src_team.zip (i.e. jsmith_src_team.zip – but be certain to include all team members in every code header)</li>

</ul>

Place your <strong>CLEANED</strong> project file(s) and / or folder(s) inside this correctly named top level directory before zipping your files.