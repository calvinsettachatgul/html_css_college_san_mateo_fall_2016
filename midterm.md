Midterm HTML5 & CSS3 Fall 2016
Max. Marks: 100

Each question carries 10 marks
Group work, use of internet and copying is prohinited
You can use textbooks for reference
The exam due date is 1th of October, 8pm.
Upload your answers in text files only. No pdf or doc formats.

1q. In the code: var socketConnection = new WebSocket('ws://mysocketlecture.com/display',['soap']);

a. What could be the alternative for "ws" (in bold)? And, what difference would it make?
b. What does "soap" refer to? 

2q. Explain the code: socketC.onopen = function(){connection.send("This meesage is being sent now");};

a. What is socketC referring to?
b. How would you create a socketC object?
c. Where is the message being sent to? 


3q. WebSocket('ws://mysocketlecture.com/display',['soap']) refers to:

a. Destructor
b. Constructor
c. Variable
d. None of the above

4q.a. What will the following piece of HTML5 code do?

<!DOCTYPE HTML>
<body>

<form id="myForm" action='mysocketlecture.com/help.php' method="get">
Username: <input type="text" name="username">
Password: <input type="password" name="password">
<input type="submit">
</form>

</body>

</html>

b. What else could be used in place of method="get"?
c. Would it be different from "get"? Explain.

5q. Consider a div with class "bigdiv". It contains a second div with id "innerdiv" and there is a third div which is inside "innerdiv". What will be the effect of the following chunk of code blocks on the divs?

a.

div.bigdiv div{
	border: 4px solid;
	border-radius:25px;
}

b. div.bigdiv > div{
	border: 4px solid;
	border-radius:25px;
}

6q. What does the following chunk of code do?

a. <canvas id="newCanvas" width="170" height="125"></canvas>
b.    var canvasContext = document.getElementById("newCanvas").getContext("2d");
In b, what is the need of creating a canvasContext?
7q. Draw a triangle with the help of  "var canvasContext" object in question 6b.
8q.  You are asked to create a flight booking form for the year 2016 only. So, consider that a user can input all dates from 1-1-2016 through 12-31-2016. How would you achieve this with the help of HTML5?
9q. Given the following piece of markup:
<audio controls>
<source src="maroon5songone.mp3" type="audio/mpeg">
<source src="tobykeithscountrymusic.mp3" type="audio/mpeg">
</audio> 
Given that a user is trying to play the audio files on a non supported browser, how would you inform the user about it?
10q. What is the difference between css code a and b?
a.
.myDiv {
float: left;
margin: 8px;
padding:4px;
height: 200px;
border: 4px solid blue;
} 

b. @media all and (max-width: 1000px) and (min-width: 700px) { 
	.myDiv {
	float: left;
	margin: 8px;
	padding:4px;
	height: 200px;
	border: 4px solid blue;
	} 
}
 





