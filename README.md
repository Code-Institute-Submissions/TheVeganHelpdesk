# The Vegan Helpdesk
## User Centric Frontend Project - Code Institute
---
A community based website for new and old vegans, people who are interested in starting a vegan lifestyle/diet, or those who wish to try it out once or twice a week for any reasons whatsoever. Features will include
- reasons to try out a plant based diet
- advice on getting started and what to try
- a featured brand specialising in plant based foods
- a sign-up to receive monthly e-zines on new products on the market, community recipes, and the 15% off featured brand (local hero)

---
## Goals
---
This is a platform for people who wish to try more plant based eating, but feel overwhelmed/confused by the info that's out there. The main pages will feature simple reasons and tips to make the move to plant based eating, while the featured brand and e-zine will have more comprehensive tips and ideas.

The end goal will be to build the community and attract brands to purchase space in the e-zine. Therefore, the website will need to highlight how easily achievable going plant based is.

The target customers are:
- people looking to go full- or part-time vegan
- people who are already trying and looking for tips/motivation


## UX

This site is aimed at
- English speakers
- Lives in Ireland (not necessarily, but the aim would be to have local small plant based businesses get feature spots)
- Is preferrably over 18 and can make the choice themself

People who come here are looking for guidance on introducing veganism into their lifestyle

The Helpdesk will be a good place to go because:
- veganism is often seen as extreme or preachy, we will not be
- this will be an inclusive and easy going approach
- there are no requirements in terms of commitments, this is just a guide for the visitor
- the information will be short, sweet and relaxed
- There will be an option to sign up to receive a 15% discount for our local hero every month, as well as an e-zine with recipes and new products available in Ireland.


## The Site - Features

Each page has a responsive navigation bar at the top, which collapses down to a hamburger button and the site name on smaller devices. The footer matches in colour with basic "copyright" info and social links (These lead to the various social media main pages as this company is fictional!) The colors for these were determined using [Encycolorpedia](https://encycolorpedia.com/) and [BrandGradients](http://www.brandgradients.com/). I did not end up using multicolors for the Instagram Logo, but used the linear gradient function I discovered in Brandgradients for many parts of the rest of the project.

There is an over-all colour scheme of cream, green and charcoal, with the green being taken from the main hero image (using the color finder in the developer tools). The local hero page has a different layout and aesthetic, as its focus is to promote a partner company. The hero image becomes the background image to the sign up form.

### 1. Home page

This is an introductory page with a background style hero image, intended not to clutter the header area. There is a small 'headline' to the left of the image. The title of the website will appear only in the browser and nav bars. The page contains typical reasons peeple have for switching to a plant-based diet.

The first is environmental with a visual comparison of the various dietary impacts on the environment. This is purely a visual comparison aid using bootstraps progress bar tool. The information here is based on basic searches regarding the impact of diet on the environment. No one particular source. I have not included numbers on the graph for this reason.

The second and third are animals and health, with accompanying images. All three observe the rule of thirds when viewed in full screen, and condense as the screen gets smaller to a mobile screen where elements take a full col-12 width. This is altered slightly for larger screens, offset on each side by one column to avoid the text spreading out on lines too long to comfortably read.

The Home Page is accessed by both the "logo" and the home button in the Navbar.

### 2. Getting Started Page

This completely follows the home page stylistically. There is a link to sign up in the start slow section of this. Clicking on the sign up link, opens a modal over the page, designed to resemble the main sign up page at the end.

### 3. Local Hero Page

This is a showcase of a local company that is plant-based or environmentally friendly. This page is a little more stylistically neutral. It uses only the cream and charcoal from the color scheme in order to give importance to the featured company. Style here is kept to a minimum and can be easily adapted month on month to suit each new featured company. 

There is a literal hero image in a bootstrap Jumbotron, with a sign up link to the modal again. The jumbotron fades to the charcoal for the next section. 

This is a charcoal background with the Company name as the title, followed by a small blurb about the comapny ad a link to their website/media. This is followed by an easily maintained bootstrap carousel featuring product images for the company.

### 4. Sign Up Page

This features the hero image as a full background for the page. The sign up form contains options for what type of diet the user wishes to follow. Without JavaScript. This form is non functional. Please see testing for the workaround used to make this behave as though it were functional. This is followed by a small responsive 'about' section that follows the layout of the first 2 pages.

### Wireframes

- [Wireframe Page 1](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhhomepagefinal.png) (home page)
- [Wireframe Page 2](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhgettingstartedpagefinal.png) (getting started page)
- [Wireframe Page 3](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhlocalheropagefinal.png) (local hero page)
- [Wireframe Page 4](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhsignuppagefinal.png) (sign up page)
- [Original Wireframe Desktop](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhdesktopfirstdraft.pdf) (draft version)
- [Original Wireframe Mobile](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/assets/wireframes/vhmobilefirstdraft.pdf) (draft version)


---

## Execution
The project was created using:
- HTML 
- CSS
- Bootstrap (including CSS, JavaScript and JQuery scripts) 
- Google Fonts 
- Font Awesome
- [Undraw](https://undraw.co/)
- [Unsplash](https://unsplash.com/)
- [Favicon.cc](https://www.favicon.cc/?)
- [FreeLogoDesign](https://www.freelogodesign.org/)
- [HTML and CSS Formatter](https://webformatter.com/)


Referenced are:
- [Encycolorpedia](https://encycolorpedia.com/)
- [BrandGradients](http://www.brandgradients.com/)
- [FreeCodeCamp](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/)
- [W3C Validation](https://jigsaw.w3.org/css-validator/)
- [HTML5 Validator](https://html5.validator.nu/)
- [W3C Schools](https://www.w3schools.com/)

The page container layout to keep the footer at the bottom was influenced by [FreeCodeCamp](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/).
The navigation bar, sign up form, basic grid layout, modal, carousel, progress bar and accordion were taken from the bootstrap library and then styled using CSS. 

There was to be an introduction to the website above the reasons section in the Introduction as per the Wireframe, but it ended up looking cluttered and a little childish, and ultimately added nothing to the website. There is a small about section added to the final page instead.

The layout of the page past the hero image is constructed using the .row and .col containers from Bootstrap. For small and medium screens, each col will be full width as after various aesthetic tests, this was the tidiest option for a medium screen. In large+ screens, this will observe the rule of thirds: the image/bar chart will take up one third with the text taking two. (in extra large screens, these are offset to avoid the text spreading out too far)

The images files for these needed to be square (as opposed to rectangular) in order to maintain similar dimensions as the corners were curved off to a circle. These were all styled the same way to maintain a visual harmony between elements.

The background colour for each section is comprised of the main cream and green from the website with a linear gradient of 0 degrees, fading from the green of the hero image, to cream, to green, to the cream of the footer. The colours for the bar chart were chosen in order that they would reasonably stand out from the background, while retaining a visual link to the rest of the site.

This was created with a mobile first attitude in mind as I was drawing on Bootstrap. In keeping with this, all CSS is correct for mobile devices first and where necessary, media adjustments are made for larger devices.


See [TESTING.md](https://github.com/Shinners888/TheVeganHelpdesk/blob/master/TESTING.md) for testing info.

## Deployment

This project was developed in [Gitpod](https://gitpod.io/), committed to git and pushed to GitHub.

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

-  Go to github and log into your account.
-  Select [project repository](https://github.com/Shinners888/TheVeganHelpdesk)
-  Above green Gitpod button, select settings, and scroll down to gitpod pages section
-  In source: select master branch and root folder.
-  Hit save. This may then require patient waiting for the site to be deployed!
-  Scroll back down to the GitHub Pages section to retrieve the link to the deployed website. If it is not yet ready, make some tea and wait.

## Cloning the repository

Cloning in Gitpod
- log into your Github account
- go to [this repository](https://github.com/Shinners888/TheVeganHelpdesk)
- click on the green gitpod button (Ensure you have a gitpod account and the gitpod browser extension. Recommended to do this in chrome)
- this will now open a new gitpod workspace using the code in github, for you to work on

Cloning in other IDEs
- go to [this repository](https://github.com/Shinners888/TheVeganHelpdesk)
- beside the green gitpod button, click the 'code' dropdown
- select the HTTPS option and copy the link to your clipboard
- go to your IDE and open the terminal
- type: 'git clone' followed by pasting the copied link, and press enter
- your clone should be created. for troubleshooting, see: [Github docs](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

View [The Vegan Helpdesk]() here
---
## Credits

### - Photos
Limes
- [Photo by Lewis Fagg on Unsplash](https://unsplash.com/photos/nauk28dN79s)

Sheep in field
- [Photo by Luke Stackpoole on Unsplash](https://unsplash.com/photos/sfB_Nw9sggw)

Oats cookies with banana
- [Photo by Monika Grabkowska on Unsplash](https://unsplash.com/photos/7zT-RtY7MxE)

Vegan salad bowl
- [Photo by Anna Pelzer on Unsplash](https://unsplash.com/photos/IGfIGP5ONV0)

Tortoise 
- [Photo by Joel M Mathey on Unsplash](https://unsplash.com/photos/qC_b3XPPUjo)

Heart made out of nuts
- [Photo by Michael Longmire on Unsplash](https://unsplash.com/photos/Y5nVEThyBxQ)

Oreos
- [Photo by Mae Mu on Unsplash](https://unsplash.com/s/photos/oreos)

Vegan Burger
- [Photo by Free to use sounds on Unsplash](https://unsplash.com/photos/q0vYaAcfulM)

Beans
- [Photo by Betty Subrizi on Unsplash](https://unsplash.com/photos/3OqOUrJBgZU)

### - Graphics

SVG graphics come from [Undraw](https://undraw.co/)

### - Favicon 

Favicon image was created using [Free Logo Designer](https://www.freelogodesign.org/) and uses a generic symbol for veganism. This was in turn converted to .ico using [Favicon](https://www.favicon.cc/?).

### - Content

Text was deliberately vague. No actual data was used for the environment chart. 

### - Thanks

I'd also like to thank my mentor Nishant, the folks on Slack for reassurances and making my same mistakes before me!