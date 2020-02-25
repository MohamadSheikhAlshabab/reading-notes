# class-09

____________

## HTML Summary :
 ### FORMS :
 - ADDING TEXT:
   - Text input (single-line)
   - Password input
   - Text area (multi-line)
   
 - Making Choices:
   - Radio buttons
   - Checkboxes
   - Drop-down boxes
   
 - Submitting Forms:
   - Submit buttons
   - Image buttons
 
 - Uploading Files:
   -File upload
   
 - <'form'> has attribute :
     - action : Its value is the URL for the page on the server that will receive the information in the form when it is submitted. 
     - method .
     
 - <'input'> :
      - type="text" it creates a singleline text input.
      - type="password" it creates a text box that acts just like a single-line text input, except the characters are blocked out.
      - type="radio" allow users to pick just one of a number of options.
      - type="checkbox" allow users to select (and unselect) one or more options in answer to a question.
      - type="file" This type of input creates a box that looks like a text input followed by a browse button.
      - type="submit" is used to send a form to the server.
      - type="image" use an image for the submit button.
      - type="hidden" shows a hidden form control.
      - type="date" give the type attribute a value of date.
      - type="email" If you ask a user for an email address to input it. 
      - type="url" used when you are asking a user for a web page address.
      - type="search" If you want to create a single line text box for search queries.
      
  - <'textarea'> : is used to create a mutli-line text input.
  - <'select'> is used to create a drop down list box.
  - <'option'> is used to specify the options that the user can select from.
  - <'label'>  : 1. Wrap around both the text description and the form input.
                 2. Be kept separate from the form control and use the for attribute to indicate which form control it is a label for.
  - <'fieldset'> You can group related form controls together inside it.
  - <'legend'> contains a caption which helps identify the purpose of that group of form controls.


- HTML5 introduces new form elements which make it easier for visitors to fill in forms.


----------------------

 ### Lists, Tables and Forms :
  
  - list-style-type : allows you to control the shape or style of a bullet point known as a **marker**.
    can be : 
            1. Unordered Lists :  
                - none
                - disc
                - circle
                - square
            2. Ordered Lists :
                - decimal
                - decimal-leading-zero
                - lower-alpha
                - upper-alpha
                - lower-roman
                - upper-roman
   - list-style-image :  You can specify an image to act as a bullet point.
   - list-style-position :indicates whether the marker should appear on the inside or the outside of the box containing the main points.
      - has two values :
       - outside (default)
       - inside
- list-style :allows you to express the markers' style, image and position properties in any order.
- cursor  allows you to control the type of mouse cursor that should be displayed to users.
  values :
  - auto
  - crosshair
  - default
  - pointer
  - move
  - text
  - wait
  - help
  - url("cursor.gif");
  
  
_________________

## JS Summary :
  ### EVENTS :
  
  - Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
  - Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
  - When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
  - You can use event delegation to monitor for events that happen on all of the children of an element.
  - The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.
