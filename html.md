html:

HTML, which stands for Hypertext Markup Language





1- <h1>your note</h1> 

(this becomes the header priority and size 1 of your website in SEO this tells a lot)



2- <h2> your not which is sub header</h2>

(this becomes your sub-header)

+++note we can have multiple sub header while for header we can not have more than one ;



3- then comes the <p>paragraph</p>

which is normal text which we may edit later with css







&#x20;+++there are 6 headers in html from h1 to h6 their are used to show the importance of text displayed in you page from 1 the  most imp to 6 the least imp





&#x20;++++ java script makes your page interactive it tells what happens when you click hover or change the volume of your mouse 





(first collective according to above lessons ):

<h1>Welcome to freeCodeCamp</h1>

<h2>Full-Stack Curriculum</h2>

<p>Learn the skills to become a full-stack developer</p>



<h3>Introduction to HTML</h3>sss

<p>HTML represents the content and structure of a webpage</p>



<h3>Introduction to CSS</h3>

<p>CSS is used to style a webpage</p>



<h3>Introduction to JavaScript</h3>

<p>JavaScript adds interactivity to a webpage</p>



4-What Are Attributes, and How Do They Work?

An attribute is a value placed inside the opening tag of an HTML element. Attributes provide additional information about the element or specify how the element should behave. Here is the basic syntax for an attribute:



<element attribute="value"></element>



The attribute name is followed by an equal sign (=) and a value in quotes. The value can be a string or a number, depending on the attribute.



4-The <a> element, also known as the anchor element, is used to create hyperlinks. The text between the opening and closing <a> tags is the clickable part users select to navigate.



5/6-src, and alt, or alternative, attribute - which is used to specify the source of an image and provide alternative descriptive text for the image, respectively.







+++In previous steps, you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.







\*Similar to the href attribute, the src attribute is required because it specifies the image file to be displayed. The alt attribute is not required, but it is recommended for accessibility purposes. Accessibility means making sure that everyone, including those with disabilities, can use and understand things like websites, apps, and physical spaces. You will learn more about accessibility in the upcoming lessons.



righteous format to get up and use img src and href : 



<h1>Welcome XYZ Pet Adoption!</h1>

<p>Consider adopting a pet today. We have cats, dogs, rabbits and more.</p>



<h2>See our cats!</h2>

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch.">



<h2>Adopt a cat!</h2>

<a href="/cats">Visit cats page</a>



<h2>Adopt a dog!</h2>

<a href="/dogs">Visit dogs page</a>









7- Link element: 

The link element is used to link to external resources like stylesheets and site icons. Here is the basic syntax for using the link element for an external CSS file:

<link rel="stylesheet" href="./styles.css" />



The rel attribute is used to specify the relationship between the linked resource and the HTML document. In this situation, we need to specify that this linked resource is a stylesheet.



It is considered best practice to separate your HTML and CSS in different files. Developers will use the link element for their external CSS file instead of writing everything in the HTML document.



The href attribute is used to specify the location of the URL for the external resource.



The dot followed by a forward slash in the example tells the computer to look in the current folder, or directory, for the styles.css file.



The link element should be placed inside the head element as seen in the following example:









+++It is considered best practice to separate your HTML and CSS in different files. Developers will use the link element for their external CSS file instead of writing everything in the HTML document.







8-What Is an HTML Boilerplate?



It's like a ready-made template for your webpages. Think of it as the foundation of a house. A boilerplate includes the basic structure and essential elements every HTML document needs. It saves you time and helps ensure your pages are set up properly. Here is an example:



<!DOCTYPE html>

<html lang="en">

&#x20; <head>

&#x20;   <meta charset="utf-8" />

&#x20;   <meta

&#x20;      name="viewport"

&#x20;      content="width=device-width, initial-scale=1.0" />

&#x20;   <title>freeCodeCamp</title>

&#x20;   <link rel="stylesheet" href="./styles.css" />

&#x20; </head>

&#x20; <body>

&#x20; </body>

</html>









9-First, there is the DOCTYPE declaration:It tells browsers which version of HTML you're using. Next, comes the html tag:

<!DOCTYPE html>

<html lang="en">

&#x20; <!--All other elements go inside here-->

</html>

This wraps around all your content, and can specify the language of your page. Inside the html tag, you'll find two main sections - a head, and a body:



<!DOCTYPE html>









10-The head section contains important behind-the-scenes information

Your site's metadata, contained in meta elements, has details about things like character encoding, and how websites like Twitter should preview your page's link. Your site's title, found in the title element, determines the text that appears in the browser tab or window. Finally, you'll typically link your page's external stylesheets in the head section using link elements.





11-the body section is where all your contents go :

<body>

&#x20; <h1>I am a main title</h1>

&#x20; <p>Example paragraph text</p>

</body>







12-What Is UTF-8 Character Encoding, and Why Is It Needed?

UTF-8, or UCS Transformation Format 8, is a standardized character encoding widely used on the web. Character encoding is the method computers use to store characters as data. Essentially, all text on a web page is a sequence of characters stored as one or more bytes. In computing, a byte is a unit of data consisting of 8 bits, or binary digits. UTF-8 supports every character in the Unicode character set - and this includes characters and symbols from all writing systems, languages, and technical symbols. Here is an example of using the meta element with the charset attribute to set the character encoding to UTF-8:



<meta charset="UTF-8" />











13-nesting:

In the previous step

(

<html>

&#x20; <body>

&#x20;   <main>

&#x20;     <h1>CatPhotoApp</h1>

&#x20;     <h2>Cat Photos</h2>

&#x20;     <!-- TODO: Add link to cat photos -->

&#x20;   <p>Everyone loves cute cats online!</p>

&#x20;   </main>

&#x20; </body>

</html>

)

, you put the h1, h2, comment, and p elements inside the main element. This is called nesting









## 14-Src

The src attribute in an img element specifies the image's URL (where the image is located).







## 15-target attribute 

To open links in a new tab on anchor,The target attribute specifies where to open the linked document. target="\_blank" opens the linked document in a new tab or window.







## 16-section

The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.





### 17-ul element.

To create an unordered list of items, you can use the ul element



++since it's element it comes with closing tag as well 







