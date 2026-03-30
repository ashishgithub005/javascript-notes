
<pre>
<b>CallBack Function :: </b> 
A callback function is a function that is passed as an argument to another function and is executed later.
<b>Simple words: </b>
A callback is a function that runs after another function finishes.

Example
function greet(name, callback) {
    console.log("Hello " + name);
    callback(); // calling callback function
}

function sayBye() {
    console.log("Goodbye!");
}

greet("Ashish", sayBye);

Output:

Hello Ashish
Goodbye!


</pre>
