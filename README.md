# SPCA - Potential Website Revamp

Using only HTML,CSS and Bootstrap, my project for Code Institute's User Centric Frontend Development looks to revamp Singapore's SPCA(Society for the Prevention of Cruelty to Animals) website. SPCA is a society that mainly promotes affection between humans and animals. The current [website](http://www.spca.org.sg/) is mobile-unfriendly, cluttered with content and information, which might put off potential volunteers, adopters and partners. 
 
## UX

### Concept

In order to cut down on the quantity of content that users have to face, I desire to make a minimalist website, where navigation is clear and simple. For instance, if the user wants to adopt an animal, the user will be able to look at the list of animals available with no more than three clicks. The simplified navigation bar also allows users to easily identify the pages they want to visit. As human eyes read in a Z-shaped manner, I have placed the hero images and call to action buttons in the home page such that:

1. Users will first see a picture of a dog and a girl enjoying the company of each other, transferring the message SPCA wishes to convey to users.
2. Next, they will be able to read the introduction and see the call to action button that promotes adoption of animals.
3. Then, users see the call to action button where users can read stories about the affection between pets and owners, which further promotes SPCA's motto and encourage adoption of animals.
4. Lastly, users will be directed to the image of a dog exploring the forest with its owners, which illustrates the potential bonds between humans and animals. 


### Color Scheme

The colors I have chosen for the website are white, black and gold. White and black were chosen for a minimalist website to make the website look modern, and to appeal to the younger tech-savvy audience. Gold/yellow was chosen for its portrayal of positivity, loyalty, and happiness. I wanted to associate "happiness" with "animals", in order to remind users that animals are lovable creatures.

### Animations

Small animations are added throughout the website to make the pages look lively, as animals are too, lively creatures.

### User Stories

- As a potential adopter, I want to look at the list of animals up for adoption so that I can make a decision to head down personally and adopt it.
- As a potential adopter/volunteer, I want to read some annecdotes about the relationships between humans and pets so that I can be motivated to join SPCA's cause.
- As a volunteer, I want to be able to contact SPCA in order to apply for voluntary work.
- As a donor, I want to be able to contact SPCA to know how I can make donations.
- As a visitor, I want to know the opening hours and address of SPCA's phyiscal location so that I can head over there.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

Before I start on the features of my website project, to avoid confusion, I will like to point out some of the things that won't work and the reasons why.

#### The limited capabilities of HTML & CSS

1. Submitting the contact form and subscribing to the newsletter.
2. The search/filtering features in the adoption page will require javascript.

#### Potential Content
1. Currently, the SPCA (Singapore) does not feature a Spotify page. Thus, clicking on the Spotify icon will not bring the user to a Spotify page. I imagined this to be a potential feature for SPCA to be podcasts sharing tips about pet care or personal stories with other pet owners/lovers.
2. Clicking the tiles on the stories page will not give the user contents of stories to read. Similarly, this is a potential feature that can promote affection towards animals.

### Existing Features

#### Navigation Bar: 

The slightly customised Bootstrap navigation bar has links that takes the user to pages of their interests. The links moves up slightly and gets underlined when cursors are hovered over them. This is to highlight the link that the user is currently at. The navigation bar turns into a hamburger menu in mobile view. Smooth scrolling was also applied to the page, making the page scroll unabruptly when contact us link is clicked in the homepage.

#### Hover Animations: 

I have applied transition hover effects such that buttons and the contact form appear to be 3D. Call to action buttons appear to be pressed inwards when the user click on it (click and hold to see the effect more clearly). Icons/links at the footer will also bounce and get highlighted when hovered over. Cards displaying information about the animals will also scale up in size upon hovering. The story tiles will expand in width and increase in opacity to reveal more of the displayed image when hovered. Some of the hover effects are disabled in mobile view as they wont work on touchscreen-reliant devices.

#### Mobile Friendly: 

To my best knowledge and efforts, I believe that I have ironed out enough bugs such that the website is mobile-friendly.

#### Content: 

With limited time and scope(HTML + CSS) to work on this project, the website will mainly focus on pet adoption, community stories and a way to contact the organisation. The footer features the address, contact no., opening hours, newsletter subscription and social media links(Facebook, Instagram, Youtube, Twitter & Spotify). The adoption page features the option to search by type(see all/dogs/cats) and a button to direct the user to the next page. The story tiles are intended to direct users to a new tab where the stories will be available for the user to read.


### Features Left to Implement
- Shopping page: a page for visitors to purchase merchandises that will contribute to SPCA's funds. The page can include functions such as search, add to cart, make payment, track orders and filtering. 

- Forums: a place for pet lovers and owners to gather and share their views and experiences. The Pet Care and Lost & Found sections of the current SPCA page can be combined and be placed in the Forums.

- Widgets: widgets that display content such as the Google Map or Twitter feed can be considered as additions to the main page.

- For SPCA itself: as mentioned earlier, potential educational podcasts can be released on Spotify and Youtube to spread awareness about animals and the organization.

## Technologies Used
- HTML5
- CSS3
- Bootstrap
- Google Fonts
- Font Awesome
- Visual Studio Code
- Git
- Github
- Google Chrome
- Firefox


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- Much of the content on the main page and adoption page were referenced and paraphrased from SPCA's website.

### Media
- The photos used in this site were obtained from [pexels.com](www.pexels.com).
- The dog, cat and heart shapes were created using Illustrator.
- The custom SPCA logo on the right side of the navigation bar was made using [Hatchful](https://hatchful.shopify.com/).

### Acknowledgements

- I received inspiration for this project from the local [SPCA website](http://www.spca.org.sg/) as mentioned earlier.
