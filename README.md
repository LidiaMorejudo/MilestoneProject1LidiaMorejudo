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

These are the erros found in the Gallery page:<br>

![ Warnings](/assets/img/HTMLcodeerrorsgallery.png)
<br>

1. The error <strong>Bad value image/x-ico n for attribute type on element link: Expected whitespace or a semicolon but saw n instead. In this case I used the incorrect type attribute, it should be /img instead of icon. I have now updated this in the code for the Gallery page.</strong>

2. The second and third error Bad value <strong>assets/img/Gigs 2022.jpeg for attribute src on element img: Illegal character in path segment: space is not allowed</strong> refers to the extra space in the name of the jpg file. I changed the name on the jpg file and then updated the line in the HTML code to Gigs2022.



<strong>Deployment<strong>
<br>
I deployed the project using Github. This is what I did to deploy it:<br>

1.	I logged in to my GitHub Repository.<br>
2.	Then went to 'Settings'.<br>
3.	In 'Settings' I selected 'Pages'.<br>
4.	Found 'Source' and selected 'None' in the dropdown menu and then 'Main Branch'.<br>
5.	After the page was refreshed the life link appeared in the 'GitHub Pages' section. <br>

<strong>MEDIA, CONTENT AND SUPPORT<strong><br>

Here will go information about media, content and support.




