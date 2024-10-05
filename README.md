# MilestoneProject1LidiaMorejudo
Kiss Me Killer 

PURPOSE OF THE WEBSITE
<br>
Kiss Me Killer’s official website is a dynamic online hub designed to connect fans, prospective clients, and music enthusiasts with the electrifying world of this pop-funk-heavy music band. The website serves as a comprehensive resource, keeping fans informed about upcoming gigs and events, showcasing vibrant images and videos, and offering a seamless platform for booking inquiries. With a focus on engaging content, including music samples and exclusive behind-the-scenes glimpses, the site not only keeps the band's loyal followers updated but also attracts new listeners eager to discover Kill Me Killer's unique sound.
<br>

VALUE FOR THE USERS
For event organizers and clients looking to add a burst of energy and groove to their events, the website provides an accessible and user-friendly experience for exploring booking options. The combination of captivating visuals, detailed event information, and an easy-to-use contact form ensures that both fans and potential customers can effortlessly engage with the band. Whether you're a long-time supporter or a new listener, the Kill Me Killer website offers an all-encompassing platform to experience the essence of their music and connect with the band like never before.
 <br>
 This is an image of the actual home page
![ Images from the Website](/assets/img/IntroductionWebsite.png)

These are the planning stages on the Wireframes of the Home page:

![ Wireframes](/assets/img/WireframeHome1.png)

This shows the planning on how it would look in smaller screens:

![ Wireframes](/assets/img/WireframeHome2.png)


Features
Existing Features
•	Navigation Bar
o	Featured on each of the four pages, the full responsive navigation bar includes links to the Home page, Gallery, Book us and Gigs pages and is identical in each page to allow for easy navigation. Furthermore, the logo is also present on each page on the left top side and this also links to the home page for easy navigation.
o	Thanks to the navigation bar and the logo link, users can easily navigate through the different sections of website across all devices without having to use the back button.
 
![ Images from the Website](/assets/img/NavigationbarKissMeKiller.png)

•	The landing page image
o	The landing page includes several pages of the band. First, the user is greeted by a picture of the band in full playing with a text introduction under it. 
 
![ Images from the Website](/assets/img/LandingPageImage.png)


•	Members of the Band section
o	Below the main image and brief history of the band. The visitor will see individual pictures of each of the band members with a brief introduction to each player and their personality.
o	This section will help the visitor get a better understanding of the motivations and style of each member, and hopefully get a flavour of what the band will be like if they are new to it, or get a glimpse into their favourite band member’s styles and personalities for fans.
 
 ![ Images from the Website](/assets/img/Landingmembersband.png)

•	The Footer
o	The footer section includes links to the relevant social media sites for Kiss me Killer. The links will open to a new tab to allow easy navigation for the user.
o	The footer is valuable to the user as it encourages them to keep connected via social media
 
![ Images from the Website](/assets/img/Footer.png)

•	Gallery
o	The gallery provides images from members of the band in different situations, as well as posters. There are six images in total, and at the top they all appear in a carousel. 
o	This section provides the users and fans with more visual input into the band and what their performances are like. 
 
 This is an image of the Gallery page:

![ Images from the Website](/assets/img/Gallery.png)

This is the planning Wireframe for the Gallery page:

![ Images from the Website](/assets/img/WireframeGallery.png)

•	The Book-up Page
o	This page provides information of the different packages available for events. It also allows the user to send a booking request for their special event. There are specific fields set up so the band receives the information needed to see if the event is possible, and also a box for custom text so the user can submit additional information. 

These are two images from the actual Booking us page:

![ Images from the Website](/assets/img/Bookingpagepackages.png)

![ Images from the Website](/assets/img/Bookingpageform.png)

This is the wireframes stage of the planning:

![ Images from the Website](/assets/img/WireframeBookingform.png)

Gigs
In the gigs page, site visitors can find information of upcoming events and gigs. Other pictures of the band are placed next to the text, and there is also a video that the band recorded and is publically available in YouTube. This is to provide the visitors a more in depth experience of the band and their music.

This is an image of the final gibs pages:

![ Images from the Website](/assets/img/Gigs.png)

This is the wireframes planning stage:

![ Images from the Website](/assets/img/WireframeGigs.png)

Future features:
•	A feature that would be good to implement in future would be a booking system for the gigs for the band.
•	Another feature would be a page where the band can present their merchandaise and accept orders for it.


<strong>Testing</strong><br>
<strong>TESTING INDEX PAGE</strong><br>

I used the validator <strong>https://validator.w3.org/<strong> to test the HTML with the live link: <strong>https://lidiamorejudo.github.io/MilestoneProject1LidiaMorejudo/</strong><br>

Once the live link put in the box and I clicked enter, 13 warnings and errors appeared. The first ones I dealt with were the warnings.<br>

![ Warnings](/assets/img/HTMLcodewarnings.png)
<br>
1. The first warning was informing that the HTML document was missing the language tag. So, I added this in all pages. <br>

2. The second was an advisory more than a warning. It was a reminder that the trailing slash / at the end of selfclosing elements is not needed in HTML5. I have removed this slash. <br>

3 ot 5 These warnings advise me that there is no heading in the sections mentioned. However, the first section contains the image of the band and the main heading for the page is on another section. I don't want another heading for this image. Therefore, I am not adding another header. I don't want a specific header for the other sections either.

This image shows the errors found by the checker in the index page.<br>

![ Errors](/assets/img/HTMLcodeerrorsindex.png)

6 and 7. This error reminds me that I have closed the nested tags in the incorrect order.I had an "i" tag inside the "a" tag, but I had closed he "a" tag first, leaving the "i" tag outside incorrectly. I have corrected this now in the index page an other pages as this was in the footer with the social media links. <br>
The error in line 7 is related to the previous one <strong>No i element in scope but a i end tag seen.</strong> As the a element and the i element were in the wrong order, it looked like the i element did not have a corresponding opening i element.<br>
Erros 8 to 13 are the saem as 6 to 7, as these refer to the lines of code in the footer for the social media icons, which are the same code but with different links for differnet social media platforms.<br>

<strong>TESTING GALLERY PAGE</strong><br>

These are the errors found in the Gallery page:<br>

![ Warnings](/assets/img/HTMLcodeerrorsgallery.png)
<br>

1. The error <strong>Bad value image/x-ico n for attribute type on element link: Expected whitespace or a semicolon but saw n instead. In this case I used the incorrect type attribute, it should be /img instead of icon. I have now updated this in the code for the Gallery page.</strong>

2. The second and third error Bad value <strong>assets/img/Gigs 2022.jpeg for attribute src on element img: Illegal character in path segment: space is not allowed</strong> refers to the extra space in the name of the jpg file. I changed the name on the jpg file and then updated the line in the HTML code to Gigs2022.

3. There are also warnings about headers. However, in this section I am not including a header as I just want pictures of the band.

TESTING THE GIGS PAGE

These are the errors and warnings encountered:

![ Warnings](/assets/img/HTMLcodeerrorsgigs.png)

1. This is the same error that appeared before in the other page in the header, and I had forgotten to update it in all pages. The image used for the imaticon is a png, not "icon", so I have changed it to PNG. 

2. I had an extra tag in line 42, effectively opening two divs, but only closing one. I have deleted one of them now.

3. One of the erros indicate that the frameborder attribute has been deprecated in HTML5, so I had to change this setting for CSS, setting the frame border to none.

TESTING THE BOOKUS PAGE

These are the errors and warnings encountered:

![ Warnings](/assets/img/HTMLcodeerrorsbookus.png)

1. There is an extra <br> inside the select element, which shouldn't be there. I have deleted it now.

2. The second error refers to the list in the form for the venues. As I hadn't added an empty item in the list, the one selected by default was the first item in the list "weddings". I have added another item, so the user has to select one of the items from the list and the item "wedding" is not selected by default.

After checking with my tutor, I was advised that it would be preferable if the details entered on the form were cleared after the user clicked on submit. So, I looked up how I would do this. I ended up with a short Javascript script.

In this script, the different components do the following. There is an event listener, which is  ID "bookingform". It listens for a "submit" event, which is when the user clicks on the submit button.

Although for this project the data entered in the form won't go anywhere, i.e. I don't have a database or a server for this, it seems important in include an event in the script that prevents the browser from carrying out the default behaviour for this type of form, which would be reloading the page or sending the form. event.preventDefault(). If this were not included, the form would still not send the information to a server, as there is no server, however, the Alert message might just appear and disappear quite quickly, and the user might miss it. So, by using this event to prevent the default behaviour, the alert message will appear clearly for the user to understand their data has been "sent". 

The alert Message displays a pop-up to thank the user for their submission and this item of script this.reset() resets the form fields, clearing any text or selections made by the user, bringing it back to its default state.

As now the alert message is on the Java Script the "onclick" event in the HTML is not needed. I have taken it off. 

CHECKING ERRORS IN CSS

I used the WW3 CSS validator to check for errors: https://jigsaw.w3.org/css-validator/. I checked the four pages on the validator and it did not find any errors.



<strong>Deployment<strong>
<br>
I deployed the project using Github. This is what I did to deploy it:<br>

1.	I logged in to my GitHub Repository.<br>
2.	Then went to 'Settings'.<br>
3.	In 'Settings' I selected 'Pages'.<br>
4.	Found 'Source' and selected 'None' in the dropdown menu and then 'Main Branch'.<br>
5.	After the page was refreshed the life link appeared in the 'GitHub Pages' section. <br>

<strong>MEDIA, CONTENT AND SUPPORT<strong><br>

MEDIA

All the pictures, the video and logo used for the website were provided by the band members. They were shared with me freely.

Only the Favicon was obtained from a free online library of images.

THE CONTENT

The content is based on the actual band type of music preferences, however, the descriptions used for the band members and the band are not their own and were made up for this exercise. 

The information about past and upcoming gigs and the venues was made up for this exercise.

SUPPORT

Here will go information about media, content and support.
I used https://www.w3schools.com/ as a reference to check code in HTML and CSS, and refresh my memory on how to do certain things in code and what tags are needed for what purposes. For instance, to add a message so users are reassured their message has been received when clicking the button to join the mailing list or to send the information form, I check www.w3schools.com and found the tag onclick="alert('Hello World!')" which I modified with my own message.

I also used the w3 validators to check if there were any errors in HTML and CSS.

I used Chat GPT to ask questions about things I did not understand. For instance, the w3 validator is good, but some of the explanations for the errors were difficult to understand if you are starting in coding, so I asked Chat GPT what it meant. I found this useful as the AI explained it with examples. This helped me to fix the errors.

I have also found ideas and answers to queries in the forums of https://stackoverflow.com/. 



