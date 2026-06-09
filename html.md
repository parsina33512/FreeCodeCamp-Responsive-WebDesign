#### html:

HTML, which stands for Hypertext Markup Language





#### 0-<!DOCTYPE html>

in <!DOCTYPE html> we believe









#### 1- <h1>your note</h1>

(this becomes the header priority and size 1 of your website in SEO this tells a lot)







#### 2- <h2> your not which is sub header</h2>

(this becomes your sub-header)

+++note we can have multiple sub header while for header we can not have more than one ;









#### 3- then comes the <p>paragraph</p>

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















#### 4-What Are Attributes, and How Do They Work?

An attribute is a value placed inside the opening tag of an HTML element. Attributes provide additional information about the element or specify how the element should behave. Here is the basic syntax for an attribute:



<element attribute="value"></element>



The attribute name is followed by an equal sign (=) and a value in quotes. The value can be a string or a number, depending on the attribute.













#### 4-The <a> element, also known as the anchor element, is used to create hyperlinks. The text between the opening and closing <a> tags is the clickable part users select to navigate.











#### 5/6-src, and alt, or alternative, attribute - which is used to specify the source of an image and provide alternative descriptive text for the image, respectively.











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









#### 7- Link element:

The link element is used to link to external resources like stylesheets and site icons. Here is the basic syntax for using the link element for an external CSS file:

<link rel="stylesheet" href="./styles.css" />



The rel attribute is used to specify the relationship between the linked resource and the HTML document. In this situation, we need to specify that this linked resource is a stylesheet.



It is considered best practice to separate your HTML and CSS in different files. Developers will use the link element for their external CSS file instead of writing everything in the HTML document.



The href attribute is used to specify the location of the URL for the external resource.



The dot followed by a forward slash in the example tells the computer to look in the current folder, or directory, for the styles.css file.



The link element should be placed inside the head element as seen in the following example:









+++It is considered best practice to separate your HTML and CSS in different files. Developers will use the link element for their external CSS file instead of writing everything in the HTML document.







#### 8-What Is an HTML Boilerplate?



It's like a ready-made template for your webpages. Think of it as the foundation of a house. A boilerplate includes the basic structure and essential elements every HTML document needs. It saves you "time" and helps ensure your Fpages are set up properly. Here is an example:



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









#### 9-First, there is the DOCTYPE declaration

It tells browsers which version of HTML you're using. Next, comes the html tag:

<!DOCTYPE html>

<html lang="en">

&#x20; <!--All other elements go inside here-->

</html>

This wraps around all your content, and can specify the language of your page. Inside the html tag, you'll find two main sections - a head, and a body:



<!DOCTYPE html>









#### 10-The head section contains important behind-the-scenes information

Your site's metadata, contained in meta elements, has details about things like character encoding, and how websites like Twitter should preview your page's link. Your site's title, found in the title element, determines the text that appears in the browser tab or window. Finally, you'll typically link your page's external stylesheets in the head section using link elements.













#### 11-the body section is where all your contents go :

<body>

&#x20; <h1>I am a main title</h1>

&#x20; <p>Example paragraph text</p>

</body>













#### 12-What Is UTF-8 Character Encoding, and Why Is It Needed?

UTF-8, or UCS Transformation Format 8, is a standardized character encoding widely used on the web. Character encoding is the method computers use to store characters as data. Essentially, all text on a web page is a sequence of characters stored as one or more bytes. In computing, a byte is a unit of data consisting of 8 bits, or binary digits. UTF-8 supports every character in the Unicode character set - and this includes characters and symbols from all writing systems, languages, and technical symbols. Here is an example of using the meta element with the charset attribute to set the character encoding to UTF-8:



<meta charset="UTF-8" />











#### 13-nesting:

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

You may have seen the target attribute on anchor elements, or links. This important attribute tells the browser where to open the URL for the anchor element.

Enable the interactive editor, click on the link and you will be directed to the freeCodeCamp homepage in a new browser tab.

<a href="https://freecodecamp.org" target="\\\\\\\\\\\\\\\_blank">Visit freeCodeCamp</a>
There are four important possible values for this attribute. Note that each value is preceded by an underscore.

The first value is \_self, which is the default value. This opens the link in the current browsing context. In most cases, this will be the current tab or window.





The second value is \_blank, which opens the link in a new browsing context. Typically, this will open in a new tab. But some users might configure their browsers to open a new window instead.





The third value is \_parent, which opens the link in the parent of the current context. For example, if your website has an iframe, a \_parent value in that iframe would open in your website's tab/window, not in the embedded frame.





The fourth value is \_top, which opens the link in the top-most browsing context - think "the parent of the parent". This is similar to \_parent, but the link will always open in the full browser tab/window, even for nested embedded frames.





There is a fifth value, called \_unfencedTop, which is currently used for the experimental FencedFrame API. At the time of this lesson, you probably won't have a reason to use this one yet.

Selecting the right target value to control where your users end up is an important consideration when creating a website.









## 16-section

The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.













### 17-ul element.

To create an unordered list of items, you can use the ul element



++since it's element it comes with closing tag as well













### 18-li element

The li element is used to create a list item in an ordered or unordered list.

list of items are shown with bullets



++++then it can be used under the <ol> too













### 19-The figure element

Step 25

The figure element represents self-contained content and will allow you to associate an image with a caption.



we can Nest inside figure element.











### 20-figcaption

A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.

Example Code:

<figure>

&#x20; <img src="image.jpg" alt="A description of the image">

&#x20; <figcaption>A cute cat</figcaption>

</figure>













#### 21-em

To place emphasis on a specific word or phrase, you can use the em element.













#### 22-ol

The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.











#### 23-The strong element

The strong element is used to indicate that some text is of strong importance or urgent.

+++ it's some sort of font for texts out there













#### 24-The footer element

The footer element is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.



+++ it comes after main element













#### 25-The title element

determines what browsers show in the title bar or tab for the page.













26-The div element
The div element is used as a container to group other elements.
---

Here is an example of a div element. Add another paragraph element inside of the div element and see the changes in the preview window. To see the previews, you will need to enable the interactive editor.

<div>
  <p>Example paragraph element.</p>
</div>
You will mainly use the div element when you want to group HTML elements that will share a set of CSS styles.



+++For example, if you wanted to divide up your content into sections, then the section element would be more appropriate than a div element.



+++The section element has semantic meaning over the div element which is not semantic. Semantics are the meaning of words or phrases in a language. In HTML, which is a language, elements have their own semantic meaning too. So, this means if you use a section element, the browser will pick up its semantic meaning and understand to treat this as a section - on desktops, mobiles, you name it.
in summary div has no semantic meaning.







#### 27-The id and class attribute

id att adds a unique identifier to an HTML element.

+Browsers will see this space as part of the id which will lead to unwanted issues when it comes to styling and scripting. id attribute values should only contain letters, digits, underscores, and dashes.

++In contrast to the id attribute, the class attribute value does not need to be unique and can contain spaces.

+++So, to recap, when should you use an id versus a class? Classes are best used when you want to apply a set of styles to many elements. If you want to target a specific element, it is best to use id because those values need to be unique.

++If you wanted to add multiple class names to an element, you can do so by separating the names by a space.





28-What Are HTML Entities: < >
to put an < now we can put <img> and it would show as it should without being removed >







29-The script element
The script element is used to embed executable code. Most developers will use this to execute JavaScript code. JavaScript is used to add interactivity to your web pages. Common examples of using JavaScript include interactive games, image sliders, and dynamic forms that validate user input in real-time.





+++While you can technically write all of your JavaScript code inside the script tags, it is considered best practice to link to an external JavaScript file instead. Here is an example of using the script element to link to an external JavaScript file:

<script src="path-to-javascript-file.js"></script>











30-button element

The button element is used to create clickable buttons on a webpage. Buttons are interactive elements that users can click to perform actions.











31-SEO

SEO, or Search Engine Optimization, is a practice that optimizes web pages so they become more visible and rank higher on search engines. One way to improve your site's SEO, is to provide a short description for the web page using the meta element.













### 32-Open Graph

The open graph protocol enables you to control how your website's content appears across various social media platforms, such as Facebook, LinkedIn, and many more. By setting these open graph properties, you can entice users to want to click and engage with your content. You can set these properties through a collection of meta elements inside your HTML head section.



#### The first important OG property to include would be the title.

Here is an example of setting the OG title for the freeCodeCamp homepage:



<meta content="freeCodeCamp.org" property="og:title" />

For the property attribute, you will need to specify that it is og:title. The content attribute is where you will write the title you want displayed for social media sites.



#### The next important OG property would be the type.

Here is an example of using the OG type for the freeCodeCamp homepage:

<meta property="og:type" content="website" />

The type property is used to represent the type of content being shared on social media. Examples of this content include articles, websites, videos, or music.



#### The third important OG property would be the image.

Here is an example of setting the OG image for the freeCodeCamp homepage:



<meta

&#x20; content="https://cdn.freecodecamp.org/platform/universal/fcc\_meta\_1920X1080-indigo.png"

&#x20; property="og:image"

/>

In this example, the open graph image is pointing to the freeCodeCamp logo. All of these images should be high quality with good dimensions and ratios. Most social media platforms will include criteria for image requirements to help you ensure that your content displays well on their site. For example, the developers.facebook.com documentation page states:



"use images that are at least 1200 by 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 by 315 pixels to display link page posts with larger images."



#### The fourth important OG property would be the url.

&#x20;Here is an example of setting the OG url for the freeCodeCamp homepage:

<meta property="og:url" content="https://www.freecodecamp.org" />

There are many more OG properties that you can set, like description, audio, video and locale. However, the open graph url, image, type, and title are the most important ones to include.



So how do these open graph properties affect Search Engine Optimization? When your content is shared on social media, well-crafted OG properties can enhance the appearance for your content in users' feeds. This can lead to higher click-through rates which could signal to search engines that your content is relevant and engaging.







##### an exemplary usage of <a> on img in figure with figcaption as second nested element with target att to \_blank:



<figure><a href="https://www.freecodecamp.org/learn" target="\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\_blank"><img src="https://cdn.freecodecamp.org/curriculum/labs/sea.jpg" alt="Tropical travels are avaiable"></a><figcaption>Tropical Islands</figcaption></figure>  

&#x20;











#### 33.34-HTML Audio and Video Elements

The audio and video elements allow you to add sound and video content to your HTML documents. The audio element supports popular audio formats like mp3, wav, and ogg. The video element supports mp4, ogg, and webm formats.







+++++++++++++++

35-If you want to see the audio player on the page, then you can add the audio element with the <controls> attribute.

==================

+++they come with src and can have href and target too be anchored as well



#### 36- The loop attribute is a boolean attribute that makes the audio replay continuously.

&#x20;

+++loop and control att dont need any value



When it comes to audio file types, there are differences in which browsers support which type. To accommodate this, you can use source elements inside the audio element and the browser will select the first source that it understands. Here's an example of using multiple source elements for an audio element:



<audio controls>

&#x20; <source src="audio.ogg" type="audio/ogg" />

&#x20; <source src="audio.wav" type="audio/wav" />

&#x20; <source src="audio.mp3" type="audio/mpeg" />

</audio>





+++element. This lets you provide the same video in multiple formats, and the browser will choose the first one it can play.



<video

&#x20; controls

&#x20; width="400"

&#x20; poster="https://peach.blender.org/wp-content/uploads/title\_anouncement.jpg?x11217"

>

&#x20; <source

&#x20;   src="https://archive.org/download/BigBuckBunny\_124/Content/big\_buck\_bunny\_720p\_surround.mp4"

&#x20;   type="video/mp4"

&#x20; />

&#x20; <source

&#x20;   src="https://archive.org/download/BigBuckBunny\_124/Content/big\_buck\_bunny\_720p\_surround.webm"

&#x20;   type="video/webm"

&#x20; />

&#x20; Your browser does not support the video tag.

</video>















#### 37-Poster att

For the src, or source attribute, we are using a video called "Big Buck Bunny" from archive.org. If you wanted to display an image while the video is downloading, you can use the poster attribute. This attribute is not available for audio elements and is unique to the video element.









+++++++++++++++++++++++++++++++++++++++++++++++

640x480 640 is the width and 480 is the height , older formats or jpg and PNG while newer and useful one are : WEBP and AVIF

+jpg losses cpmarison data while being redownloaded, it's more trash than other overall

while svg is scaleable vector graphic setting it's values in XML,which is top notch to work with, keep that in mind

+++++++++++++++++++++++++++++++++++++++++++++++







#### 38-SVG element















39-path element

which describes the values of SVG we gonna build















#### 40- d attribute

















#### 41-while width and height come as att inside the svg element



















42-viewBox Attribute
which controls what part of image is visible inside SVG
---

















43-fill attribute
to fill the color of Certain place loke the drawn box in svg







### 







44-iframe element
This element stands for inline frame. It's an inline element used to embed other HTML content directly within the HTML page. That HTML content could be a video, map, another HTML element, or even other web pages.





++++++it's a replaced element just like img. That means it can also take the width and height properties to determine how tall and wide it should be.

















#### 45-beside iframe element we use ALLOW (allow att)

It's like a permission list that tells the browser what features the iframe is allowed to use



Here's an iframe element with the allow attribute:



<iframe

&#x20; allow="accelerometer autoplay clipboard-write encrypted-media gyroscope picture-in-picture web-share"

></iframe>





accelerometer lets the iframe use motion sensors so it can detect things like device tilting and rotation. autoplay lets the video start playing automatically, and clipboard-write lets the iframe write data to the user’s clipboard.



+++also encrypted-media, gyroscope, and web-share

These three will allow the use of encrypted media extensions to protect the video, grant access to the device’s motion and orientation sensors, and allow sharing the iframe content through the device's native share dialogs.





















### 46-another att used in allow : referrerpolicy

&#x20;It is the rule that determines how much detail you share when your page connects to another page.



Add the referrerpolicy attribute and set it to strict-origin-when-cross-origin. This shares the full address on the same site, only the site name on other sites, and nothing on insecure sit



















##### 47-and then there is allowfullscreen att for allow element here(till now , idk about future)















#### 48-Absolute and relative path

+++An absolute path is a complete link to a resource. It starts from the root directory, includes every other directory, and finally the filename and extension. The "root directory" refers to the top-level directory or folder in a hierarchy.



+++If you are linking to a resource on your local machine, use an absolute path, which includes the full directory location of the file.





+++An absolute URL is a complete address used to access a resource. It includes the protocol - which could be http, https, and file and the domain name if the resource is on the web.





Here's how to link to the about.html file with an absolute path:



<p>

&#x20; Read more on the

&#x20; <a

&#x20;   href="/Users/user/Desktop/fCC/script-code/absolute-vs-relative-paths/pages/about.html"

&#x20;   >About Page</a

&#x20;   >







Here's an example of an absolute URL that links to the freeCodeCamp logo:



<a href="https://design-style-guide.freecodecamp.org/img/fcc\\\_secondary\\\_small.svg">

&#x20; View fCC Logo

</a>







##### ++++An absolute path shows the full location of a file within a file system and is commonly used for resources on a local machine. An absolute URL includes access information - such as the protocol and, for web resources, the domain name - which tells the browser how and where to retrieve the resource.







++++A relative path specifies the location of a file relative to the directory of the current file. It does not include the protocol or the domain name, making it shorter and more flexible for internal links within the same website. Here's an example of linking to the about.html page from the contact.html page, both of which are in the same folder:



<p>

&#x20; Read more on the

&#x20; <a href="about.html">About Page</a>

</p>

So imagine you are on the contact.html page, and because the about.html page is in the same place, you simply get the filename. This is an example of using a relative file path.



So, which should you use and when: an absolute path, an absolute URL, or a relative path? Here are the rules you should follow:



Use absolute paths when you want to reference a resource from a fixed location, such as from the root of your site or a known directory on your local machine.



Use absolute URL when linking to a resource hosted on an external website.



Use relative paths when linking to resources within the same website.



Use relative paths if you want to keep your code cleaner and easier to maintain during development.

















#### 49-What Is the Difference Between Slashes, a Single Dot, and Double Dot in Path Syntax?















#### 50-What Are the Different Link States

The first is the default state, which is :link. This state represents a link which the user has not visited, clicked, or interacted with yet. You can think of this state as providing the base styles for all links on your page. The other states build on top of it.





The second state is :visited, which applies when a user has already visited the page being linked to. By default, this turns the link purple - but you can leverage CSS to provide a different visual indication to the user. This is helpful to let someone know they have already read a portion of your documentation. Or, that the site is one they can trust because they have used it before.



The third state is :hover. This state applies when a user is hovering their cursor over a link. This state is helpful for providing extra attention to a link, to ensure a user actually intends to click it.





And finally, we have :active. This state applies to links that are being activated by the user. This typically means clicking on the link with the primary mouse button by left clicking, in most cases. This state can be helpful for showing a user that the element they clicked on is interactive.





51-I element
i is simple italic it's out of use but good to know, it's similar in terms of look to <em>\\





52-<B> element
similar to strong but this one comes when we have a highlighted text no where else while strong comes for strong feelings or emergencies as well





53-<dl> description list

Description lists are perfect for presenting terms and definitions in an organized and easy-to-read format, like in a glossary, or real dictionary, where you can find words with their corresponding definitions.

This is an example of a description list in HTML with two terms and their corresponding details.



<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
  <!-- <dt>JS</dt>
  <dd>JavaScript</dd> -->
</dl>

You will need three HTML elements to define a description list. First, the description list element, dl, which is the container for the entire list. You can see it wraps around all the other elements of the description list in the example.

Then, one description term element, dt, for each term. In this case the description list has two terms, HTML and CSS, so it has two of these elements.

And finally, after each term you will find a description details element, dd, for the description, or details associated with that term. In this example, they are Hypertext Markup Language and Cascading Style Sheets.



























54-blockk quote element :
In HTML, quoted elements are used to distinguish quoted text from the surrounding content. This gives the quoted text a format that is easy to identify.



<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">

&#x20; "Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?"

</blockquote>





+++This element has a cite attribute. The value of the cite attribute is the URL of the source. While this attribute doesn't change the presentation of the block quote, it's very helpful for giving screen readers and search engines more information about the quote. In the browser, you'll see that the text is slightly indented.





+++If you want to start and end the block quote with quotation marks, you may need to write them explicitly within the text. You can write the text directly within the block quotation element, like I just did, or wrap it within one or more paragraph elements. This is helpful when the text has multiple paragraphs, but you want to keep them within the same block quote. Here's an example with four paragraphs:



<blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">

&#x20; <p>Build your projects. Show them to your friends. Build projects for your friends.</p>

&#x20; <p>Build your network. Help the people you meet along the way. What goes around comes around. You'll get what's coming to you.</p>   

&#x20; <p>It is not too late. Life is long.</p>

&#x20; <p>You will look back on this moment years from now and be glad you made a move.</p>

</blockquote>





++++++++++++++++++++++++++++++using the cite attribute to attribute the source of the quotation, but the attribute doesn't really show the source to the user. It only works behind the scenes.







If you want to attribute the source visually, you can add a citation element, cite, outside of the block quotation element. This is different from the cite attribute. The citation element is an HTML element that you can use to mark up the title of a referenced creative work like a book article, song, film, website, or research paper.



example;



<div>

&#x20; <blockquote cite="https://www.freecodecamp.org/news/learn-to-code-book/">

&#x20;   Can you imagine what it would be like to be a successful developer? To have built software systems that people rely upon?

&#x20; </blockquote>

&#x20; <p>—Quincy Larson, <cite>How to Learn to Code and Get a Developer Job \[Full Book].</cite></p>

</div>





54\*-while the quote element itself is <q></q>

you may and better use cite att in it's first row of values : <q cite="whatever.com">what ever</q>







+++++++++++++++++++++++++++++++++++++++++++++What's the difference between block quotes and inline quotes? You should use block quotes for extended quotations from other sources and inline quotes for short quotations from other sources that should be part of existing paragraphs.

























55-abbreviation 

comes in two forms of acronyms and initialisms 

acronyms are outstanding for letter taken from words and formed together as one

while initialisms are first letter of each word put together and at the end their different is that acronym are called as a word while initials are considered a letter even after their assembly 

initialism: html 

acronyms: GUI





+++While you don't necessarily need to use the abbreviation element for every abbreviation on your web page, it's recommended for those that might be unclear and those that might need additional context.



You should use your best judgment to find the right balance between information and presentation to avoid cluttering the text while being clear and concise.





+++you may use title att in your <abbr> element t o improve it's meaning if it's a title of your subject























#### 56-address element 

The address element is versatile and can be used for business pages, author pages, personal sites, and more.



When it comes to building out your website's contact sections, you should use the semantic address element over a generic element like a div.



















57-break element  

<br></br> comes in the middle of your text nce in a while to set different by putting a line where ever it comes :D



Here is an example of using the address element for a company contact page:



<address>

&#x20; <h2>Company Name</h2>

&#x20; <p>

&#x20;   1234 Elm Street<br />

&#x20;   Springfield, IL 62701<br />

&#x20;   United States

&#x20; </p>

&#x20; <p>Phone: <a href="tel:+15555555555">+1 (555) 555-5555</a></p>

&#x20; <p>Email: <a href="mailto:contact@company.com">contact@company.com</a></p>

</address>

In this example, there is the company name, physical address, phone, and email information. For the physical address, the line break element, br, is used to show the division between the street name, city, and country.



For the phone number, we have an anchor element with the href value set for telephone numbers. The tel:+ value inside the href attribute creates a clickable link to initiate a phone call on certain devices that support that.



For the email address, another anchor element is used with the href value set to a mailto link. mailto links are used in HTML documents to allow users to open a new email within their preferred email client.



























58- time element/datetime att

&#x20;time element is used to represent a specific moment in time.



Here is an example using the time element to represent twenty hundred hours, or eight PM in the evening.

<p>The reservations are for <time datetime="20:00">20:00 </time></p>

The datetime attribute is used to translate dates and times into a machine-readable format.



This is important, because it helps with search engine results and helps the browser process date and time information more effectively.



The value for the datetime attribute must be either a valid year, valid month, valid time, local date, global date, or valid duration string.



Here is another example of using the time element to represent a particular date:



<p>

&#x20; The graduation will be on <time datetime="2024-06-15T15:00">June 15</time>

</p>

The value for the datetime attribute is in the ISO 8601 format. ISO 8601 is an international standard to represent dates and times.



The first part of that value is the year, month and day. The capital T in the value is a separator between the date and time.



The fifteen hundred hours would be three PM in the afternoon.



Whenever you need to represent events, publication dates, or appointments, it is best to use the time element.















59-\&mdash; command

\&mdash; is an HTML entity that represents an em dash —., you may use it at the beginning of your text without any <>

















