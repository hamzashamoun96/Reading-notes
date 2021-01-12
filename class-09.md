# Forms
* There are several types of form controls that you can use to collect information from visitors to your site, such as password input , text input , making choices(Radio buttons , Checkboxes , Drropdown boxes) and submitting forms.
### How form work 
* Auser fill in a form then presses a button to submit th information to the server, then the name of each form control is sent to the server then the server processes the information using a programming language it also store the information in a database then the server creates a new page to send back to the browser based on the information recived.
* The server needs to know which piece of inputted data corresponds with which form element.
* To create a form use < form> element with an attribute of (action) which it's value is the URL for the page on the server that will recive the information in thr form.
* < input> element is used to create several different form control it have an attributr called (type) and it's value determines what kind of input they wil be creating, also it must have an attribute called (name) to let know the server which form control each data was intered to.
* < textarea> element allows you to create a multiline text input.
* (radio) value of the (type) attribute create a radio button. 
* (checkbox) value of the (type) attribute create a checkbox.
* To create a drop down list box use < select> element and < option> element to specify the option this list have.
* To create a file input box use < input> element with an attribute (type) and it's value (file).
* To create a label form each form control use < label> element.
# Events
* When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events. 
* Here is a selection of the events that occur in the browser while you are browsing the web:
![events](https://serving.photos.photobox.com/77638807ef9f34e69a9694bfde8caaf35fc3570476d9477b98de505d530d7a68f5daf18e.jpg)