
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.<br><br>

Within a Github action that runs whenever code is pushed. This is because this way we are able to detect issues early thru github actions (like in our teams project), allowing us to ensure of code quality and bug detection. <br><br>

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)<br><br>
   
No, because end to end testing is meant to test from the user persepctive (UI). There is another test for seeing if a function/code is returning the wrong output.<br><br>

3) What is the difference between navigation and snapshot mode?<br><br>
   Snapshot evalutes on an already loaded page(faster) while navigation mode loads the page in order to evalute (slower). 

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.<br><br>
   1. properly sized images as it could save 864 kib, helping perfomance issues<br>
   2. have a <meta name="viewport">  tag as it can optimizes the app for mobile screen sizes<br>
   3. reduce unused javascript as it can also help with performance issues

 
