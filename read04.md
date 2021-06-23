# HTML Links, JS Functions, and Intro to CSS Layout
Links are the defining feature of the web because they allow us to move from one web page to another — enabling the very idea of browsing or surfing.
### Types of links:
- Links from one website to another.
- Links from one page to another on the same website.
- Links from one part of a web page to another part of the same page.
- Links that open in a new browser window.
- Links that start up your email program and address a new email to someone.

### Write a link
- Linking to Other Sites
If you want to mention one HTTP status code, then describing it in your document might make sense. If you want to make sure that your reader understands the idea of HTTP status codes, and knows what several of them mean, then linking them to an external document (such as the HTTP spec) might be a good idea.

### Linking to Other Pages on the Same Site
 
 (Links to an external site.)

### Relative URLs
- Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
Relative Link TypeSame Folder :To link to a file in the same folder, just use the file nameChild Folder, use the name of the child folder,followed by a forward slash, then the file name.Grandchild Folder Use the name file,then by aforward slash,then the name of grandchild folder followed by another forward slash,then the file name.Parent Folder Use ../ to indicate the folder above the current one, then follow it with the file name.GrandParent Folder Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.

### Summary of links
-  Links are created using the element.
- The element uses the href attribute to indicate the page you are linking to.
 - If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
-  You can create links to open email programs with an email address in the "to" field.
-  You can use the id attribute to target elements within a page that can be linked to.
 


**Layout:**
- **Building Blocks** CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text.
You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too) To separate boxes, you can use borders, margins, padding, and background colors.

- **Containing Elements** If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
It is common to group a number of elements together inside a
(or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation).
The element that contains this group of elements is then referred to as the containing elements.
- **Floating Elements** float
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
Anything else that sits inside the containing element will flow around the element that is floated.
Basics Java Script Instructions:
A script is made up of a series of statements. Each statement is like a step in a recipe.
Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
Variables are used to temporarily store pieces of information used in the script.
Arrays are special types of variables that store more than one piece of related information.
JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
Expressions evaluate into a single value.
Expressions rely on operators to calculate a value.
## FUNCTIONS & OBJECTS BUILT-IN
### function
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).
- Declaring a function
Calling function
- 6 Reasons for Pair Programming
"
- Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making
- Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
- Learning from fellow

Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of
- Social skills

Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities.
- Job interview readiness

A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.
- Work environment readiness 

Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product