[Quiz](https://openclassrooms.com/en/courses/6663461-code-an-accessible-website-in-html-css/exercises/3949)
# Create Accessible Web Pages Using Semantic HTML and ARIA Attributes

## Question 1
**What does "semantic meaning" refer to?**
- [ ] It is a CSS programming paradigm that provides guidelines on how to write good CSS.
- [ ] It is a concept related to databases and their integration in commercial sites.
- [x] It is the ability to give an explicit role to elements through HTML.
- [ ] It is a term related to the concept of "mobile first."

_The use of semantic HTML assigns tags with an explicit meaning or role to content. This includes tags such as navigation, header, footer, table, img, etc._

## Question 2
**What can ARIA attributes do?**
- [x] They make it possible to specify the role of an element (i.e., a search).
- [ ] They allow you to animate content.
- [x] They are used to define the state of an element.
- [ ] They allow you to automatically change the language of the browser.
- [x] They allow you to assign properties, such as labels, to elements.

_According to the W3C, the ARIA attributes can enrich the content of HTML pages. They make it possible to specify the role, state, and properties of an element.
It's recommended to use these attributes within semantic tags to enhance compatibility._

## Question 3
**Which code snippet below is the most accessible?**
- [ ] &lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
   &lt;meta charset="UTF-8"&gt;
   &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
   &lt;title&gt;Tonight In Gotham - OpenClassrooms&lt;/title&gt;
 
   &lt;link rel="stylesheet" href="./css/normalize.css"&gt;
   &lt;link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet"&gt;
   &lt;link rel="stylesheet" href="./css/app.css"&gt;
&lt;/head&gt;
&lt;body&gt;
   &lt;div class="header"&gt;
       &lt;div class="main-nav"&gt;&lt;/div&gt;
   &lt;/div&gt;
   &lt;div class="content"&gt;
       &lt;div class="inner-page-navigation"&gt;
       &lt;/div&gt;
       &lt;div class="section"&gt;
       &lt;/div&gt;
   &lt;/div&gt;
   &lt;div class="footer"&gt;
       &lt;div class="footer-nav"&gt;&lt;/div&gt;
   &lt;/div&gt;
&lt;/body&gt;
&lt;/html&gt;
- [ ] &lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
   &lt;meta charset="UTF-8"&gt;
   &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
   &lt;title&gt;Tonight In Gotham - OpenClassrooms&lt;/title&gt;
 
   &lt;link rel="stylesheet" href="./css/normalize.css"&gt;
   &lt;link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet"&gt;
   &lt;link rel="stylesheet" href="./css/app.css"&gt;
&lt;/head&gt;
&lt;body&gt;
   &lt;header class="header"&gt;
       &lt;nav class="main-nav"&gt;&lt;/nav&gt;
   &lt;/header&gt;
   &lt;main class="content"&gt;
       &lt;div class="inner-page-navigation"&gt;
       &lt;/div&gt;
       &lt;section class="section"&gt;
       &lt;/section&gt;
   &lt;/main&gt;
   &lt;footer class="footer"&gt;
       &lt;div class="footer-nav"&gt;&lt;/div&gt;
   &lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;
- [x] &lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
   &lt;meta charset="UTF-8"&gt;
   &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
   &lt;title&gt;Tonight In Gotham - OpenClassrooms&lt;/title&gt;
 
   &lt;link rel="stylesheet" href="./css/normalize.css"&gt;
   &lt;link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet"&gt;
   &lt;link rel="stylesheet" href="./css/app.css"&gt;
&lt;/head&gt;
&lt;body&gt;
   &lt;header class="header"&gt;
       &lt;nav aria-label="main navigation" class="main-nav"&gt;&lt;/nav&gt;
   &lt;/header&gt;
   &lt;main class="content"&gt;
       &lt;nav aria-label="inner page navigation" class="inner-page-navigation"&gt;
       &lt;/nav&gt;
       &lt;section class="section"&gt;
       &lt;/section&gt;
   &lt;/main&gt;
   &lt;footer class="footer"&gt;
       &lt;nav aria-label="footer navigation" class="footer-nav"&gt;&lt;/nav&gt;
   &lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;
- [ ] &lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
   &lt;meta charset="UTF-8"&gt;
   &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
   &lt;title&gt;Tonight In Gotham - OpenClassrooms&lt;/title&gt;
 
   &lt;link rel="stylesheet" href="./css/normalize.css"&gt;
   &lt;link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet"&gt;
   &lt;link rel="stylesheet" href="./css/app.css"&gt;
&lt;/head&gt;
&lt;body&gt;
   &lt;header class="header"&gt;
       &lt;div class="main-nav"&gt;&lt;/div&gt;
   &lt;/header&gt;
   &lt;main class="content"&gt;
       &lt;div class="inner-page-navigation"&gt;
       &lt;/div&gt;
       &lt;div class="section"&gt;
       &lt;/div&gt;
   &lt;/main&gt;
   &lt;footer class="footer"&gt;
       &lt;div class="footer-nav"&gt;&lt;/div&gt;
   &lt;/footer&gt;
&lt;/body&gt;
&lt;/html&gt;

_Answer 3 is the correct answer. It identifies the role of each navigation menu and also uses semantic HTML tags._

## Question 4
**How can you use CSS for accessibility?**
- [ ] Unfortunately, CSS has no impact on accessibility. It is of no use in this respect.
- [ ] There are CSS properties dedicated to accessibility such as  for:accessibility  and  html:accessibility.
- [ ] JavaScript makes sites accessible, not CSS.
- [x] By using pseudo elements such as :hover, :focus, and :visited.

_Although CSS does not impact the use of assistive technologies such screen readers, it can help other users by providing visual cues, for example by using :hover and :focus properties for interactive elements._

## Question 5
**How would you indicate that a page is the current page to assistive technology users?**
- [x] Using the  aria-current  attribute.
- [ ] By adding the  current-page  attribute.
- [ ] By changing the link address.
- [x] By adding text visible only to assistive technologies.
- [ ] You don't have to do anything, HTML does it automatically.
- [ ] By adding the  the-current-page-is  attribute.
- [ ] None of the above.

_Two methods are possible to indicate the current page. You can either use the  aria-current="page"  attribute, or place text in a span and hide it visually._

## Question 6
**What are the techniques to make a dropdown menu accessible?**
- [ ] It is not possible to make a dropdown menu accessible. You can't use this type of interaction.
- [x] You have to use the  aria-haspopup  and  aria-expanded  attributes to describe the state of the dropdown menu and its control.
- [ ] You must use the  aria-dropdown-menu  attribute. It has the advantage of being self-managed.
- [ ] This can be done in the CSS via the  dropdown  property.

_A dropdown menu requires two ARIA attributes:  aria-haspopup  and  aria-expanded  . These allow you to define the interaction and state of the menu. You can take a look at our "Tonight in Gothman" project for more information._

## Question 7
**Why is it important to give visual feedback for links and menu navigation?**
- [ ] Assistive technologies are able to understand the links and will translate them for all users.
- [ ] It doesn't matter for accessibility. It's more visual enhancement than anything else.
- [x] Because it makes it easier for everyone to interact with the page elements by understanding the current state of interactive elements.
- [ ] This is useful for search engines. Giving visual feedback allows them to browse our site well.
- [x] Keyboard users need a visual indicator to see what element of the page they are interacting with.

_Visual cues help everyone to better understand what elements are interactive and what is currently in focus or hovered over. They are especially important for keyboard users who don’t rely on a pointer such as a mouse cursor._

## Question 8
**Is it good practice to make tables with  div  tags on a web page?**
- [x] No, because a div tag has no semantic meaning.
- [ ] No, because a  div array is particularly difficult to integrate with CSS. The table tag and its associated tags offer more flexibility.
- [ ] No, because a div table does not support a mobile format.
- [ ] Yes, div tables should be used instead of the  table  tag, which is reserved for emails.

_As you have seen throughout the course, a  div  tag has no semantic meaning and does not provide information about the type of content. It also does not allow header cells to be associated with content cells._

## Question 9
**How can you specify if a table header cell is associated with a row or a column?**
- [x] With the scope attribute and the values  row  and  col.
- [ ] By specifying a reading direction using the dir attribute and the values  horizontal  and  vertical.
- [ ] You can't associate headers and cells programmatically. Assistive technologies do it for us.
- [ ] With the  caption  tag.

_The  th  tag combined with the scope attribute allows to define the content that is associated with a particular header. This is especially useful if your table has several reading directions (horizontal and vertical)._

## Question 10
**Why and how should subtitles be included in a video?**
- [ ] You don't need to include subtitles. The  video  tag adds them by default.
- [ ] To allow people who are deaf or hard of hearing to understand the content. We can use the  text  tag to add captions.
- [x] To allow people who are deaf or hard of hearing to perceive the content. The  track  tag is used to add captions.
- [ ] To allow search engines to understand the content. The  caption  tag is used to add captions.

_Captions help users who are deaf or hard of hearing to perceive the audio in videos. The  track  tag can be used to link a video with a caption file._