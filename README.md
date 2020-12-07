<h2>Motivation</h2>
i was bitten few times by async\await inside loop so decided to show the problem and solution

<h2>Problem</h2>
i have a loop on axios.get and i want to console Done after i get all the responses, so i am using await on each axios.get.
This is not working -> check server-async-for-sample-problem.js and server-async-foreach-sample-problem.js

<h2>Solution</h2>
<ul>
<li>use Promise.all for loop with foreach -> check these versions server-async-loop-ok-ver1.js and server-async-loop-ok-ver2</li>
<li>use await for loop with loop </li>
</ul>

<h2>Conclusion</h2>
Doing loop with await is confusing but the solution used in for loop seem reasonable.

