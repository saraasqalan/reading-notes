# JS
![object](https://cdn.educba.com/academy/wp-content/uploads/2019/10/JavaScript-Objects-2.png)
## what is object 
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names

**how to creat a new object**
- literal notation is the easiest and most popular way to creat object ( var objectName = 'value')
yoy can add property to object by added after (.)

## The Document Object Model
specifies how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window
![dom](https://media.geeksforgeeks.org/wp-content/uploads/DOM.png)
**methods that find elements in the DOM tree are called DOM queries  when you need to work with an elemnt more than once you should use a variable to store the result of this query**

- SELECTING AN ELEMENT FROM A NODELIST (There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want.)

- Array syntax ( is preferred over the item() method because it is faster )

- when you have NodeList you can loop through each node in the collection and apply the same statment to each

**ADDING OR REMOVING HTML CONTENT**
there are two very different approaches to adding and removing content from DOM tree
- the **innerHTML** property
- **DOM** mainpulation

**ATTRIBUTE NODES**
once ypu have an element node yoy can use other properties and methods on that element node to access and change its attributes

***MOST IMPORTANT TO KNOW**
- The browser represents the page using a DOM tree.
DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
- From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and
child elements that are siblings of each other.
- n older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
- Browsers offer tools for viewing the DOM tree



