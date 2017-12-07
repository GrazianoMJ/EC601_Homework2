# Homework 5 - Unit Testing
## Exercise Folder:
The folder contains files that cover all of the steps involved in converting roman numerals and integers, and the unit tests associated with the program.
Exercise documentation: [Dive Into Python 3 - Chapter 9. Unit Testing](www.diveintopython3.net/unit-testing.html)
## Part 1 - Black Box Testing and Creating Test Cases
This homework assignment will be performed on the friendlychat application that can be found [here](https://github.com/GrazianoMJ/friendlychat-web)
- 8 test cases were identified and described in detail in the Excel document *Homework_5_Test_Cases.xlsx*
- Video of the performance of some test cases and their results are shown in the following file:
    - *Homework5_Testing_ID7-8.mp4*
## Part 2 - Automated Testing
This portion of the homework assignment utilizes the following website to perform a Monkey Test on the friendlychat web application: [Monkey Test It](https://monkeytest.it/)
- Video of the testing performed can be located in the following file:
    - *Homework5_Testing_MonkeyTest.mp4*
- Description of the result fields:
    - *Page Weight & Page Asset Count:*
        - This section shows how large each component type of the webpage takes up and also how many components of each type are present.
    - *On Load Events:*
        - This section would normally show how long loading data from the cloud would take/how much data is loaded. In the even that too much data was being loaded or it was taking to long, it would provide warnings.
    - *On Click Events:*
        - This section shows whether or not all the buttons on screen do what they are supposed to. As we can see the buttons pressed all show errors but the error message seems to indicate that Monkey Test It doesn't have the ability to access or see the pop-up windows that appear for things such as sign in and picture upload.
    - *Broken Links:*
        - This section would show error warnings about any links that were broken/led to the wrong address. There are no links in my application and therefore we don't see any information.
    - *Search Engine Optimization (SEO):*
        - This section helps to indicate what is broken/missing about the web page to help optimize it for web searches. As we can see, the Meta Description of the website does not provide a lot of information and there is a missing tag.
    - *Page Assets:*
        - This section shows the various assets, their size contributions and what files are associated with it. This section is useful because the sliders on the right hand side allow you filter out the descriptions of certain assets so it is easier to read.

This portion of the homework also included some experimentation with Selenium IDE.
- Selenium IDE is a Firefox Add-on for Firefox Version 34 and below that allows  you to record actions and then play them back to test a webpage.
- Although fundamentally easy to use, this system does not allow hide any sensitive information. No videos of its performance were taken
- I tested ID-1 and ID-4 using the system and although it was capable of performing the actions, the system would indicate failure due to a timeout error for the various pop-up windows.
    - I would record these items as Failures but indicate that they may be a false result and suggest alternative means of testing. 
