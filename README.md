Software Requirements Specification
for
Blakes Portfolio website
Version 1.02 approved
Prepared by blake
NMIT
31/8/2025
 
Table of Contents
Table of Contents	ii
Revision History	ii
1.	Introduction	1
1.1	Purpose	1
1.2	Document Conventions	1
1.3	Intended Audience and Reading Suggestions	1
1.4	Product Scope	1
1.5	References	1
2.	Overall Description	2
2.1	Product Perspective	2
2.2	Product Functions	2
2.3	User Classes and Characteristics	2
2.4	Operating Environment	2
2.5	Design and Implementation Constraints	2
2.6	User Documentation	2
2.7	Assumptions and Dependencies	3
3.	External Interface Requirements	3
3.1	User Interfaces	3
3.2	Hardware Interfaces	3
3.3	Software Interfaces	3
3.4	Communications Interfaces	3
4.	System Features	4
4.1	System Feature 1	4
4.2	System Feature 2 (and so on)	4
5.	Other Nonfunctional Requirements	4
5.1	Performance Requirements	4
5.2	Safety Requirements	5
5.3	Security Requirements	5
5.4	Software Quality Attributes	5
5.5	Business Rules	5
6.	Other Requirements	5
Appendix A: Glossary	5
Appendix B: Analysis Models	5
Appendix C: To Be Determined List	6


Revision History
Name	Date	Reason For Changes	Version
Blake	31/8	Initial creation	1.01
	3/9	Minor changes to functional specs	1.02


 
1.	Introduction
1.1	Purpose 
The purpose of this document to provide technical information in relation to the development and creation of Blake’s portfolio website. The purpose of the website is for blake to have a platform to promote his projects, skills, and provide a means for contact for users who many want to contact or recruit blake.

The purpose of this website is to allow blake a platform to showcase his skills sets and projects to potential employers, and also allow for people to contact blake for collaboration for projects.
1.2	Document Conventions
Important conventions in this document:

HMTL – hypertext markup language. This will be the language used for the creation of the website
CSS – cascading style sheets. This is the language use along side of HTML to provide fidelity and visual features
HTTPS – hypertext transport protocol secure. This allows HTML and other communications to go across the internet to be encrypted.
1.3	Intended Audience and Reading Suggestions
This document is intended to be read by users needing to develop further features on the website, 
And for Blakes teachers to read through to understand the requirements of his project
1.4	Product Scope
The scope of this project is the a static website for blake, which will contain 4 webpages.
2.	Overall Description
2.1	Product Perspective
This website will be a standalone static website which will be hosted onto a webserver to be publicly visible, as of current the HTML and CSS created is created statically and needs to be locally run for it to be seen. The final product will involve a website which is public facing
2.2	Product Functions
Show users photos and links of Blake’s projects:
Allow users to enter contact information if they wish to contact blake
The website will allow users to navigate between pages using hyperlinks and navigation bars.

2.3	User Classes and Characteristics
Blake / owner :

Will use the website to update information on it.
and check any emails left by the contact page

Users / vistiors:

Will use the website to understand Blakes skills better,
And leave their information in the contact page
2.4	Operating Environment
Currently the website is locally run for the purpose of development, but a working branch has been hosted onto GitHub pages.

using an index file to redirect 
2.5	Design and Implementation Constraints
As of current the only languages allowed to be used in this project is HTML and CSS, no JavaScript can be used as of current

#user documentation

#assumpptions and dependencies
3.	External Interface Requirements
3.1	User Interfaces
The website will have GUI elements which the users will have to interact with to navigate and to leave contact information for blake to follow up on later
3.2	Hardware Interfaces
This website will be compatible with any device that can run web browsers and has been made to ensure wide coverage of devices will be able to access it without any issues.
3.3	Software Interfaces
This website will run on all commercially available browsers. And require no extra installation of software other than the web browser to access and show the website.
3.4	Communications Interfaces
The web site will be accessible using HTTPS to ensure a secure connection between users and the website, in the future implementation of the website Google firebase will be used to securing host and handle login sessions, as well as securing storing users’ emails, they enter in the contact form

When login is added there will be email confirmation for users to confirm that their email is a real email and prevent spammers
4.	System Features
4.1	Home page
This page will contain information about blake including a blurb about him and hyper links to other pages in his project.

this page requires a working navigation bar to move across the websites.

This page will contain the footer which can be updated to contain any legal information or access to any important information user might need in relation to legal or other concerns.


4.2	Skills page
This page will contain a selection of Blakes skills, this page can be updated in HTML by blake to include any updated skills he wants to add to it.

This page requires a grid layout which can act as modular which allows him to put skills as he requires.

This page also requires the navigation bars and footers same as home

4.3	Projects page
This page will contain a story of some Blakes projects along with screenshots to help illustrate the project. This page can be updated 

This page will use grids to have text on the left and the right will contain a photo of the project 

Each project will be its own container stacked below the previous container


4.4	Contact page

This page will contain a contact form which will allow users to provide contact information for blake. This page currently is not functional but is being implemented in a manner which can be enabled once JavaScript usage is allowed, and a database is attached.

It is important once this becomes functional that it is locked behind a login screen to prevent spamming, as well as ensuring that all communications using this are covered using HTTPS




5.	Other Nonfunctional Requirements
5.1	Performance Requirements
While this website is a small website it is still important to ensure that it runs fast and use HTML and CSS methods which aim to ensure that the website runs quickly and loads resources fast.

It is also important that the performance to be kept optimal to ensure that power usage on laptops and phones is also kept low
5.2	Safety Requirements
Given the website contains information about blake it is important to ensure that data is correctly scrubbed to ensure no data blake does not want public to be hosted on the website
5.3	Security Requirements
In the future any login features or password storing will be handed by google fire base.

Information stored on the website needs to be checked and verified to ensure that no personal information is leaked onto the website.
5.4	Software Quality Attributes
It is important to ensure that the website is of good quality, as visitors visiting the site will be making an impression of the website based on the website

5.5	Business Rules
Since users might be representing businesses interests when they visit the website it is important to ensure that the website remains professional.
6.	Other Requirements
This project must be made in a way which allows future features and upgrades to be implemented into it for future iterations. 

For this website to work on GitHub and be hosted we need to implement a index page which will redirect the “index “that git hub looks for to the home page, from there normal navigation will take over.
