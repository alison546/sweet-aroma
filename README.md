![alt text](documentation/sweet-aroma-logo.png)

---

# *Sweet Aroma* 

The Sweet Aroma website allows visitors to learn more about the bakery and the products that it offers. This website is targeted to anyone who loves cakes, pastries, and treats for any and every occasion. Visitors can use the contact form to find out more information.

The website can be accessed through this [link](https://alison546.github.io/sweet-aroma/)

![Responsive Mockup](documentation/sweet-aroma-am-i-responsive.png)

---

## Features
### Favicon
* A favicon of a birthday cake is displayed in the tab of the website along with the name.

![Favicon](documentation/sweet-aroma-favicon.png)

### Navigation 
* Featured at the top of the page, the navigation bar shows the name of the bakery in the left corner: Sweet Aroma. If the user hovers over it with the mouse, it will turn from brown to orange, indicating that it is a link and can be clicked. The logo will take the user to the Home Page.
* The other navigation links are to the right: Home, Gallery and Contact which link to the Home, Gallery and Contact pages respectively. 
* The navigation makes it easy for the user to find their way to the different pages of the website.


![Nav Bar](documentation/sweet-aroma-navigation.png)
![Logo Hover Effect](documentation/sweet-aroma-logo-hover.png)

* The navigation bar is responsive
* When users view the website on a mobile phone, the logo is in the center and a hamburger menu appears on the left hand side.
* When the hamburger menu is clicked on, a dropdown menu appears and the links can be accessed

![Index Page Desktop](documentation/sweet-aroma-navigation-mobile.png)

* When the website is viewed on a tablet, the logo and the links appear more centered to accommodate the screen size.

![Index Page Desktop](documentation/sweet-aroma-navigation-tablet.png)

### Home Page
* The Home Page gives information about the company and what it does
* Illustrates the type of products the bakery provides 
* Provides easy navigation to the other links and pages
* The links have a hover effect

![Index Page Desktop](documentation/sweet-aroma-macbook-index.png)



### The Header
* The Header shows a picture of raspberry tarts with a slogan of "Providing you with a slice of heaven". It shows the user  a insight into what they can expect from the bakery.

![Header on desktop screen](documentation/sweet-aroma-header.png)

### The Main Section
* In the main section, there is an about us section which details what the bakery offers customers and underneath there is a "Get in Touch!" button that when clicked on will bring users to the Contact page.
* There is a small gallery which illustrates the products that the bakery offers such as: Fresh Cream Cakes, Fresh Cream Pastries, Treats, Breads and Birthday Cakes.
* A "Back to Top" button allows the user to go back to the top of the page without scrolling.


![About Us section on desktop screen](documentation/sweet-aroma-about-us.png)
![Home Gallery on desktop screen](documentation/sweet-aroma-home-gallery.png)

### The Footer Section
* The footer contains icons for Facebook and Instagram that link to those websites respectively. When hovered over they will increase in size to show they can be clicked on. 

![Footer](documentation/sweet-aroma-footer.png)

### Gallery Page
* The Gallery Page contains the same navigation bar and footer as the Home Page for easy use.
* It also contains a "Get in Touch!" under the introductory message that links to the Contact Page.
* The Gallery contains images of the products that the bakery offers, as well as the prices for each item.
* The Gallery is responsive to the user's screen and will display as appropriate.
* A "Back to Top" is displayed underneath the gallery to allow users to go back to the top of the page.

![Gallery page on laptop screen](documentation/sweet-aroma-gallery-macbook.png)



### The Contact Page 
* The Contact Page has a contact form for users to fill out.
* Each of the input fields has labels of: First Name, Last Name and Email.
* There is a textarea field for the message which is optional
* All the input fields have a required attribute to ensure users fill out these fields.
* The form is responsive on all screens
* The submit button leads to the response page.

![Contact Page on laptop screen](documentation/sweet-aroma-macbook-contact.png)

### The Response Page 
* The response page appears after the contact form is submitted
* It contains a thank you and be in touch shortly message
* It will automatically redirect to the Home page after 4 seconds

![Response Page on laptop screen](documentation/sweet-aroma-macbook-response.png)

---

## Technologies Used 
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML): for building the structure of the website
* [CSS](https://developer.mozilla.org/en-US/docs/Web/css): for used for styling the elements and layout of the website
* [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox): to set items to shrink or grow to fit the space available
* [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid): to make the gallery responsive
* [Gitpod](https://gitpod.io) editor used to write and edit the code
* [Git](https://git-scm.com/): was used for the version control of the website
* [GitHub](https://github.com/): was used to host the code of the website
* [Snipping Tool](https://support.microsoft.com/en-us/windows/use-snipping-tool-to-capture-screenshots-00246869-1843-655f-f220-97299b865f6b): was used to edit and resize images for README file


## Testing 
* I tested this website on the Google Chrome and Microsoft Edge browsers
* I confirmed that the website functions correctly on all screen sizes using Chrome Devtools.
* The different sections of the website are easy to read and understand
* The form works correctly, where the user must fill out the input fields and the submit button works as well.

### Bugs 
* There were no bugs when I deployed my project to GitHub pages

### Validator Testing
* An error occured in the Index page when I passed the code through the W3C Validator
* Error: The element a must not appear as a descendant of the button element.
* I corrected this error by switching by making the button a descendent of the a element
* There was no errors in the CSS when it passed through the CSS Jigsaw Validator
* I confirmed that the colors and fonts chosen are easy to read and accessible by running each page through lighthouse in devtools 
1. Desktop Lighthouse Report - Index
![Index Page Lighthouse Report](documentation/sweet-aroma-index-lighthouse-desktop.png)
2. Desktop Lighthouse Report - Gallery
![Gallery Page Lighthouse Report](documentation/sweet-aroma-gallery-lighthouse-desktop.png)
3. Desktop Lighthouse Report - Contact
![Contact Page Lighthouse Report](documentation/sweet-aroma-contact-lighthouse-desktop.png)

---

## Deployment 
* This site was deployed to GitHub pages. I used the following steps to do so: 
 1. In the [GitHub](https://github.com/alison546/sweet-aroma), click on the Settings tab at the end of nav bar.
 2. On the left sidebar, click on Pages and this will open GitHub Pages.
 3. In the Build and Deployment section, make sure source is set to "Deploy from Branch", "main" is selected and folder is set to "/root".
 4. Click on the save button
 5. Click on the Code tab to go to the repositiory. Wait a few minutes before refreshing the page.
 6. Under Deployments on the right-hand side, click on github-pages.
 7. Click View Deployment to see the live site. [Sweet Aroma](https://alison546.github.io/sweet-aroma/)

 ## Design 
 ### Typography
 * I used the Roboto Google font as the main font for the body for easy readibility of the content.

 ![Roboto font family](documentation/roboto-font-family.png)

 * For the headings and logo, I used the Lobster Google font to grab the viewers attention and it fits very well into the theme of the website.

 ![Lobster font family](documentation/lobster-font-family.png)

 ### Color Scheme 
![Body background color](documentation/body-background-color.png)
![Heading color](documentation/heading-color.png)
![Nav and Footer color](documentation/nav-and-footer-background-color.png)
![Hover effect color](documentation/hover-color.png)

* I used these colours because they are warm colours 

---

## Credits

### Content
* Inspiration for the navigation bar menu and header came from [Love Running](https://alison546.github.io/sweet-aroma/) project 
* Inspiration for the contact form came from [GreatStack](https://www.youtube.com/watch?v=524ycUqs3f0)
* Inspiration for the colour scheme came from [Esty](https://www.etsy.com/ie/listing/1684479465/bakery-website-template-wix-website?gpla=1&gao=1&&utm_source=google&utm_medium=cpc&utm_campaign=shopping_ie_en_ie_-paper_and_party_supplies-paper&utm_custom1=_k_EAIaIQobChMIlNWW5Z7WhwMVyYFQBh2vuQvBEAQYByABEgLJ4fD_BwE_k_&utm_content=go_13703308007_123455828599_530490400750_pla-314261241307_c__1684479465enie_582240817&utm_custom2=13703308007&gad_source=1&gclid=EAIaIQobChMIlNWW5Z7WhwMVyYFQBh2vuQvBEAQYByABEgLJ4fD_BwE)
 
### Images 

The images for this website came from [iStock](https://www.istockphoto.com/), [Pexels](https://www.pexels.com) and [Google Images](https://www.google.ie/imghp?hl=en&ogbl)

* [Hero Image](https://www.supervalu.co.uk/recipe/raspberry-tartlets)
* Gallery on Home Page
    * [Black Forest Cake](https://www.istockphoto.com/photo/black-forest-cake-gm182895267-13945313)
    * [Chocolate Eclair](https://www.istockphoto.com/photo/chocolate-eclair-gm181880715-24671451)
    * [Chocolate Chip Cookies](https://www.pexels.com/photo/macro-photography-of-pile-of-3-cookie-230325/)
    * [Banana Bread](https://www.istockphoto.com/photo/banana-bread-loaf-on-wooden-table-gm1147312072-309428235)
    * [Red Velvet Birthday Cake](https://www.lolascupcakes.co.uk/Ordering/2408/Red-Velvet-Happy-Birthday-Cake.htm)

* Gallery Page 
    * [Black Forest Cake](https://www.istockphoto.com/photo/black-forest-cake-gm182895267-13945313)
    * [Victoria Sponge Cake](https://www.istockphoto.com/photo/two-layer-victoria-cake-with-whipped-cream-strawberry-jam-and-fresh-berries-closeup-gm1477957941-506354570)
    * [Vanilla Swiss Roll](https://www.istockphoto.com/photo/two-layer-victoria-cake-with-whipped-cream-strawberry-jam-and-fresh-berries-closeup-gm1477957941-506354570)
    * [Mojito Cheesecake](https://thebakingexplorer.com/mojito-cheesecake-no-bake/)
    * [Chocolate Eclair](https://www.istockphoto.com/photo/chocolate-eclair-gm181880715-24671451)
    * [Fresh Cream Doughnuts](https://eatmeerecipes.co.za/south-african-desserts/fresh-cream-doughnuts/)
    * [Chocolate Chip Cookies](https://www.pexels.com/photo/macro-photography-of-pile-of-3-cookie-230325/)
    * [Raspberry Tarts](https://www.supervalu.co.uk/recipe/raspberry-tartlets)
    * [Chocolate Croissants](https://www.istockphoto.com/photo/fresh-chocolate-croissants-on-a-plate-gm180824921-24763997)
    * [Danish Pastries](https://www.istockphoto.com/photo/colourful-donut-gm971075570-264526757)
    * [Banana Bread](https://www.istockphoto.com/photo/banana-bread-loaf-on-wooden-table-gm1147312072-309428235)
    * [Sourdough Bread](https://delightbaking.com/the-big-fluffy-round-sourdough-bread/)
    * [Kit Kat Cake](https://www.gracebakery.in/p/kitkat-birthday-cake/birthday-cakes)
    * [Spiderman Cake](https://watchmecelebrate.com/best-spiderman-birthday-cake-ideas/)
    * [Original Birthday Cake](https://ohehirs.ie/product/birthday-original/)
    * [Red Velvet Birthday Cake](https://www.lolascupcakes.co.uk/Ordering/2408/Red-Velvet-Happy-Birthday-Cake.htm)





