[Quiz](https://openclassrooms.com/en/courses/6663451-make-your-web-content-accessible/exercises/3864)
# Assess Accessibility Barriers on the Web

## Question 1
**What is the color contrast ratio for the following text and background?**
- [ ] 3:1
- [ ] 4.5:1
- [x] 4.9:1
- [ ] 6.3:1

_You can check the contrast ratio by using a color contrast analyzer. The contrast ratio between the white text and purple background  is 4.9:1._

## Question 2
**How many heading levels appear on the Wikipedia page on accessibility?**
- [ ] 2
- [ ] 3
- [x] 4
- [ ] 5

_You can check the heading structure of a page by using the HeadingsMap tool. The Wikipedia page on accessibility has four heading levels, H1, H2, H3, and H4._

## Question 3
**A linked image missing alternative text impacts which success criteria?**
- [x] 1.1.1 Non-text content
- [ ] 1.3.1 Information and Relationships
- [ ] 1.3.3 Sensory Characteristics
- [x] 2.4.4 Link Purpose

_Image links that are missing alternative text fail two success criteria. They fail SC 1.1.1, which requires alternatives to non-text content such as images and icons. They also fail SC 2.4.4 because the link destination is not communicated, making the purpose of the link unclear. If you’re using the WAVE tool, you can see the success criteria related to each type of issue on the details page for each of the icons in the Icon Index._

## Question 4
**The following image hides the answer in the alt text description. Based on the alternative text, which of the checkboxes is the best answer?**
- [ ] A is the answer!
- [x] I bet it’s B.
- [ ] C can’t be wrong.
- [ ] Definitely D.

## Question 5
**You can check that a website has unique programmatic page titles by using which of the following methods:**
- [ ] Running an automated accessibility check.
- [ ] Looking at the main heading on the page.
- [x] Looking at the text that appears in the browser tab.
- [ ] Inspecting the HTML  title  attribute of the  &lt;page&gt;  element.
- [x] Inspecting the HTML  &lt;title&gt;  tag in the  &lt;head&gt;  section.

_You can find the programmatic page title by either looking at the text that appears at the top of your browser tab, or by locating the  &lt;title&gt;  tag within the  &lt;head&gt;  section of the HTML code. While the title is often consistent with the main heading on a page, it is not always the case. And an automated checker will only flag an error if a title is missing entirely. It cannot judge whether it’s unique, clear, or properly structured._

## Question 6
**Which of the following information will not come up in automated checks?**
- [ ] Low contrast between text and background.
- [ ] Missing form labels.
- [x] Unclear instructions.
- [x] Misused markup.
- [ ] Incorrect heading structure.

_Automated checkers can’t evaluate the quality or clarity of information. While in some cases they can identify incorrectly structured markup, they cannot check whether markup correctly matches the semantic meaning of content._

## Question 7
**Which of the following success criteria can be tested by navigating a website with a keyboard?**
- [ ] The presence of visible focus and hover indicators.
- [ ] Whether focus targets are sufficiently large for interaction.
- [x] A logical focus order.
- [x] Whether mouse and gesture based interaction can also be performed with a keyboard.

_Testing a site with a keyboard can reveal many accessibility barriers, such as the logical focus order of elements, and whether all functionality, including tasks that typically rely on a mouse or gesture-based interactions, are also available with a keyboard. Testing with a keyboard can identify the presence of visible focus states, but will not test hover states. And the target size of interactive elements is relevant for touch gestures but doesn’t tend to come up during keyboard testing._

## Question 8
**What is the biggest difference between using a screen reader on a mobile device and using a screen reader on a laptop or desktop computer?**
- [ ] Using a screen reader on a desktop allows you to navigate the page by regions, headings, and links while a mobile screen reader does not.
- [ ] Using a screen reader on a mobile device allows you to explore the screen by touch while a desktop screen reader does not.
- [ ] Using a screen reader on a desktop only allows you to perceive the content sequentially while a mobile device allows you to hear items out of order.
- [x] None of the above.

_Both mobile and desktop screen readers allow users to navigate by certain content types, like links, headings, and regions. Although touch based interactions, such as exploring the content by moving your finger around the screen, are more common for screen readers on mobile, they are now also available on many desktop and laptop devices. This type of interaction, called "explore by touch," allows you to hear the content out of order as well, not just sequentially as when navigating with a keyboard._