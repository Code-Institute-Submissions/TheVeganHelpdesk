## Testing 

### Validation

 - Required me to remove consecutive hyphens from comments. These appear to be warnings rather than errors (confirmed after a little search through Slack). Comments Shortened.

 - Showed up in the head section, http-equiv had ie-edge instead of ie=edge for the content.

 - The form from Bootstrap had legend as the direct child of a div instead of fieldset. While it was working for me, the validator did not pass this. Legend was changed to 'label' (line 153 in gettingstarted.html, line 149 in localhero.html and line 55 in signup.html)

Declared valid using [Validator.nu](https://html5.validator.nu/) and [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

### First Draft

 - The earlier wireframe was supposed to be the layout for the project. The 'about' sections were being implemented using bootstrap accordion. In practise, while fun, this approach looked cluttered and childish and added nothing of substance to the project. The hero section of the initial wireframe was also too busy, and the Logo was removed. 
This allowed for a total reimagining of the project and the final product is cleaner and clearer.

### Page Layout/Footer.

 - Issues with footer remaining at the bottom of the page. Initial fix was to keep footer fixed to bottom of page. This however stayed at the bottom of the viewport while there was still content to be scrolled. 
 - Position: absolute; bottom: 0; had the footer start at the bottom of the page, but scroll up with the content so that it was blocking part of the content. The solution came from [FreeCodeCamp](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/). Changes to the overall layout of the page, using properly placed containers helped the footer remain where it should be. 
 
 This also helped remove blank space at the right of the page. Commented reference in CSS.

### Image positioning and responsiveness

- First, the images needed to be square in order for the border radius to make them circular and keep them uniform.
- The writing on pages one and two were overlapping with the images when the viewport was reduced. The easiest option here was to keep the images small and increase padding between text and image.
- Style for photos (align-self-centre) did not work for SVG graphics. For this, I used [W3C Schools](https://www.w3schools.com/howto/howto_css_image_center.asp) solution. Commented reference in CSS.
### Favicon error

- Solved after going through Slack thanks to JimLynx_lead answering others' questions on this. Favicon created and added.

### Heading under logoBanner (page 1 and 2)

- Moved up into logoBanner to have a fading background and remove the harsh bottom edge of the hero image.

### Sections page 1 and 2

- Moved headings to separate rows above section for responsiveness reasons.
- Added an offset column for extra large screens so the paragraphs wouldn't be too spread out to read

### Usable form without JavaScript

Sign Up Page Form
- I wanted this to feel like a proper sign up form, however, without JavaScript, there had to be workarounds. I wanted a modal to pop up after submission to indicate success. However, as the sign up was a submit button, the modal would only flash for a second. By changing the button type to button, it leaves the modal open and the user can close as they wish. 
With this workaround, if the user doesn't enter the required fields, the error button shows up through the modal, so i removed the required fields from this form. This is purely for aesthetic reasons. If this was a functioning form, the correct code could be used, with JavaScript, and the required command left in

Modal Forms
- Again, these were just for UX purposes. The sign up button is actually triggering the close button for the modal. Again, completely non-functional, just a UX form.

### Gallery
- Photos did not display captions in mobile format. Removed d-none and d-md-block from carousel-caption div. The caption with the descrition was too big and unnecessary in the mobile format, so I included the d-none and d-md-block into the descriptor part. 

- Also added a span to the heading and description so the background wouldn't stretch futher than necessary.

- Added an extra media query to ensure the gallery is never too big or small. Sized paragraph text for local hero accordingly.

### Color
- in order to soften the color changes between sections, and to not have too much of the same colour on each page, the linear gradient function was used a lot. Consistently at 0 degrees to maintain some uniformity.

### Hover

 - Hover features added to anything clickable. 
---
## UX Testing

Easy to read, uncluttered content. User arrives on home page with gentle convincing reasons to eat more plant-based foods. The only interactivity here is with the navbar and footer, and a single link in the content. All external links open in new tabs.

Next step, getting started. First offer to sign up outside of sign up form appears here. 

Local Hero page. Offers a little more interactivity, can control the gallery, and sign up button advertising 15% off the featured companies products is top of the page. Link to local hero website/media opens in new tab.

Form Page. Short form to fill in, not asking for too much data. Requires consent to be contacted.

Easy to navigate, simple website. Plenty of opportunities to sign up throughout. The user is never overloaded with information. This is a relaxed, experience that will hopefully encourage the user to be happy to reduce their meat and dairy intake if they wish. 