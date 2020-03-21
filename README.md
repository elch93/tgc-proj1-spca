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

The colors I have chosen for the website are white, black and gold/yellow. White and black were chosen for a minimalist website to make the website look modern, and to appeal to the younger tech-savvy audience. Gold/yellow was chosen for its association with positivity, loyalty, and happiness. I wanted to associate "happiness" with "animals", in order to remind users that animals are lovable creatures.

### Animations

Small animations are added throughout the website to make the pages look lively, as animals are too, lively creatures.

### User Stories

- As a potential adopter, I want to look at the list of animals up for adoption so that I can make a decision to head down personally and adopt it.
- As a volunteer, I want to be able to contact SPCA in order to apply for voluntary work.
- As a donor, I want to be able to contact SPCA to know how I can make donations.
- As a visitor, I want to know the opening hours and address of SPCA's phyiscal location so that I can head over there.



## Features

Before I start on the main features of my website project, I will like to point out some of the things that won't work on this website.

#### The limited capabilities of HTML & CSS

1. Submitting the contact form and subscribing to the newsletter.
2. The search/filtering features in the adoption page will require javascript.

#### Potential Content

1. Currently, the SPCA (Singapore) does not feature a Spotify page. Thus, clicking on the Spotify icon will not bring the user to a Spotify page. I imagined this to be a potential feature for SPCA to be podcasts sharing tips about pet care or personal stories with other pet owners/lovers.
2. Clicking the tiles on the stories page will not direct the user to a web page that contains a story for reading. Instead, I have placed dummy links which will redirect the user to a story post on SPCA's Instagram.

### Existing Features

#### Navigation Bar: 

The slightly customised Bootstrap navigation bar has links that takes the user to pages of their interests. The links moves up slightly and gets underlined when cursors are hovered over them. This is to highlight the link that the user is currently at. The navigation bar turns into a hamburger menu in mobile view. Smooth scrolling was also applied to the page, making the page scroll unabruptly when contact us link is clicked in the homepage.

#### Hover Animations: 

I have applied transition hover effects such that buttons and the contact form appear to be 3D. Call to action buttons("Adopt A Pet" & "Read Tales") will appear to be pressed inwards when the user click on it (click and hold to see the effect more clearly). Icons/links at the footer will also bounce and get highlighted when hovered over. Cards displaying information about the animals will also scale up in size upon hovering. The story tiles will expand in width and increase in opacity to reveal more of the displayed image when hovered. Some of the hover effects are disabled in mobile view as they wont work on touchscreen-reliant devices.

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
- Google Fonts(Heebo)
- Font Awesome(social media icons, map & phone icons)
- Visual Studio Code(IDE for coding)
- Git(for version control)
- Github
- Google Chrome, Firefox(for preview and debugging)



## Testing

### Website Functions

#### Links
Clicking on the logo on the top right of the page will lead you to: [https://elch93.github.io/tgc-proj1-spca/index.html](https://elch93.github.io/tgc-proj1-spca/index.html)

Clicking on the Adopt link on the navigation bar and "Adopt A Pet" button redirects to: [https://elch93.github.io/tgc-proj1-spca/adoption.html](https://elch93.github.io/tgc-proj1-spca/adoption.html)

Clicking on the Stories link on the navigation bar and "Read Tales" button redirects to:[https://elch93.github.io/tgc-proj1-spca/stories.html](https://elch93.github.io/tgc-proj1-spca/stories.html)

Clicking on the Contact Us link on the navigation bar will redirect to: [https://elch93.github.io/tgc-proj1-spca/index.html#contactus](https://elch93.github.io/tgc-proj1-spca/index.html#contactus)

Clicking on the Facebook icon in the footer will open up in a new tab: [https://www.facebook.com/spcasingapore/](https://www.facebook.com/spcasingapore/)

Clicking on the Instagram icon in the footer will open up in a new tab: [https://www.instagram.com/spcasingapore/](https://www.instagram.com/spcasingapore/)

Clicking on the Twitter icon in the footer will open up in a new tab: [https://twitter.com/spca_sg?lang=en](https://twitter.com/spca_sg?lang=en)

Clicking on the YouTube icon in the footer will open up in a new tab: [https://www.youtube.com/channel/UCVupAEb6uU3fFjBdnp6Tobw](https://www.youtube.com/channel/UCVupAEb6uU3fFjBdnp6Tobw)

Clicking on the Spotify icon in the footer will redirect to the main page: [https://elch93.github.io/tgc-proj1-spca/index.html](https://elch93.github.io/tgc-proj1-spca/index.html)

Clicking on any of the story tiles in the Stories page will open up a dummy link in a new tab: [https://www.instagram.com/p/B8yBY3bnZyn/?utm_source=ig_web_copy_link](https://www.instagram.com/p/B8yBY3bnZyn/?utm_source=ig_web_copy_link)

#### Hover Effects/Animations
Links on the navigation bar and footer will float up slightly and get highlighted when hovered.

Call to action buttons will pop up and also depress when clicked (click & hold longer to see the effect more clearly).

A shadow will appear behind the form in the contact us section.

The subscribe(in Home) and next page(in Adopt) buttons behave similarly to the call to action buttons without the depress effect.

The dog, cat and heart shaped icons will appear to be bobbing up and down in the Adopt page.

The search by type function and the next page button will not work in the Adopt page for reasons specified above.

The cards with descriptions of animals will grow bigger in size.

Similarly, the story tiles will grow in width when hovered.

### Mobile Responsiveness

The website is suitable for small(smartphones) to large sized devices(laptops/computers).

### Bugs

A lot of bugs were discovered during the process of making this website but it was a great learning experience and from some mistakes, I had observed and acquired some css tricks. The most challenging aspect I find is to utilise vh, % properly. Being too reliant on these units may cause sizing problems as screen sizes change. To manage that, I tried using minimum or maximum height to limit the size change.

## Deployment

I started out by creating a repository on GitHub with Code Institute's template, and clone it to a folder in my laptop using command prompt. I then code using Visual Studio Code and mostly Firefox for the preview of the website. Commits were pushed to GitHub. The master branch was deployed as a website by GitHub.



## Credits

### Content
- Much of the content on the main page and adoption page were referenced and paraphrased from SPCA's website.

### Media
- The photos used in this site were obtained from [pexels.com](https://www.pexels.com/).
- The dog, cat and heart shapes in the Adopt page were created using Illustrator.
- The custom SPCA logo on the right side of the navigation bar was made using [Hatchful](https://hatchful.shopify.com/).

### Acknowledgements

- I received inspiration for this project from the local [SPCA website](http://www.spca.org.sg/) as mentioned earlier.
