# HTML FORM 
![how forms work](https://img.webnots.com/2014/01/How-HTML-Form-Works.png)
**how forms work**
- A user fills in a form and then presses a button
to submit the information to the server.
- A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.
**Form Structure**
- < form>
Form controls live inside a
< form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.
- action
Every < form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted
- method
Forms can be sent using one of
two methods: get or post
**form structure**
< form action="http://www.example.com/subscribe.php"
method="get">


**< input> The < input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating**
- type="password"
When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
They are hidden in this way so
that if someone is looking over
the user's shoulder, they cannot
see sensitive data such as
passwords.
- < textarea>
The <textarea> element
is used to create a mutli-line
text input. Unlike other input
elements this is not an empty
element. It should therefore have
an opening and a closing tag.
- type="radio"
Radio buttons allow users to pick
just one of a number of options.
- type="checkbox"
Checkboxes allow users to select
(and unselect) one or more
options in answer to a questio

***MOST IMPORTANT TO KNOW***
- Whenever you want to collect information from
visitors you will need a form, which lives inside a
< form> element.
-  Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
- HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# HTML List Table and Forms
- In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
- List markers can be given different appearances
using the list-style-type and list-style image
properties.
- Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
- Forms are easier to use if the form controls are
vertically aligned using CSS.
- Forms benefit from styles that make them feel more
interactive


# JS EVENTS
![js events](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)
 **event flow**
 HTML elements nest inside other elements if you hover or click on a link you will also be hovering or cliking on its partent element
 
 The flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant elements


 ***MOST IMPORTANT TO KNOW IN JS EVENT***
 - Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
- Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
- When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
- You can use event delegation to monitor for events
that happen on all of the children of an element.
- The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 




