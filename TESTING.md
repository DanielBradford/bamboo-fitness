## **Testing**

HTML VALIDATION - https://validator.w3.org/
* All HTML written in this project has been submitted for validation via the above software
* ALL pages returned the vaildation that "Document checking completed. No errors or warnings to show."

CSS VALIDATION - https://jigsaw.w3.org/css-validator/
* All CSS written in this project has been submitted for validation via the above software
<img src="https://github.com/DanielBradford/bamboo-fitness/blob/master/assets/images/TESTING%20SCREENSHOTS/CSS%20-%20Validation.png" alt="CSS Validation">


### **Client Story Testing:**
1. As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
    * Every page has a clear navigation bar that is easy to find. It also is highlighted when the user is on that page.
    * Every page shows the logo image which when clicked leads back to the home page

1. As an interested client, I want an easy to fill in enquiry form, so I can make contact with the gym.
    * The landing/home page has a clear "call to action" button (labelled "Join Us")which when clicked opens an enquiry form to be easily filled by the user
    * The Contact Us page also has the option to fill in an enuiry form which can be sent to the gym.

1. As a new visitor to the website, I want learn more about the gym, so I can feel I understand their brand and ethos.
    *  All pages hold the logo and images that maintain the theme of nature, fitness and well being. 
    *  All pages hold an alert box at the top of the page that advertises the gyms charity donations.
    *  The landing/home page's first section has a summary of what the gym offers.
    *  The landing/home page's second section has information about the gym's charity donations.

1. As a new and potential client, I want information about gym memberships and prices, so that I can decide what suits my needs and budget.
    * On the landing/home page the membership section clearly displays 3 options of membership with text displaying information and prices.

1. As an interested current/or potential client, I want to follow the gym on social media, so I can keep up with their latest news.
    * At the bottom of every page there are social media icons. When clicked these open a new browser tab witht he selcted social media site.

1. As a potential/current client, I want to check the class timetable, so I know when my classes would be/are.
    * The Classes page has a clear "call to action" button (labelled "Class Timetable") which when clicked opens a pop-up window with a time-table of classes.
    * HOME > CLASSES > CLASS TIMETABLE 
    * This also offers the client the option to download a PDF version of the class timetable to the users device.
    * HOME > CLASSES > CLASS TIMETABLE > Download PDF > (PDF Opens in new tab)
    * The client also has the option (if using a desktop) to scan a QR-Code with their phone which will download the PDF to their phone.
    * HOME > CLASSES > CLASS TIMETABLE > (User scans QR Code with Phone) > (PDF opens on user mobile)
1. As a new/current client, I want to know what classes are on offer so i know what classes there are.
    * The Classes Page displays class "medals" that display breif summaries of the classes that the gym has to offer.
    * HOME > CLASSES 
1. As a new visitor to the website, I want view the gym's gallery, to see images and videos of their members and facilities, so i can decide if I want to join.
    * The Gallery page displays a number of images that show members, equipment and facilities of the gym. When selected the image will open to a full size in a new tab.
    * The Gallery Page displays a number of videos that show members, equipment and facilities of the gym.
    * HOME > GALLERY 

1. As a new and potential client, I want to get in contact with the gym, so that I can ask more specific questions with a representative of the gym.
    * The Contact Us page also has the option to fill in an enquiry form which can be sent to the gym.  
    HOME > CONTACT US > (User completes form) > SEND

1. As a potential/current client, I want to check the opening times, so that i know when i can go to gym.
    * The Contact Us page has a clear "call to action" button (labelled "Opening Times") which when clicked opens a pop-up window with a table of opening times.
    * HOME > CONTACT US > OPENING TIMES

1. As a current client, I want to get contact information, so i can ask a question about my membership
    * The Contact Us page has a section displaying the 3 main forms of contact information: Phone, Email and Address.
    * When the Phone Feature is selected the users device (if enabled) will invite a call to be made using that number
    * When the Email Feature is selcted the users device (if enabled) will open a new email with 'to' address completed automatically
    * HOME > CONTACT US > EMAIL
    * HOME > CONTACT US > PHONE

1. As a current client, I want to know where the gym is located, so that i can find it. 
    * On the Contact Us page, when the address feature is selcted the users device will open a new window and driect them the google maps link for the address of the gym.
    * HOME > CONTACT US > ADDRESS
    * From this point the user can get directions and make travel plans.



## Logical Testing (MANUAL) of all functions and elements:

### **Home/Landing Page**

* Go to the "Home" page from a desktop.

    * **Alert Box**
        1. Verify the sizing of the box adjusts from desktop > tablet > mobile and that no over flow distorts the layout:
            * _During testing i decided to only make the alert box visible on desktop versions._
        2. Verify that the link "Click for more info" works:
            * _When the link is clicked the user is taken to the charity information section._
            * _During testing i had issues with the navigation between different pages but i fixed this by altering the href of the anchor tag._
    * **Navigation Bar**
        1. Verify that the sizing of the navigation bar adjusts with screen size changes:
            * _I made the navaigation menu condense to a hamburger button for both tablet and mobile screen sizes._ 
        2. Change screen size to small and click burger icon, verify that the menu drops down and that the menu text is clear and visible.
            * _I had difficulties during testing but found a method to make this work_
        3. Hover over the navigation links and verify the CSS stylings changes
            * _Some styling choices were changed during testing due to accessbility/contrast issues_
        4. Click on each of the navigation links and verify that it takes the user to the corresponding pages
            * _During testing i found the home button did not function. This issue was corrected_
        5. Repeat verification of functionality and responsiveness on my mobile phone and tablet.
    * **Logo**
        1. Click the logo and verify the user is taken to the home/landing page.
    * **Background/Container Images**
        1. Verfiy all background images are well sized and do not obstruct the information presented.
        2. Check this on all screen sizes.
    **"Join US" Button**
        1. Hover on button to verify CSS styling causes color change to allow user to see selection before clicking
        2. Click button to verify the enquiry form is displayed via a modal. 
    * **Enquiry Form**
        1. Click "Send" with empty input fields to verify the form will NOT submit and reminds the user the inputs need to be made
        2. Purposely enter an INVALID email address in email input to verify the form validation reminds user to enter VALID email address.
        3. Click Send with VALID inputs to verify the form window closes at completion.
        4. Click Close button to verify the pop-up window closes correctly.
        5. Verify the form is visible and functional in tablet and mobile. 
    *  **What we do**
        1. Hover over highlighted words to verify they increase in size to add impact
            * During testing i decided to keep the increase minimal to not disturb the user
        2. Verfiy all information is centered and visible
    *  **What we offer**
        1. Hover over highlighted words to verify they increase in size to add impact
            * During testing i decided to keep the increase minimal to not disturb the user
        2. Click on Charity Logos to verfiy the link to corresponding website works
        2. Verfiy all information is centered and visible
    *  **Membership Medals**
        1. Hover over the item to verify the scaled transition to show user selection.
            *During testing i decided to keep the scale increase minimal to not disturb the user
        2. Verfiy all information is centered and visible.       
    * **Footer**
        1. Hover over the icons to verify the hover color change is applied
        2. Click each of the Social Media Icons and verify the user is taken to the corresponding websites.
        3. Verfiy the icons are visible
            * During testing i altered the color of the icons to give a higher contrast rating to make them more visible 
        4. Hover over each social media icon and confirm colour and size transitions expected.
        5. Click "Return to Top" link to verify the user is returned to top of current page.
        6. Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.


### **Classes Page**
* Go to the "Classes" page from a desktop 

    * **Alert-Box**
        1. Repeat verification steps done for alert-box on Home page.
        2. Confirm that alert-box code is identical on all html pages.
    * **Navigation Bar**
        1. Repeat verification steps done for navbar on Home page.
        2. Confirm that navbar code is identical on all html pages.
    * **Logo**
        1. Repeat verification steps done for logo on Home page. 
    * **Background/Container Images**
        1. Verfiy all background images are well sized and do not obstruct the information presented.
        2. Check this on all screen sizes.
    * **"Class Timetable" Button**
        1. Hover on button to verify CSS styling causes color change to allow user to see selection before clicking
        2. Click button to verify the class timetable is displayed via a modal. 
    * **Class Timetable Modal** 
        1. Verify all table information is valid and correct 
        2. Verify all table information is visible in the pop-up window.
        3. Verify the form is visible and functional in tablet and mobile. 
        4. Hover on "Download PDF" button to verify the hover color change happens
        5. Click on "Download PDF" button to verify the user is taken to new tab with PDF Timetable version. 
        6. (DESKTOP ONLY) Scan QR CODE with mobile phone camera to verify the user is taken to PDF on their mobile device
        7. Click on close button to verify the user can close the pop-up window.
    * **Class Type Medals**
        1. Hover on Class Medals to verfiy they increase in scale
            *During testing i decided to keep the scale increase minimal to not disturb the user
        2. Verfiy all information is centered and visible
    * **Team Medals**
        1. Hover on Team Medals to verfiy they increase in scale
            *During testing i decided to keep the scale increase minimal to not disturb the user
        2. Verfiy all information is centered and visible
    * **Footer**
        1. Hover over the icons to verify the hover color change is applied
        2. Click each of the Social Media Icons and verify the user is taken to the corresponding websites.
        3. Verfiy the icons are visible
            * During testing i altered the color of the icons to give a higher contrast rating to make them more visible 
        4. Hover over each social media icon and confirm colour and size transitions expected.
        5. Click "Return to Top" link to verify the user is returned to top of current page.
        6. Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
  

### **Gallery Page**
* Go to the "Gallery" page from a desktop 

    * **Alert-Box**
        1. Repeat verification steps done for alert-box on Home page.
        2. Confirm that alert-box code is identical on all html pages.
    * **Navigation Bar**
        1. Repeat verification steps done for navbar on Home page.
        2. Confirm that navbar code is identical on all html pages.
    * **Logo**
        1. Repeat verification steps done for logo on Home page. 
    * **Background/Container Images**
        1. Verfiy all background images are well sized and do not obstruct the information presented.
        2. Check this on all screen sizes.
    * **Images**
        1. Verfify all images are displayed in a clear grid format and respond to all screen sizes
        2. Hover over each image and verify the image border appears
        3. Click on each image to verify the image opens in a new tab in full size
        4. Verify all images are in a presentable format and correlate with the user and business needs
    * **Videos**
        1. Verify all videos are displayed in a clear row format and respond to all screen sizes
        2. Click on each video to verify the controls function i.e. PLAY | PAUSE | FULL SCREEN 
    * **Footer**
        1. Hover over the icons to verify the hover color change is applied
        2. Click each of the Social Media Icons and verify the user is taken to the corresponding websites.
        3. Verfiy the icons are visible
            * During testing i altered the color of the icons to give a higher contrast rating to make them more visible 
        4. Hover over each social media icon and confirm colour and size transitions expected.
        5. Click "Return to Top" link to verify the user is returned to top of current page.
        6. Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
  
    

### **Contact Us Page**
* Go to the "Contact Us" page from a desktop 

    * **Alert-Box**
        1. Repeat verification steps done for alert-box on Home page.
        2. Confirm that alert-box code is identical on all html pages.
    * **Navigation Bar**
        1. Repeat verification steps done for navbar on Home page.
        2. Confirm that navbar code is identical on all html pages.
    * **Logo**
        1. Repeat verification steps done for logo on Home page. 
    * **Background/Container Images**
        1. Verfiy all background images are well sized and do not obstruct the information presented.
        2. Check this on all screen sizes.
    * **Opening Hours Button**
        1. Hover over button to verify CSS color change
        2. Click on button to verfiy the modal functions and opens the pop-up window
    * **Opening Hours Modal**
        1. Verify all table information is clear and visible
        2. Verfify the modal is viewable in all screen sizes    
            * _During testing i found this modal to cause side-scrolling so i altered the format of the table from 4 columns to 3._
    * **Phone Contact Information**
        1. Verfiy the information is clear and visible
        2. Click on link to verify the user is presented with the option to call the gym
            * On Desktop the user is offered the option to do so via Facetime
    * **Email Contact Information**
        1. Verify the information is clear and visible
        2. Click on link to verfiy a new email is created on the users device with the gym's email address added 
    * **Address Contact Information**
        1. Verify the information is clear and visible
        2. Click on the link to verfiy google maps opens with the address of the gym presented
    * **Social Media Icons**
        1. Repeat verification steps done for social media icons on Home page.
    * **Footer**
        1. Hover over the icons to verify the hover color change is applied
        2. Click each of the Social Media Icons and verify the user is taken to the corresponding websites.
        3. Verfiy the icons are visible
            * During testing i altered the color of the icons to give a higher contrast rating to make them more visible 
        4. Hover over each social media icon and confirm colour and size transitions expected.
        5. Click "Return to Top" link to verify the user is returned to top of current page.
        6. Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
  

### **Development Tools Testing**
From using the technologies of Wave and Lighthouse i was able to check the performance and accessiblity of the website. By utilisng this in DevTools i was able to generate reports for both desktop and mobile.
By analysing these rerports i was able to make alterations in both the HTML and CSS code to improve the accessiblity of the site.
    
**Performance**
* In initial reports the website had an average Performance rating of **86**.
* I changed changed the appropriate .jpg & .png files into webp format to minimalise memory usage and speed up loading and rendering times.
* I streamlined the style.css file to lessen the date being loaded.
* By  making these changes the current Performance rating is now (on average) **94**

**Accessibility**
* In initial reports the website had an average Accessibility rating of **84**
* I altered color schemes of text vs. background to maximise the contrast score allowing information to be more visible to a wider group of users with accessiblity issues.
* I resized icons and images to make them more visible
* I re-assessed background image choices for their contrast score
* By making these changes the current Performance rating is now (on average) **96**

**Best Practices**
* In initial reports the website had an average Best Practices Score of **91**
* I added 'rel' attributes for links in anchor tags leading to external sites e.g. rel=noreferrer
* By making these changes the current Best Practices rating is now (on average)**100** 

**Search Engine Optimisation**
* In inital reports the website had an average SEO rating of **98**
* I added in some META tags to give more information about the websites content and creator.
* By making these changes the current SEO rating is now **100**

**DESKTOP REPORT SCREENSHOTS**
Lighthouse Desktop Reports:

* Home/Landing Page:
<img src="https://github.com/DanielBradford/bamboo-fitness/blob/master/assets/images/TESTING%20SCREENSHOTS/Home-Testing.png" alt="Home Page - LIGHTHOUSE REPORT">
* Classes Page:
<img src="https://github.com/DanielBradford/bamboo-fitness/blob/master/assets/images/TESTING%20SCREENSHOTS/Classes-Testing.png" alt="Classes Page - LIGHTHOUSE REPORT">
* Contact Us Page:
<img src="https://github.com/DanielBradford/bamboo-fitness/blob/5e1a9747eb6cdad697dbe29864a69c005cd5dc92/assets/images/TESTING%20SCREENSHOTS/Contact%20Us%20-%20Testing%20Screenshot.png" alt="Contact Us Page - LIGHTHOUSE REPORT">
* Gallery Page:
<img src="https://github.com/DanielBradford/bamboo-fitness/blob/master/assets/images/TESTING%20SCREENSHOTS/Gallery%20-%20Testing.png" alt="Gallery Page - LIGHTHOUSE REPORT">