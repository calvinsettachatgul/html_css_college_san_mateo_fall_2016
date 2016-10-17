Midterm HTML5 & CSS3 Fall 2016
Max. Marks: 100

Each question carries 10 marks
Group work, use of internet and copying is prohinited
You can use textbooks for reference
The exam due date is 1th of October, 8pm.
Upload your answers in text files only. No pdf or doc formats.

1q. In the code: var socketConnection = new WebSocket('ws://mysocketlecture.com/display',['soap']);

a. What could be the alternative for "ws" (in bold)? And, what difference would it make?
	*there is also wss which is a secure web socket. This is a more secure connection because it can be encrypted *
b. What does "soap" refer to?
	*soap stands for the protocol of sending data over the internet it stands for simple object access protocol*
2q. Explain the code: socketC.onopen = function(){connection.send("This meesage is being sent now");};
	*a listener onopen is placed on the socketC object and executes the javascript method which will send a message (string) when the connection is open*

a. What is socketC referring to?
	*socketC is a web socket object*

	
b. How would you create a socketC object?
	* Use the web socket constructor as above 
	var socketConnection = new WebSocket('ws://mysocketlecture.com/display',['soap']);
c. Where is the message being sent to?
	the message is being sent to the server

3q. WebSocket('ws://mysocketlecture.com/display',['soap']) refers to:
	*a WebSocket Constructor*

a. Destructor
b. Constructor
c. Variable
d. None of the above

4q.a. What will the following piece of HTML5 code do?
	*takes the data from the form username and password and executes the action mysocketlecture.com/help.php*

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
	method="post"
c. Would it be different from "get"? Explain.
	*method="post" sends data to a server.  Then the data will get sent to mysocketlecture.com/help.php to execute a method serverside.*

5q. Consider a div with class "bigdiv". It contains a second div with id "innerdiv" and there is a third div which is inside "innerdiv". What will be the effect of the following chunk of code blocks on the divs?

a.

div.bigdiv div{
        border: 4px solid;
        border-radius:25px;
}
	*Both the first and second  innerdiv will have these styles  of border: 4px solid, border-radius: 25px this selector refers to any divs inside a div with class bigdiv.*

b. div.bigdiv > div{
        border: 4px solid;
        border-radius:25px;
}

	*Only the first inner div will have the styles because > means a direct child of the outer div with class bigdiv.  The first innerdiv will have those styles.*

