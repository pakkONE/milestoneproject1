# Moments by Fran

This website aims to reach people who are looking for someone to help them create their special moment/day and make it memorable. 
Whether it is a gift for someones birthday or if it is the bouqeut for their wedding day that they would like to help with - this website will give them assurance that Fran is the person for the job.

Users who visit the site will know what Fran does, see what she has done in the past, and have a chance to get in contact with her if they are interested in her services.

## User stories
<hr>

### _Logo_
- As a visiting user, I want to go to top of the page and therefore click on the logo that leads me there.

### _Navbar_
- Home
  - As a visiting user I want to go to top of the page and therefore click on the Home button.
- Gallery
  - As a visiting user I want to see the past work that Fran has done to help me decide if I want to work with her and therefore click on the Gallery button.
- Get in touch
  - As a visiting user I want to get in touch with Fran so I click on the Get in touch button that leads me to the form.

### _Hero Image_
- As a visiting user I want to know what this website is about so I expect the hero image and its subtitle text to provide me with the answer.

### _Gallery_
- As a visiting user I want to see the past work that Fran has done to help me decide if I want to work with her and therefore scroll through the gallery.

### _Get in touch form_
- As a visiting user I want to get in touch with Fran to get a quote for her work so I submit a form.

### _/confirmed.html_
- As a visiting user I want to know that my form submission was successfully submitted and therefore expect a confirmation message.

### _Footer_
- As a visiting user I want to keep in touch with Fran and follow her on social media platform and therefore expect to find links in the footer of the website that opens them in a new tab.

## Features
<hr>

### __Existing features__

#### _Logo_
- The logo is a clickable link that will bring you back to index.html (or top of the page).

#### _Navigation Bar_
- The navigation bar is fixed and will follow along on top of the page as you scroll down the content. In this way there will always be a call to action with the user seeing the Get in Touch-button at all times.
- The navigation bar is built by using flex and will therefore work really nicely on smaller screen devices.

#### _Hero Image_
- The Hero Image gives a visual background of one of Frans handiworks as well as some subtitles that clearly describes what she does.

#### _Gallery_
- The gallery is built by using the popular masonry style. The content contains images of things that Fran has personally made, whether it is food arrangement, bridal bouquet or the images containing quotes from known people.

#### _Get in touch_
- This form is used as a call to action for the visitor and is placed right after the gallery section. By this time hope fully the user will have a hightened interest for Frans services and now we present them with an option to get in touch with her.
- Each line of the form will be required, except the comment section. This is optional and will give the user an opportunity to let Fran know beforehand what the user is interested in as Fran will reach out to the user.
- Once the user has filled out the form and clicks on the Submit button the user will get a confirmation on the page that the form submission was successful.

#### _Footer_
- The footer will contain important copyright information as well as links to social medias to stay in touch with Fran.
- This is important as most of the new content will be posted on her Instagram.

### __Future features__
<hr>

Here are some the future features I will implement at a later stage. This is due to not having enough information at the moment, nor the skills, or that it would be too much time consuming at this stage of the project.

- Use Bootstrap for responsive navbar.
- Change logo to an actual image, the same as Fran has as a profile photo on Instagram (https://instagram.com/momentsbyfran).
- Remake the gallery and use and API from her Instagram so that each new post she makes gets automatically added. (I will also limit it to a maximum of 20 posts)
- Add more links to social media as they are made available.
- Perhaps make three, or more, separate pages as there's more content available. This is to reduce the amount of data that needs to be load each time you go to the webpage.
- Add a blog section where Fran gets to share stories of how moments she made different moments special and perhaps some behind the scenes content as well.

## Wireframes
<hr>

![This is a desktop wireframe](docs/Milestone%20project%201.png)
![This is a tablet wireframe](docs/Milestone%20project%201%20tablet.png)
![This is a phone wireframe](docs/Milestone%20project%201%20phone.png)

## Typography and color scheme
<hr>

### _Fonts_
- I used Amatic SC in cursive and Playfair Display as fonts

### _Color scheme_
- Color scheme was following: beige: #dbd5c9 grey: #393638 white: #fff black: #000

## Technology
<hr>

### _GitHub_
 - GitHub is where the code is stored and the site was hosted.

### _GitPod_
- GitPod is the developer environment in the cloud.

### _HTML_
- The content of the website is written in HTML5.

### _CSS_
- The website is and its content is designed with CSS3.

## Testing
<hr>

### _Code validation_
- HTML
  - Got no significant errors in [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2F8000-pakkone-milestoneprojec-e6o30ic3ynb.ws-eu38.gitpod.io%2F)
  - I used `"section id=gallery"` on line 45 so that the link button Gallery in the navbar would work.
  - The error on line 85 did not cause any issues on the live website.
- CSS
  - No errors in [(Jigsaw validator)](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F8000-pakkone-milestoneprojec-e6o30ic3ynb.ws-eu38.gitpod.io%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

### Test cases
#### _Desktop_
- What happens when you click on Logo or Home button:<br>
![Desktop Logo/Homebutton](docs/Desktop_Logo_HomeButton.png)

- What happens when you click on Gallery button:<br>
![Desktop Gallery button](docs/Desktop_GalleryButton.png)

- What happens when you scroll through the masonry style gallery:<br>
![Desktop Gallery section](docs/Desktop_GallerySection.png)

- What happens when you click Form button:<br>
![Desktop Form button](docs/Desktop_FormButton.png)

- What happens when you Test filling out the form:<br>
![Desktop Form test](docs/Desktop_FormTest.png)

- What happens when you submit the form:<br>
![Desktop Form confirmation page](docs/Desktop_FormConfirmation.png)

#### _Phone_

- What happens when you click on Logo or Home button:<br>
![Desktop Logo/Homebutton](docs/Phone_Logo_HomeButton.jpg)

- What happens when you click on Gallery button:<br>
![Desktop Gallery button](docs/Phone_GalleryButton.jpg)

- What happens when you scroll through the masonry style gallery:<br>
![Desktop Gallery section](docs/Phone_GallerySection.png)

- What happens when you click Form button:<br>
![Desktop Form button](docs/Phone_FormButton.jpg)

- What happens when you Test filling out the form:<br>
![Desktop Form test](docs/Phone_FormTest.png)

- What happens when you submit the form:<br>
![Desktop Form confirmation page](docs/Phone_FormConfirmation.jpg)

### _fixed bugs_
- Fixed a bug that made the form to become too narrow on smaller screens
- Fixed bug that made an empty margin of circa 20% width to appear on the right of the hero image on smaller screens
- Fixed bug that caused the submit button to appear too big on smaller screens

### _Supported screens and browsers_
- I used Chrome Developer Tool to test the website on all kinds of screen sizes as well in landscape mode.
- The website seem to work well on all screen sizes.

## Deployment
<hr>

### _via GitPod_
- GitPod was used as the environment for development. These are the steps to set it up.
  - I used Code Institute GitPod template (https://github.com/Code-Institute-Org/gitpod-full-template)
  - Click Use this template.
  - GitPod will now set up the environment for you with all addons/shortcuts needed.

### _via GitHub pages_
- The site was deployed to GitHub Pages. These are the steps to make it happen:
  - Go to the relevant repository, then click Settings.
  - Click on Pages on the left column.
  - Under source, pick main and also make sure that /root is selected. Click Save.
  - The site will then be deployed within 10-15 minutes and the link should be shown above the Source section.

Find my site here: https://pakkone.github.io/milestoneproject1/

## Credits
<hr>

### _Images_
- Background for form section - Edward Eyer, [Pexels account](https://www.pexels.com/sv-se/@edwardeyer)
- Hero Image - Trung Nguyen, [Pexels account](https://www.pexels.com/sv-se/@ku3weddinghouse)

### _Code_
- Ideas for code for both HTML5 and CSS3 came from [W3School](https://www.w3schools.com/)

### _Icons_
- Instagram icon for footer came from [Font Awesome](https://fontawesome.com/)