# All Things Space #

All things space is a website which its primary function is to help gain new members to club of space enthusiasts. All things space is a club of space enthusiasts located in the south west of Ireland who meet up on a regular space to share in each others love for space.

Users who visit this website will be able to understand what this club is about , meeting places and also reach out through a contact form and ask any questions they may have. There is also a page showing recent photos taken by club memebers.

![](assets/images/amiresponsivescreenshot.png)

## UX/UI ##

   * A dark template was chosen to sit in with the overall theme of space. Blue tones were also brought in as they went well with the dark images. 
   * I went with orange covered navigational links and headers as I felt they went well with the dark background and the contrast between both worked well.

## Features ##

 * Navigation

    * On the top left hand side of the page is the club name All Things Space. This links you back to the homepage.
    * The others navigational links at the top of the page , Home, Your Images & Contact Us all bring you to those namesake pages.
    * The navigational links use a Google font called Bungee Spice with an orange colour. This style of text has a retro spacey feel about it which compliments the colour theme and gives the user a sense of what this site may be about.
    * The navigational links clearly tell the user where to go on the site and allows the user to navigate quiet easily around the site.

    ![](assets/images/navigational-links.png)

 * Header

    * Featured on the top of the page there is a hero .mp4 video of a the globe spinning. This gives the user a clear idea on what the main topic of the site and club is.
    
    ![](assets/images/screenshotofheader.png)

 * The about us section

    * This section gives some information on what the club is about , when meetings are and on what it is the club does.
    * There is also an image of a man using a telescope just to again emphasize what it is the club is about.     

    ![](assets/images/screenshot-of-about-us-section.png)

 * Where we meet

    * This is a simple embedded Google Maps I-frame giving detailed information on where meetings are held 

    ![](assets/images/screenshot-of-iframe.png)

 * Your Images

    * This is a page showcasing some of the better images taken by members of the space club.

    ![](assets/images/screenshot-of-your-images-page.png)   

 * Contact Us

    * This page allows users fill out a form which gathers their name and email address. It also asks them to send a question. 
    * The form will not send unless all blocks are filled out.
    * Once the form has been sent it directs the user to a thank you page which then re-directs the user back to the homepage. 

    ![](assets/images/screenshot-of-contact-us-page.png)  

* Footer

    * All pages have a footer disaplying the various social media links. This helps drive engagement on our social platforms. 

    ![](assets/images/screenshot-of-footer.png)

# Testing #

   * This site works in different browsers, Chrome , Safari & Firefox

   **Firefox**
![](assets/images/screenshotofheader.png)

   **Chrome**
![](assets/images/chromeimage.png)

   **Safari**
![](assets/images/safari.png)

   * The site is responsive and reacts well to different screen sizes.
   * I confirmed that the navigational links work, are easy to understand and all content text is readable.
   * I confirmed the form does work, each box must be filled otherwise the form will not submit. Also the email field must show a valid email or the form will not send.

**Bugs** 

*Solved Problems*

   * The background in the about us section caused the about us header to become unreadable. Creating a darker backgrouynd solved this
   * On a smaller screen a bit white space formed between the about us section and the main video banner. This was becasue I had a height define for the video and removing this fixed it. 
   * The text in the about us section lost its bullet points on smaller screens. Converting a pixel margin setting to em solved this.

**Validator Testing**

* HTML
   * No errors were retuned when passing through the official W3C validator

```
https://validator.w3.org/nu/?doc=https%3A%2F%2Foconnorian3.github.io%2Fallthingsspace%2Fyourimages.html
```
```
https://validator.w3.org/nu/?doc=https%3A%2F%2Foconnorian3.github.io%2Fallthingsspace%2Fcontactus.html
```
```
https://validator.w3.org/nu/?doc=https%3A%2F%2Foconnorian3.github.io%2Fallthingsspace%2Findex.html
```

* CSS
   * No errors were retuned when passing through the official (Jigsaw) validator

```
https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Foconnorian3.github.io%2Fallthingsspace%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en
```
    
* Accessibility
   * The colours and fonts are easy to read by passing it through the lighthouse in dev tools.

![](assets/images/Lighouthouse-score.png)     

# Deployment #

**The site was deployed to GitHub pages. The steps to deploy are as follows:**
   * In the GitHub repository, navigate to the Settings tab
   * From the source section drop-down menu, select the Master Branch
   * Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

   * The live link can be found here - https://oconnorian3.github.io/allthingsspace

# Credits #

**Content** 
   * The main code for the social media links was taken from the I love running project.

**Media**

   * The video and all images was taken from pexels.com
