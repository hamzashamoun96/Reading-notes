# Objects
* Objects are set of variables and functions grouped together to create a model.
* Variables in objects known as properties, and Functions knows as methods.
* Properties and methods have a name and value and in object that name called a key, and the value can be a (string, number, boolean, array, object), and the value of a method is always a function.
* We create an object by: Literal notation which is the easiest and the most popular way (write down the content between curly brackets).
* To access a property or a method in an object just write down object name followed by a (dot) then the property or method name you want to access, This is known as (dot notation).
* The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
* Each node is an object with methods and properties, Scripts access and update this DOM tree (not the source HTML file), Any changes made to the DOM tree are reflected in the browser. 
![DOM TREE](https://serving.photos.photobox.com/5981610733e78661a84a15ceaff27d1253b7569339303c7ac12bb7b123f7b467b8e3584c.jpg)
* To select an individual element node use (getElementById), (querySelector).
* To select multiple elements (nodelists) use(getElementsByClassName), (getElementsByTagName),(querySelectorAll).
* To traversing between element nodes use (parentNode), (previousSibl ing / nextSibl ing), (firstChild / lastChild).
* The innerHTML property and DOM manipulation methods are used for adding or removimg content from an element, but the DOM manipulation methods can be safer than innerHTML but it requires more code and can be slower.
* If you add HTML to a page using innerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts. 
* For defending against cross-site scripting we must validate input goning to the server.
* You can change the attributes of any element node just by calling that element node and follow it by (dot) then use a method related to the attribute such as : (getAttribute, hasAttribute, setAttribute, removeAttribute).
