Download Link: https://assignmentchef.com/product/solved-cs3358-assignment-4
<br>



<strong>Stacks – Queues</strong>




For this assignment you will implement stacks and queues ADT. A stack or a queue can be used to recognize a certain types of patterns.

Consider the pattern STRING1#STRING2 where neither STRING1 and STRING2 contains “#”.

Use stack ADT to determine whether or not the two strings are the same. STRING1 and STRING2 are the same if they have the same number of elements and the elements at the corresponding positions are the same.

Use queue ADT to determine whether or not STRING2 is reversed of STRING1.

The program displays a menu on the screen allowing the user to enter the elements of stack or queue. The program terminates when the user enters 9.

<strong>Note:</strong>

<ul>

 <li><strong>Size of stack and queue is determined by the number of the elements </strong></li>

 <li><strong>You are not allowed to use </strong><strong>stack / queue libraries. You must</strong><strong>implement all stack / queue functions and operations . Use only</strong><strong><u> one</u></strong> <strong>.cpp to define and implement templates and the driving program.</strong></li>

 <li><strong>You are not allowed to use string manipulation operations.</strong></li>

</ul>




<em>CS3358 – Data Structures                                                                                                                                            </em><em>Programming</em>

<em>Assignment 4</em>

<strong><u>Validations: </u></strong>

<strong>The program accepts only integer data type when selecting from the menu (1 , 2 , or </strong><strong>9 ) . Everything else should be rejected with an invalid option message.</strong>

<strong><u>Style Guidelines: </u></strong>

At the beginning of your program ( and <strong>before </strong>the #include statement), include the following :

<strong>Header comments </strong>(file documentation block) should be at the top of each file and should contain: Author / s, Due Date, Assignment Number, Course number and section, Instructor, and a brief description of the purpose of the code in the file. For example:

//              Roster Number / s :                      xxxxxxxxx

//

//             Author/ s : (Your name here!!)

//             Due Date :

//            Programming Assignment Number 4

//

//               Spring 2018 -­‐ CS 3358 -­‐ Your Section Number

//

//               Instructor: Husain Gholoom.

//

//               &lt;Brief description of the purpose of the program&gt;

<strong>Variable names:</strong>

<ul>

 <li>Must be meaningful.</li>

 <li>The initial letter should be lowercase, following words should be capitalized, no other caps or punctuation ( i.e. weightInPounds ).</li>

 <li>Each variable must be declared on a separate line with a descriptive comment.</li>

</ul>

<strong>Named constants:</strong>

<ul>

 <li>Use for most numeric literals.</li>

 <li>All capitals with underscores ( i.e. TX_STATE_SALES_TAX )</li>

 <li>Should occur at top of function, or global (only if necessary)</li>

</ul>

<strong>Line length </strong>of source code should be no longer than 80 characters (no wrapping of lines).

<em>CS3358 – Data Structures                                                                                                                                            </em><em>Programming</em>

<em>Assignment 4</em>

I<strong>ndentation:</strong>

<ul>

 <li>Use 2-4 spaces (but be consistent throughout your program).</li>

 <li>Indent blocks, within blocks, etc.</li>

 <li>Use blank lines to separate sections.</li>

</ul>

<strong>Comments for variables:</strong>

All variable definitions should be commented as follows:

int gender;    // integer value for the gender,

// 1 = Male , 2 = Female ,




<em>CS3358 – Data Structures                                                                                                                                           </em><em>Programming</em>

<em>Assignment 4</em>

Sample Run:

*** Welcome to My stack / Queue Program *** The function of this program is to :

<ol>

 <li>Use stack to determine whether or not two strings are the same.</li>

 <li>Use queue to determine whether or not STRING2 is the reversed of STRING1.</li>

</ol>

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 1</li>

</ol>

Enter Stack Values :    5+(12+7)#5+(12+7)

Strings are identical

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 1</li>

</ol>

Enter Stack Values : 5+(12+7]#5+(12+7) Strings are not identical

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 1</li>

</ol>

Enter Stack Values : 5+[12+7)#5+[12+7 Strings are not identical

<em>CS3358 – Data Structures                                                                                                                                           </em><em>Programming</em>

<em>Assignment 4</em>

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 2</li>

</ol>

Enter Queue Values    1234#4321

STRING2 is reversed of STRING1.

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 2</li>

</ol>

Enter Queue Values    1{[(#([{1

STRING2 is reversed of STRING1.

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 2</li>

</ol>

Enter Queue Values    1{[(#([{2

STRING2 is not reversed of STRING1.




<em>CS3358 – Data Structures                                                                                                                                           </em><em>Programming</em>

<em>Assignment 4</em>

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 3</li>

</ol>

Invalid Option

Select from the following menu

<ol>

 <li>Enter Stack Values.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. X</li>

</ol>

Invalid Option

Select from the following menu

<ol>

 <li>Enter Stack Value.</li>

 <li>Enter Queue Values.</li>

 <li>Terminate the program. 9</li>

</ol>

*** End of the program. ***

*** Written by Husain Gholoom *** *** March 28 – 2018 ***




<em>CS3358 – Data Structures                                                                                                                                           </em><em>Programming</em>

<em>Assignment 4</em>

<strong><u>Rules : </u></strong>

<ol>

 <li>Your program <strong>must compile </strong>and run. The program will be tested using the <strong>latest </strong>version of Codeblocks for windows.</li>

 <li><strong>You re</strong><strong> not allowed</strong><strong> to use stack and queue libraries . You Must implement all the functions of stacks and queues. You are also not allowed to use static arrays , vectors </strong><strong>or string manipulation operations, or tempalte.</strong></li>

</ol>

3 . Your program must be properly <strong>documented according the style above .</strong><strong> See the website for the sample programming style program.</strong>

4 . <strong>You must use</strong><strong> repetitions , control structures , and</strong><strong><u> switch</u></strong><strong> statements.</strong>

5 . Must properly format the output by use the appropriate library. See the output below . Also ,<strong> Replace my first / last name with your own first / last name.</strong>

6 . You must name your program as :

o <strong>3358_0_LastName_FirstName_PG4.cpp ( Section 260 )</strong>o <strong>3358_1_LastName_FirstName_PG4.cpp ( Section 261 )</strong>o <strong>3358_2_LastName_FirstName_PG4.cpp ( Section 262 )</strong>

<strong>Where LastName is your Last Name and FirstName is your First Name. For example, </strong><strong>the file name should look something like: 3358_1_Gholoom_Husain_PG4.cpp (</strong><strong> not </strong><strong>.cb p</strong><strong> )</strong>

<ol start="7">

 <li>Every one must upload the electronic version of the program no later than the starting of class time on the due date.<strong> No late assignments will be accepted.</strong><strong><u> DO NOT</u></strong> send your assignment solution via email.<strong><u> Group members must upload identical copy of the assignment.</u></strong></li>

</ol>

<strong>Use TRACS To upload electronic version of your program</strong>

<ol start="8">

 <li>You must <strong>also </strong>turn in hard copy of your source code no later than the starting of class time on the due date . should the hard copy consist of more than one page , then , the hard copy must be <strong>stapled</strong>. if you are unable to turn in a printout during class, you can take the program to the computer science department and hand it to the front desk personal (Comal 211 ) before the Make sure that the front office stamps the program. Make sure that include the date and time. Finally ,make sure that they place the program in my mailbox.<strong><u> Only one copy per </u></strong><strong><u>group.</u></strong></li>

</ol>

<strong>DO NOT</strong> slide your program under my office door – It will<strong> NOT</strong> be accepted




<em>CS3358 – Data Structures                                                                                                                                           </em><em>Programming</em>

<em>Assignment 4</em>

<strong>The following points will be deducted if :</strong>

¥ Compilation errors , incorrect file format such as uploading .cbp instead of .cpp , missing electronic copy , missing the hardcopy , different copies of the assignment per group, using .h and .cpp files , using vectors, using stack / queue libraries<strong> ,</strong> string manipulations, using static arrays or global arrays , using vectors or global vectors , not using class É etc<strong> ( – 10 points)</strong>

¥ Logical Errors<strong> ( at least – 1.25 points)</strong>

¥ Other<strong> ( at least          </strong><strong>-1.50 points)</strong> if <strong><u>any </u></strong> of the following takes a place:

¥ Unable to read the source code due to unclear printing or print

layout is not portrait.

<ul>

 <li>Incorrect Output format. ¥ Incorrect program file name. ¥ Hard copy is not stapled.</li>

 <li>Incorrect Style<strong> such as but not limited to</strong> Missing Header</li>

</ul>

comments , signature line, comments or program documentations

, missing roster nu mber , section number , , not using switch,

using template É etc