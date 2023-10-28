# Information Technology Terms Quiz Application

Welcome, 

This project was carried out within the framework of my Second Milestone Project for the Full-Stack Web Development Diploma from the Code Institute.  

Used technologies include  HTML5, CSS3, JavaScript to demonstrate my personal skills and acquired knowledge from this online program. 

Code was written mostly on my own but some libraries were taken as well to improve functionality and CSS. 

I will be glad to hear your feedback about your experience using this web application. Just fill out the contact form included in the application when you click on "Contact Us"

Website hosted on GitHub Pages here: [IT Terms Quiz Application](https://onuorah-joshua-nwani.github.io/ojn-msp-2-IT-Terms-Quiz-App-with-Timer/)


## UX


![Responsive Views of Home Page](/documentation/rm-images/AIR-start-quiz-page.png), 
![Responsive Views of Home Page](/documentation/rm-images/AIR-quiz-instructions-page.png), 
![Responsive Views of Home Page](/documentation/rm-images/AIR-game-play_ojn-msp-2-IT-Terms-Quiz-App-with-Timer_.png)

The main objective was to create a simple looking and appealing online dashboard for following market stock prices, EThe primary goal of this project was to develop an interactive and user-friendly web application to test the knowledge of individuals on various IT terminologies.

The application is designed specifically for beginners and those who wish to test and refine their knowledge about IT terms and phrases. Through an engaging timer-based quiz, users can gauge their expertise and improve upon their shortcomings.

This quiz platform provides the user with a set of questions, each accompanied by a timer that keeps the engagement high and the challenge intriguing. Once an answer is selected, it can't be changed, ensuring that users make thoughtful decisions within the time frame.

One of the significant advantages of this application is its simplicity. It doesn't require users to sign up or store their data. It solely depends on the browser's runtime and doesn't store any personal information, ensuring user privacy.

The inspiration behind this application came from user stories similar to the following:

"I've always been curious about IT terminologies but never really had a platform to test my knowledge. Most of the online platforms are either too complex or require sign-ups. I just wanted something quick and easy."

"As a student studying IT, I wanted a simple quiz application where I could quickly test what I've learned. The timer in this application makes it challenging and fun at the same time."

"I've been in the IT industry for a while, but it's always good to brush up on terminologies and concepts. This application provides a quick and interactive way to do just that."

Features:
Interactive Introduction Box: Provides a warm welcome and sets the expectation for the quiz.

## Info Box: 
Lays out the rules of the quiz, ensuring users are aware of the guidelines.

## Quiz Box: 
The main section where the quiz takes place. Questions and options are dynamically displayed, accompanied by a timer for each question.

## Result Box: 
Provides feedback on user performance after the completion of the quiz.

To get started with the quiz, simply launch the application and follow the on-screen instructions.



The website was first designed using a wireframe which can be found on miro.com under this link:

![Wireframe Image](/documentation/wireframes/Desktop-1.jpg) 
![Wireframe Image](/documentation/wireframes/Laptop-1.jpg)
![Wireframe Image](/documentation/wireframes/Desktop-1.jpg) 
![Wireframe Image](/documentation/wireframes/Tablet-1.jpg)

[Miro Wireframe - Second Milestone Project](https://app.visily.ai/projects/f3a5621b-2d9a-494c-b212-2149dda2c3d1/boards/584188)


## Features

### Introduction Box: 
**A warm welcome**:  to users, outlining the rules and expectations of the quiz.
**Timer**: Challenges users to respond within 15 seconds, adding a layer of excitement and urgency.
**Quiz Box**: The main area where questions will be displayed to the users along with multiple-choice options.
**Result Box**: Showcases the final score of the users once they complete the quiz. 
 
### Planned Features
**Multiple Quiz Categories**: Offering quizzes in specialized IT categories like Networking, Software Development, Cybersecurity, etc.
**Leaderboard**: Displaying top scores to foster a competitive environment.
**Review Mode**: Allowing users to review their answers post completion.

## Technologies Used

Languages, frameworks, libraries used to construct this project:

- HTML5
- CSS3
- JavaScript 
- [Font Awesome Icon Library](https://fontawesome.com/icons?d=gallery)
    - Icons were imported to provide some visual iconography, e.g. star icon for buttons to save stocks in Watch List.
- [Am I Responsive] (https://ui.dev/amiresponsive?url=https://onuorah-joshua-nwani.github.io/ojn-msp-2-IT-Terms-Quiz-App-with-Timer/)
    - Testing responsiveness of the applicaton in different devices, like the example above:

## Testing

### Problem Solving

**Problem** Difficulty in updating the UI in real-time as the user progresses through the quiz.

 - **Solution** Leveraged the DOM manipulation capabilities of JavaScript to dynamically render questions and options.
**Problem** Ensuring that once an answer is selected, it cannot be changed.

 - **Solution** Implemented event listeners that lock in the user's choice and disable further changes to that particular question.

### Unsolved Issues 
**Problem** Incorporating a responsive timer that visually counts down.
 - **Solution Pending** Plan to integrate a more dynamic countdown timer using CSS animations.

### Performance 

![Test Performance Screenshot](/documentation/testing/screenshot_test_performance.png)
A LightHouse Report was generated to evaluate the performance of the web application. The full report can be retrieved here: [Light House Report](/documentation/browser-testing/lighthouse.pdf)
In order to run this test it is necessary to open the application on incognito mode of Chrome broswer and follow these steps:
1. Activate Developer Tools by doing right click and select "Inspect"
2. Click on "Console" from the upper menu items and then click on the two arrows in the end of the list to the right >>
3. Select "Audits" and then "Generate Report"
4. Follow the prompt to finalize report. Use the options to print report if necessary. 

### Front End 
Front-End Software and JavaScript performance were tested in real phones, laptops and desktops to test the responsiveness of the site in in real life using different browsers like Chrome, IE and Firefox. 
![Front End Testing Different Devices](documentation/testing/Front_end_testing_devices.png)

### Back End
Further testing of Back-End will be peformed with automated tests when the back-end software is developed. 

## Deployment

The code was developed solely on Codeanywhere and then it was pushed to an external repository on [GitHub](https://github.com/Onuorah-Joshua-Nwani/ojn-msp-2-IT-Terms-Quiz-App-with-Timer.git).
The settings of this GitHub repository were changed to host the code into GitHub Pages from the **master branch.**
Currently the GitHub site is published here:[IT Terminologies Quiz Bank](https://onuorah-joshua-nwani.github.io/ojn-msp-2-IT-Terms-Quiz-App-with-Timer/)

To deploy the project from its repository, the following should be taken:

1. Log in to GitHub.com
2. From the repository screen, select this project "/ojn-msp-2-IT-Terms-Quiz-App-with-Timer"
3. On top of the page, click on the last right icon "Settings".
4. Scroll down until you reach the GitHub Pages section.
5. Change the source to the "Master Branch" using the drop down menu, labelled by default first as "none".
6. The application is now deployed on GitHub pages!
7. Copy the provided link from this section and share with others.

## Credits

### Content

 - The quiz questions and content are designed for testing knowledge on IT terminologies.


### Media

- FontAwesome icons are used to enhance visual appeal.

### Acknowledgements

- I received inspiration for this project from my family. 
- Special thanks to my mentor from Code Institute for the direction I needed:
    - Elaine Roche     @elaineroche_mentor
- And last but not least, many thanks to the Tutor Team from Code Institute for helping me whenever I needed help the most. 