# Java-Practice-Task-1
Parser that reads a URL from the console and returns an output based on the conditions of the task.

Request parser
Read a URL from the console.
Display a space-delimited list of all the parameters (The parameters follow the "?" and are separated by "&", e.g. "lvl=15").
The URL contains at least 1 parameter.
The parameters must be displayed in the same order in which they are present in the URL.
If the obj parameter is present, pass its value to the relevant alert method.
alert(double value) - for numbers (fractional numbers have a decimal point)
alert(String value) - for strings
Note that the alert method must be called AFTER the list of all parameters is displayed.

Example 1

Input:
http://codegym.cc/alpha/index.html?lvl=15&view&name=Amigo

Output:
lvl view name

Example 2

Input:
http://codegym.cc/alpha/index.html?obj=3.14&name=Amigo

Output:
obj name
double: 3.14


