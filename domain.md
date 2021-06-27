# Problem Domain, Objects, and the DOM
## Understanding The Problem Domain Is The Hardest Part Of Programming

##     Problem domain

- A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics of an individual's interest, and excluding everything else. For example, when developing a system to measure good practice in medicine, carpet drawings at hospitals would not be included in the problem domain. In this example, the domain refers to relevant topics solely within the delimited area of interest: medicine. This points to a limitation of an overly specific, or overly bounded, problem domain. An individual may think they are interested in medicine and not interior design, but a better solution exists outside of the problem domain as it was initially conceived. For example, when IDEO researchers noticed that patients in hospitals spent a huge amount of time staring at acoustic ceiling tiles, which "became a symbol of the overall ambiance: a mix of boredom and anxiety from feeling lost, uninformed, and out of control."
## What is the hardest thing about writing code?

There are many common answers to this question:

-  Learning a new technology
- Naming things
-  Testing your code
-  Debugging
-  Fixing bugs
-   Making software maintainable


## What can you do about it?


If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

    Make the problem domain easier
    Get better at understanding the problem domain 

You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

What I mean by this is that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

Games are really good at this.  Look at most games today and you’ll find that you start with a very small problem domain.  The first level is usually a tutorial that has a basic set of things you can do so that you don’t get overwhelmed.  But, as you advance through the levels, you usually find they get harder and introduce new concepts that build gradually on what you know, until you understand a pretty large problem domain. 


## WHAT IS AN OBJECT?
- Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
- IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES
If a variable is part of an object, it is called a
property. Properties te ll us about the object, such as
the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name
and a different number of rooms.
- IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms

## Document Object Model

- Document Object Model (DOM) is the object-oriented representation of an HTML or XML document. It defines a platform-neutral programming interface for accessing various components of a webpage, so that JavaScript programs can change document structure, style, and content programmatically.

- It generates a hierarchical model of the HTML or XML document in memory. Programmers can access/manipulate tags, IDs, classes, attributes and elements using commands or methods provided by the document object. It's a logical structure because DOM doesn't specify any relationship between objects.

- Typically you use DOM API when documents can fit into memory. For very large documents, streaming APIs such as Simple API for XML (SAX) may be used.

- The W3C DOM and WHATWG DOM are standards implemented in most modern browsers. However, many browsers extend these standards. Web applications must keep in view the DOM standard used for maintaining interoperability across browsers.
Discussion

    > What are the different components of a DOM?
    - Purpose of DOM is to mirror HTML/XML documents as an in-memory representation. It's composed of:
        Set of objects/elements
        Hierarchical structure to combine objects
        An interface to access/modify objects

    - DOM lists the required interface objects, with supported methods and fields. DOM-compliant browsers are responsible to supply concrete implementation in a particular language (mostly JavaScript).

    Some HTML DOM objects, functions & attributes:

    -  Node Each tree node is a Node object. Different types of nodes inherit from the basic Node interface.
     - Document - Root of the DOM tree is the HTMLDocument node. Usually available directly from JavaScript as document or window. Gives access to properties associated with a webpage such as URL, stylesheets, title, or characterSet. The field document.documentElement represents the child node of type HTMLElement and corresponds to <html> element.
    - Attr – An attribute in an HTMLElement object providing the ability to access and set an attribute. Has name and value fields.
    - Text — A leaf node containing text inside a markup element. If there is no markup inside, text is contained in a single Text object (only child of the element).
    

    - The simplest way to see the DOM generated for any webpage is using "Inspect" option within your browser menu. DOM element navigation window that opens allows you to scroll through the element tree on the page. You can also alter some element values and styles – text, font, colours. Event listeners associated with each elements are also listed.

    - The document is the root node of the DOM tree and offers many useful properties and methods. document.getElementById(str) gives you the element with str as id (or name). It returns a reference to the DOM tree node representing the desired element. Referring to the figure, document.getElementById('div1') will return the first "div" child node of the "body" node.

    - We can also see that "html" node has two direct children, "head" and "body". This example also shows three leaf nodes containing only text. These are one "title" and two "p" tags.

    Corresponding CSS and JavaScript files referenced from HTML code can also be accessed through DOM objects.
 