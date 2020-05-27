# website
Customized website for Department of CSE, IET Lucknow
Brief summary of website: 
Topic of the website is “Department of Computer science and engineering”. This website follows the minimalistic approach and specifically focuses on implementation of different elements of CSS. This element uses accordions, cards, sticky navigation bar, and modal signup form to name some. Theme of this website is green and white. To differentiate elements, it uses different shades of green. To get a more detailed view, a separate details section of every page is discussed below: 

Home page: 
On the home page, header contain IET logo and AKTU logo, both are links to respective websites. After that, there is an image with a quote. Then there is a navigation bar with hover effects of grey and active state of green background and white text using box shadow. After that, there is left side element, aside and right side element, article. In aside, there are two cards, one for Director sir and, one for HOD sir and in the last, there is notice section, which contains links for various notice pdfs regulated by institute. All the elements in aside section are hoverable to implement box shadow. In article section, there is simple text obtained from official website of institute. In the last, there is footer, that contains additional details.

Words of wisdom page: 
This has the same header, quote, navigation bar, aside and footer elements plus in article section, there is an image with round corners and simple text in next section. This content is also fetched from official website of institute. 

Members page: 
Header, navigation bar, quote, aside and footer is same as home page. Article section contains five accordions with animation of opening accordions. Each accordion contains cards of respective faculties, research fellows, class representatives and students Student’s accordion have a table of strength of all classes regulated under Computer science and engineering Department (CSED). Each card and accordion in this section is hoverable with implementation of box shadow property of CSS. 

Syllabus page: 
Header, quote section, navigation bar and footer is same as home page. Instead of aside and article section, there is only cards. This contains 6 cards, each is hoverable with box shadow property. Each card is also a link to respective pdf syllabus of different batches, which will be downloaded automatically, once card gets a click. 

Placement page: 
In actual, this is not a page, this is just a link in navigation bar which redirects user to official T&P cell website of institute. 

Laboratory page:
Laboratory page inherits header, quote, navigation bar, aside and footer, with all its properties from home page. In article section of this page, there is some normal text which contains various information about labs in our department. After that, this section contains a table, of which every row is hoverable with box shadow property. One column of this table contain links to respective laboratory pages on official website of institute. Table have respective columns: Serial no, name of laboratory, incharge person of that laboratory and link column. 

Contact us page: 
This page also inherits header, quote, navigation bar and footer from home page. Instead of aside and article section, this page contains two sections named address and contact form. Address section contains centrally aligned text which is address of institute and contact form has five inputs, of which three are of type=text, one is of textarea and one is of select type. Each input is hoverable with outline color customised. On clicking submit button, data will be saved on your device in the same folder where thesw html files reside in desktop. This file will have extension .txt. This file contains submitted data in a specific format: 
Name-Submitted value 
Designation-Selected value in input type
Mail- submitted mail 
Subject- submitted value 
Message – submitted value 
All these fields are compulsory to fill by default using required attribute of input. Before submission, all the submitted data is validated through a javascript code using onsubmit event. 

Login page: 
On clicking on text in header section, you will be redirected to login page. This can be done by clicking header in any above page discussed. Login page contains a centrally aligned card having a circular avatar image and two input areas, one of text type and other of password type. This card contains three buttons one of submit, one of reset, and one of signup. Firstly, all the data is validated before submission, that is client side scripting. Javascript code executed on submission will check for the specific pair of userid and password in sign.txt. The description of this file will be discussed later on. If the specific pair is found, page shows a message “User logged in”. If pair not found, “Enter correct credentials”. Input types are hoverable with outline color customisation. An horizontal reference line is also there between signup button and submit button. 

Signup page: 
In actual, this is not a separate page, this is just a modal signup page. Modal signup page is produced by first erasing everything, that is on the page, and then make a card containing a signup form with an no-repeat centrally aligned background image. The image is blurred using box shadow. This can be same or different from background image on login page. This form contains three inputs, two of password type and one of text type. Submitted values are first validated on submitting and if found in correct form, data will be written on a text file named signup.txt. This file will be located in the same folder as the HTML files. The format of data submitted is Userid-submitted value 
Password-submitted value
This file's data will be used to validate correct userid-password pair in login page by reading through the file. 

Writing and reading to a text file by javascript code: 
This is done by fs module of javascript. This module contains writeFile() in built function of javascript having syntax: writeFile( path, data, callback); This method is implemented in creating and pushing data in contact.txt and signup.txt. Reading a file includes function readFile( path, data, callback); defined in fs module of javascript. This method is implemented for login form in login page. 

Note:- This website don’t have search pair of userid-password in a text file by javascript implemented as of now. 

Implementation of Javascript: 
 Used in sticky Navigation Bar 
 Used in implementing Accordion transition 
 Used in Client side Validation 
 Used in writing/reading text file using Javascript
