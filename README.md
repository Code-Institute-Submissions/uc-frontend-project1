###Stream One Project: User-Centric Frontend Development - Code Institute

##AIM OF PROJECT:

1. This website is to create a platform for parents to teach young children aged 2+ on Hinduism and the morals of the stories provided. 
2. To provide video learning experience for the children through cartoon and the moral of the story which goes with these.
    - Currently there are not much exposure to Hinduism in foreign countries and sharing the stories through cartoons targets the young showing them some interests 
3. Help the users to learn to from the cartoons and the history of the religion in a fun and exciting way allowing for a better understanding of the subject.
    - There will be 4 stories (currently on this website, more to be added later) 
    - Devotional songs to listen to

##MOCKUPS

- The initial plan for the website had an alternative options placed within them as well. As shown in wireframe folder there are some changes made to suit childrens needs and to make it user freindly. 
- Changes were later created after talking to some parents of young children and viewing children focused webistes. 
    - Final version has merged aaspects which have been shown to be the easiest to use by children without confusing them. 

##UX:

The goal in the design was to make it user friendly for children and to make it easy to use for both parents and children. As a result, I have looked at a minimalist design for the layout. The bright colour scheme was chosen after studying multiple websites aimed at children. 

From the home page I would like to create a brief overview of the aim of the website and parts which will be updated later. In addition to this the website is also child friendly with the use of images and simple languages to provide them with easy access throughout the website. This was decided as there are some children who may not be able to read all the words of the website, therefore, these children can use the help of their parents and use images to recognise where they are on the website. 

There is also an option for both parents and children to leave comments, questions and contact us if they choose to. 

##TECHNOLOGIES:

- HTML5
- CSS
- Bootstrap - v3.3.7
    - Bootstrap CSS used mainly for the pre-defined colour schemes and the button themes 
- Font Awesome - v5.0.10
- Google Fonts 
- Hover.css - v2.3.0
    - This was used to create animation to the buttons.
- Chrome Developer Tools
    - Used extensively for line-testing and running numerous different tasks. Some used are:
        - Website / grid responsiveness
        - Element colours, style, etc.
        - Aligning and centring 
        - Attribute value search 
        - Fluidity and core functionality of the website
- Git / GitHub
    - Used to keep track of the project's evolution with frequent commits and informative messages.
    - GitHub was also used to access bootstrap's source code.
- Cloud 9
    - Used as the main editor 

##FEATURES

- Home page allows the user to select the God/Goddess the children will be looking at 
- Cartoons can be selected by language the parents or the children are most comfortable in watching. 
- The website is written in English however, the videos and songs are in tamil as the aim is to be user friendly for both parents and children globally. 
- The navbar remains collapsed throughout the different screen sizes for a simpler design. 

##FEATURES LEFT TO IMPLEMENT

In the future, I would like to add a working map showing a detailed location of the different ancient temples as well as some information on these locations. 
    - As well as this add options for the website to be viewed in mulitple languages.

##TESTING 

The children friendly user story achieved the intended outcome of providing them with a showcase of cartoons and songs to listen to in the background. In the background section, both the parents and children can both read reading the aim of the website. If this is being viewed on a desktop, the background of the section is a photo of 'Om', however, on smaller devices such as mobile phones only the bright colour is visible. 

If the submit button for both the contact form and the sign up/sign in are invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name', 'email', and 'message' fields. This is so that is the fields are not filled the form will not be able to be submitted. If all the fields are valid, the page will reload. If a parent or child is interested in contacting, leaving a commenting or leaving an enquiry, they will have to complete all fields for the form to go through. 

All links have been manually tested in order to ensure they are all working correctly and leading to the correct destinations.

This site was tested across multiple browsers (Chrome, Internet Explorer, Safari) and on multiple mobile devices (iPhone 4, 5, 7; Samsung Galaxy s8; iPad) to ensure compatibility and responsiveness. 

##Bugs:
- The video pages next / previous / home button did not respond sue to over lay of "video-container"
- In speaking to my tutor he advised on changing in codes in html files. 

- Text in the top half of the video links pages were overlayed by the overview section which followed - this was only visible in mobile views.
- Additional code in html file to bring one section above the other 
    - similar to the video view solution 

- Footer was not working correctly as images of social media were not showing. 
    - Corrected by adding in links used/needed within the HTML5 pages 

##USER STORIES

- The colours attrack the childrens attention and with the toys are attractive for young children. 
    - However, to retain childrens interest need games and interaction tool. 
    - These will be added in later using Javascript. 

##DEPLOYMENT

To run the site <a href="https://lith-visi.github.io/uc-frontend-project1/">Here. </a>

##CREDIT

#CONTENT 

All the content in the English site were written by myself, with alterations made through testings with niece and newphews.  

#MEDIA

All photos were taken from the websites ensuring these are all 'free to use, share or modify, even commercially'.

#ACKNOWLEDGEMENTS

The layouts ideas where gathered from a variety of different sources (as listed below):
- <a href="https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive"> Code Institute exmaples </a>
- The media query for the collapsed navbar regardless of viewport width was taken from <a href="https://www.codeply.com/go/iaM1zcNsQB/bootstrap-navbar-always-collapsed"> Here. </a>
