# User Centric Frontend Development Milestone Project

What I have created is a website for a fictional band where the aim is to allow existing fans more access to the band, 
and any potential new fans information on who the band are, and additional options to find out more about them. 

The overall aim of the website is to assist the band in selling more music / tickets to their shows, and gaining new 
fans.

## UX

The aim is as mentioned above, and the website does this well in the way it has been set up. 

As a fan of this band, I want to know where they are touring, so that I can purchase tickets to see them live.  

As someone who has only heard of this band recently, I want to know more about their music, so that I 
can decide if they are a band I want to follow.

As someone who has never heard their music, I want to know what genre they fall under, so I can check to see if they 
are a band I could get into.  

As a new fan of the band, I want to know how I can keep up to date with what the band is doing without having to visit
the website every day.

[Home page + Header - wireframe] (https://github.com/Abelyem/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframe/Section-1.png)

[Tour page - wireframe] (https://github.com/Abelyem/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframe/Tour-Section2.png)

[About-us page - wireframe] (https://github.com/Abelyem/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframe/About-us-Section-3.png)

[Gallery - wireframe] (https://github.com/Abelyem/User-Centric-Frontend-Development-Milestone-Project/blob/master/wireframe/Gallery-section-4.png)

Subscribe for news and updates section - Not initially planned/No wireframe made for this however this was added to the
website to ensure any potential user has the ability to keep up to date, and follow the band with minimal effort 
if intertested in doing so.

## Features 


 ### Existing Features
- Smooth scrolling applied to html - allows page to travel smoothly when any of the navigation options are 
 selected (e.g Tour / About-us / Gallery), as opposed to jumping to the specific section selected.

- Header (fixed top)

   - Has a darker background compared to hero-image which allows the header to stand out, and all 
     information/links provided within to be clearly visible as font-colour is of a lighter colour.

   - Band name clearly visible, and also allows any visitor to the site easy navigation through the 
     site as access to all sections is always easily available (removes need to press ‘back’ or do any 
     additional work to visit a separate section of the site)

   - Social links constantly available for any new visitors to find out more, or existing members to visit 
     the band’s social media/go directly to stream their music via spotify/youtube. Data target set to 
     “_blank” on social links to ensure anyone visiting the site can remain there whilst opening up different 
     links for the bands social media/youtube/spotify. 
  
   - Highlight when hovered - both the navigational links, and the social media links within the header have 
     the hover feature applied which allows them to become a slightly lighter colour when hovered over to indicate
     to any user that they are clickable links. 

- Hero-image and Quote - the image of the microphone and quote within the hero-image quickly shows the website 
   is for a band (for those who are visiting for the first time/have not heard of the band before). For existing 
   fans (and in general for all visitors) the page is kept simple, and clean - not cluttered with information, 
   allows focus to remain on the header for navigation through the site.

- Tour section
   - Ticket links given a different colour (purple) to the rest of the text to indicate they are clickable - 
     also has the same hover feature allowing the link to change colour when hovered over, once again indicating
     that they are clickable links.

   - Date, venue and city all clearly shown in table format . Easy to identify when and where the band will be 
     performing in the future. 

- About-us section
   - Image shown directly below header in black and white / faces of band members not clear - image used to create 
     some mystery around the band members.

   - Information on the band provided directly below the image mentioned above. Also mentions type of music the band 
     makes, as well as links to the band’s first hit record, first album, and most recent album (to provide a general 
     overview as to how the band entered and became well known within the music industry, in addition to how they 
     developed within it (by sharing a link of their most recent album)).  

   - The band’s song and albums referenced  are given the same colour as the ‘Ticket’ links in the ‘Tour’ section of 
     the site, there is also a change of font-weight when hovered over. As this colour has been previously used to 
     indicate that text is a clickable link, this should indicate the same once again - font-weight would also go on
     to further point this out.

   - Video link provided directly below the information on the band - if none of the links were clicked, any user who
     has remained on the website will be able to listen to the band’s music whilst remaining on the site/continuing to
     scroll.

- Gallery section - A few images of the band whilst in action (either performing or preparing a set). 

- News section - allows fans to subscribe with their email address in order to receive any news/updates on the band
    (including but not permitted to future tour dates). The ‘required’ tag also added to the input tag for the email 
    address section to ensure email entered correctly.

- Footer - signals end of page, and also features band name and copyrights 


 ### Features left to implement 
- Subscribe to ‘news/updates’ section shown below ‘About-us’ section - may change background colour of that section 
  so it stands out and is not hidden/missed due to the video placed directly above the subscribe option


## Technologies Used

- Languages used:
   - HTML
   - CSS

- Balsamiq used to create the wireframe for the project: https://balsamiq.com/ 
- Bootstrap used to create mobile friendly navigation links: https://getbootstrap.com/ 

## Testing

### Navigation:

- Home: When clicked returns user to first page where hero-image and quote is visible.
- Tour: Scrolls down to section2 of the site, and to tour section which shows information on tour dates, and venue.
- About us: Scrolls smoothly down to correct section3 of the site where band information is shown.
- Gallery: Scrolls down to section4 of the page - shows gallery images.

All navigation links tested from different starting points (e.g clicked 'Tour' from 'Gallery'/ clicked 
on 'Home' from 'About-us' section etc) to ensure scroll feature works as intended from any and every starting point.

### Social links

- All social links work as intended and lead to their respective sites. Test was carried out on each clickable icon 
  to ensure a new tab is opened each time, as opposed to leading the user off the band website ensuring there are no
  issues with the target being set as "_blank".  

Hover feature fully functioning with a white colour (#fff) being applied across each social icon when hovered over.

### Tour section

- All 'Ticket' links highlighted work as clickable links leading to the website from which tickets can be purchased.
  Ticket links all open in a new tab, and do not steer user off from the band website.
  Hover feature functioning to show a change in colour when any ticket clickable link is hovered over.

- Image below tour section has a transform tag applied which increases size of image when hovered over. This feature
  working as intended, and sized so that any increase in image size does not cover any text (e.g tour-dates inforamtion,
  or the title for the next section (About-us)).

### About-us section

- Song name/album all have amended colours (purple) and font-weight increases when hovered over to make it clear all 
  are cliakable links. As all other links, when clicked they are opened in a new tab as to not lead away from the 
  website.

- Video - song placed below About-us section. Video works without any issues - can also continue to scroll the page
  to the next section without any interruption in video.

### section 5 (email subscription for more band updates section)

- Email placeholder has text decoration which shows a blue colour when selected.
- Email address is set as 'required' in that section, unable to submit without including '@' - when attempting to do this
  as a test, error message pops up advising there is an '@' missing.
- Tested hover feature on subscribe button - working as set, and colour of button changes to purple when hovered over.

## Screensize

- Hamburger menu applied on screensizes 767px and below - this allows navigation to not clutter the header on smaller
  devices.

- A problem encounted on smaller devices was a horizontal scroll which wasn't intentially applied.

- Video under 'About-us' section was too small when being viewed on smaller devices (less than 667px) 
  and so media query was applied to increase width of video when viewing on smaller devices.

## Deployment

The option to create a new repository was provided when logging in to Github - option can also be found on the top 
right hand corner of the page ('+' symbol). After naming the file, and opening said file on gitpod, I was then able
to create new files and folders to hold the different information required (e.g images folder, index.html file, css folder 
+ file etc).

The file was deployed via Gitpages. On Github, I first went to settings then down to Github pages section and selected
the master branch as the source to enable Github pages to run.

In order to run the file locally, you can open the file via Gitpod, then in the terminal search the following command:
'python3 -m http.server' - clicking enter following that command will open a new pop-up on the terminal which gives 
the user the option of 'Make Public', 'Open Preview, and 'Open Browser' - you can click 'Open Browser' to open the 
file locally.


## Credits

### Content

- All content on the site written by me. 

- Information on the music genre for bands Red Hot Chilli Peppers and Linkin Park from:
  - https://en.wikipedia.org/wiki/Red_Hot_Chili_Peppers
  - https://en.wikipedia.org/wiki/Linkin_Park

### Media
 - https://burst.shopify.com/ 
 - https://unsplash.com 
 - https://www.pexels.com/  

### Acknowledgement 

 I received inspiration from the following sites:
 
 - https://francescamusic.com/
 - http://www.decemberists.com/
 - http://www.070shake.net/ 