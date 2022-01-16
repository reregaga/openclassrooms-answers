[Quiz](https://openclassrooms.com/en/courses/6663461-code-an-accessible-website-in-html-css/exercises/3950)
# Create Accessible Interactive Content on a Web Page

## Question 1
**Why is it important to give different types of feedback about interactions to your users?**
- [x] Users may have different needs (visual, hearing, motor).
- [ ] Animations may not work as expected.
- [ ] As a developer, you have to show that you are skilled at different technologies.
- [ ] It improves SEO.

_You want to support different modes of interaction on your site. That means taking into account people who may be using alternative navigation methods, such as a keyboard or switch, and users who perceive the site differently, for example, by using a screen reader._

## Question 2
**What technologies are used to create animations on your site? For example, a dropdown menu?**
- [ ] ARIA takes care of everything! All we have to do is add the right attributes.
- [ ] A server-side language such as PHP, which allows users to open modal dialogs.
- [x] Mainly JavaScript.
- [ ] We can do it directly via CSS. There are indeed specific CSS properties for dropdown menus.

_JavaScript allows you to create animations such as opening a dropdown menu or a modal. The HTML describes the state of the application, and the JavaScript modifies this state._

## Question 3
**Why do you have to use a  label  tag for form inputs?**
- [ ] They allow data to be sent to the server and facilitate their processing in the database.
- [ ] Without them, you can't style the form properly.
- [x] Forms cannot be validated without label tags.
- [ ] Some assistive technologies need them to communicate the purpose of the input.

_Label tags must be present for all inputs because, without them, assistive technologies like screen readers and braille displays can’t communicate the purpose of the input to users._

## Question 4
**How should you indicate that a form field is invalid?**
- [x] By giving visual feedback, i.e., in red, to indicate that the input field has not been filled out correctly.
- [x] By adding a written error message below the input.
- [x] By adding the attribute  aria-invalid="true".
- [ ] By adding the  aria-correct="invalid"  attribute.
- [ ] By adding an HTML attribute  invalid-warning="true".

_It is good practice to provide multiple cues to indicate an error. Color can be effective for drawing attention for some users, error messages give clear information about the error, and an aria-invalid attribute indicates to assistive technologies that the input has not been filled out correctly._

## Question 5
**What are the best practices regarding modals?**
- [x] Hide the content of the document when using a modal.
- [ ] The HTML  modal  tag must be used, otherwise, it will not be compatible with different browsers.
- [x] Your users must be able to use the keyboard to exit a modal.
- [x] The focus should remain within the dialog while it’s open.
- [ ] Only use modal dialogs to display forms.

_When a modal is opened, the user stops interacting with the page and focuses only on the modal content. It’s important to shift focus into the dialog, allow users to use the keyboard to interact with the content and close it, and use the aria-hidden attribute to hide the background content._

## Question 6
**What are the disadvantages of carousels?**
- [x] Moving content can be distracting.
- [x] Users rarely engage with carousel content.
- [x] They don’t create a good user experience for assistive technology users.
- [x] They can be difficult to navigate.
- [ ] They are particularly slow to load.
- [ ] Updating them often requires a lot of work.

_As you saw in the course, carousels can be quite controversial, and research shows that users usually don’t engage with their content. 
As a developer, you may sometimes need to build them anyway, so it will be important to do so in as accessible of a way as possible. 
You have to hide the carousel pages that are not visible to assistive technologies, using the  aria-hidden="true"  attribute or the CSS property  display: none, and make sure that users can stop the content and navigate between the slides with a keyboard._

## Question 7
**Which of these techniques allows you to hide content visually while communicating it to assistive technologies?**
- [ ] Using the CSS property display: none.
- [ ] Using CSS property content: "your message".
- [ ] Using  the HTML attribute aria-sr-only="your message".
- [x] Using CSS rules that are assigned to content through a class.

_You can assign CSS rules that hide the content visually but keep it perceptible to assistive technologies. You can create a dedicated class, for example,  sr-only  or  visually-hidden.
Here is an example of a dedicated class: 
.sr-only {
   position: absolute;
   width: 1px;
   height: 1px;
   padding: 0;
   margin: -1px;
   overflow: hidden;
   clip: rect(0,0,0,0);
   white-space: nowrap;
   border: 0;
}_

## Question 8
**What are the preferred CSS units of measurement for font size?**
- [ ] Pixels.
- [x] Rem.
- [x] Percentages.
- [x] Em.
- [ ] Points.

_It’s better to use relative units over absolute ones because they allow your content to be more responsive and resize in relation to other content on the page. The downside is that absolute values are a bit more complicated to implement. You will often have to be more careful when implementing relative values._

## Question 9
**Should you limit the use of JavaScript in your projects?**
- [ ] JavaScript and accessibility often do not go well together. It is advisable to limit its use.
- [x] Today, most browsers (computer and mobile) support JavaScript well. No reason to avoid it!
- [ ] The main problem is compatibility. Not all browsers support JavaScript well, so it’s better to avoid it as much as possible.
- [ ] Assistive technologies sometimes have trouble understanding DOM updates made by JavaScript. It's not really recommended.

_Limiting JavaScript is referred to as the unobtrusive JavaScript approach, which is less relevant today than it was in the past. Unlike in the past, today, it isn’t easy to do without JavaScript. Plus, it’s generally very well supported!_