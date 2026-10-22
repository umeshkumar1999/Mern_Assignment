# Assigment 1 – What happens between typing a URL and seeing the page?

\*\* Answer :-

When a user types a URL into a web browser and presses Enter, several steps happen before the webpage appears.

First, the browser reads the URL to identify the website the user wants to visit. Next, the browser uses DNS to find the IP address associated with the domain name.

After obtaining the IP address, the browser establishes a connection with the server. For an HTTPS website, it also establishes a secure connection using TLS.

The browser then sends an HTTP request to the server. The server processes the request and sends back an HTTP response containing the requested webpage or information about it.

The browser processes the HTML, CSS, JavaScript, and other resources it receives. Finally, it renders the content and displays the webpage to the user.

# Assignment 2 – Setup Proof (VS Code, Node.js, Live Server)

\*\* Answer :-
vs-code :- vs-code is stand for visual studio code and it writing code. That is why it is also called as code editior
we cand intall it from official website :- https://code.visualstudio.com/Download?utm_source=chatgpt.com

Node.js :- Node.js is a JavaScript runtime environment that allows us to run JavaScript code outside a web browser.
And dwe download it from official websites :- https://nodejs.org/?utm_source=chatgpt.com
And we can confirm it by the runnig the commands :- node -v and npm -v on the terminal

Live Server :- Live server is vs-code extention that is used to display our code on webpage.
or
Live Server is a VS Code extension that runs a local development server to display our HTML code as a webpage in a web browser. It automatically refreshes the webpage whenever we save changes to our code.

# Assignment 3 – Terminal Navigation Practice Sheet

\*\* Answer :-
| # |Task | Command | PowerSher |
|--- | --- | ---| --- |
|1| Show current forder | `pwd` |`pwd`|
|2| List files |`ls`| `ls`|
|3| List with details + hidden files| `ls-la`|`ls-force`|
|4| Create a folder |`mkdir practice`|`mkdir practice`|
|5| Enter the folder | `cd practice`|`cd practice`|
|6| create an empty file| `touch index.html`| `ni index.html`|
|7| Create nested folder| `mkdir -p css/image`| `mkdir -p css/image`|
|8| Go up one level | `cd..`| `cd..`|
|9| Go to home directory| `cd~`|`cd~`|
|10| Copy a file | `cp index.html back.html`|`cp index.html back.html`|
|11| Move a file into another file| `mv fileName1 fileName2`|`mv fileName1 fileName2`|
|12| Delete a file | `rm fileName`| `rm fileName`|
|13| Delete a folder | `rm -r folderName`|`rm -r folderName`|
|14| Print the file content | `cat filedName`| `cat fileName`|
|15| clear the screen | ` clear`| `cls`|
|16| Open the folder in vs-code | `code .`| `code .`|