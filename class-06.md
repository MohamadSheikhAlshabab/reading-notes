# JS Summary :

 ## What is an object :
 - **Objects** group together a set of _variables_ and _functions_ to create a **model**.
 - **Objects** made up curl braces and contents.
    ___
 - In an object :
  - **VARIABLES** BECOME KNOWN AS **PROPERTIES**.
  - **FUNCTIONS** BECOME KNOWN AS **METHODS**.
  -  **Name** is called a **key**.
    ___ 
 - The value of a **property** can be a _string, number, Boolean, array_, or even another object.
 - The value of a **method** is always a **function**.
  ______________________________________________________
  
  ## article :
  
  - What is the hardest thing about writing code?
   - Learning a new technology
   -  Naming things
   - Testing your code
   - Debugging
   - Fixing bugs
   - Making software maintainable
   
 - also writing code with a blurry picture or no picture at all, so sometimes don't catch big picture.
 __________________________
 
 ## The Document Object Model (DOM):
 
  - **DOM** specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents 
    of a web page while it is in the browser window.
  - **DOM tree** specifies the way in which the browser should structure this model.
  - **DOM tree** has 4 types :
     - **document node**  represents the entire page.
     - **ELEMENT NODE** it is element tags.
     - **ATTRIBUTE NODE** is attribute of opening tag of **HTML**.
     - **TEXT NODES** it's content of element if it has one.
      --------
  - **DOM queries** are methods that finds elements in the **DOM tree**.
    ----
  - getElementByld('id') Selects an individual element given the value of its id attribute.
  - querySelector( 'css selector') Uses CSS selector syntax that would select one or more element s .This method returns 
    only the first of the matching elements.
  - getElementsByClassName('class') Selects one or more elements given the value of their class attribute. 
  - getElementsByTagName('tagName') Selects all elements on the page with the specified tag name.
  - querySelectorAll ('css selector') Uses CSS selector syntax to select one or more elements and returns all
    of those that match.
  - object + "." (member operator means method is being applied to **node**).
  
    ----
  - **collection**    nodelists look like arrays and are numbered like arrays, but they are not ac tually arrays.
  - **live Nodelist** when your script updates the page, the Nodelist is updated at the same time.
  - **static Nodelist** when your script updates the page, the NodeList is not updated to reflect the changes made by the script.
  - THE item() METHOD : Nodelists have a method which will return an individual node from the Node list.
  -  getAttribute() get the value of an attribute .
  - hasAttribute() check if element node has a specified attribute.
  - setAttribute sets the value of an attribute.
  - removeAttribute removes an attribute from an element node.
  -  calssName get or set the value of the class attribute.
  - id : gets or sets the value of the id attribute.
  


  
