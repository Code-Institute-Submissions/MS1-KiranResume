# Kiran Satyarthy resume site- Testing details

[Main README.md file](README.md)

[View live site here](https://kiran6248.github.io/MS1-KiranResume/index.html)

## Testing--

  [W3C Markup Validation Service](https://validator.w3.org/)

  * W3C Markup Validation Service is used for the testing of the **HTML** and **no error** was found. The result can be seen here [HTML Test](assets/docs/html-test.JPG)

  [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)

* W3C CSS Validation service is used to check the **CSS** of the project and **no error** was found. The result can be seen here. [CSS Test](assets/docs/css-test.JPG)

 The Project was tested for Browser compatibility. It was found that the navbar was not being fixed in other browsers. Which was fixed by checking codes in **AutoPrefixer.github.io** and updating 
the CSS. That issue is resolved now.

### **Client Stories Testing**--

Testing client stories from UX part of README.md 

1. Recruiters want to easily navigate through the site 
    * Navbar is always fixed on top of the page, It doesn't matter what section of the site they are in.
    * All menu links are connected to the different sections of the page, so it is easy to move anywhere.

2. Recruiters want to see the past work experience of the client and what is He/She doing in present.
    * A separate section is made for the present ongoing course and projects done in that.
    * Past work experience is mentioned in the About section inside the blog.

3. Recruiters want to see the educational qualification of the client. They want to be sure if the applicant is capable of the job.
    * Educational qualification is mentioned in the Heading as well as in the about section.   

4. Recruiters want to know what the employee thinks about herself/himself and how does He/She look.
    * A blog is added to the site and a profile picture is added to the home page.

5. Recruiters want to get a pdf of cv if they like the profile.
    * PDf version of CV can be downloaded from the Resume section in the menu link as well as one download link in the footer.

6. As a recruiter, If I want to contact the applicant, how many ways are there to contact her/him. For example, can I make a telephone call or Can I send an 
 email immediately or can I send a message on any social network sites, such as Linkedin or Twitter.
    * In the personal information section, a telephone number is given. 
    * link to Github and link to Linkedin is also given in the personal information section and the footer also.
    * Twitter link is given in the footer.

7. Recruiters want to know how eagerly applicants want this job and how He/She is upscaling themselves to get this.
    * The Present ongoing diploma is mentioned in the project section.
    * link to Github and Repl.it is also there in the project section.

8. If recruiters like the profile, Is there any way to tell the applicant about the project for which they are considering that profile.
    * One contact form with a project description section is given in the contact section.
    * An Email link is also given in the contact section.    


 


### **Manual Testing of all elements and functionality of every page.**---
* **Navigation Bar**
    
    1. Check if the **navbar** is situated always on top.
    2. Click The **brand logo**, Check if the Home page opens.
    3. Click the **Home link** on the menu bar, the page should remain on the home page.
    4. Click the **Portfolio link**, after clicking the project section opens.
    5. Click the **Resume link**, check if the page opens in a different window with a pdf of CV in it.
    6. Check the **About link**, Blog about me opens in the about section.
    7. Click the **Contact link**, contact section opens with the form in it.
    8. Check for **Responsiveness**, In the mobile view it collapsed in bars.
    9. The collapsed bar in mobile view is checked for its links, It does not collapse back after clicking on a link. This can be viewed as an **open bug** in the navbar.

* **Heading**

    1. Check spelling and content in the **Heading** and qualification.
    2. Check Media query for larger screen size.

* **Personal Info section**

    1. Check **full name** and spelling.
    2. Check the **address** given.
    3. Check the **Phone Number** provided. If it is a valid number.
    4. **Email link** check, if it opens a default Email client.
    5. Click the  **Github** link provided, if it opens the Github of the applicant in a different window.
    6. Click the **Linkedin** link provided, if it opens the Linkedin profile of the applicant in a different window.

* **Profile Image**

    1. Check the responsiveness of the image by reducing the size of the screen.

* **PortFolio**

    1. Go to the project section of the site.
    2. Click Image of the project, it should open the live **URL** of the project in a different window..
    3. Click on the name of the project, it should open the **Github repository** of the project.
    4. Repeat steps 2 and 3 for the second project.
    5. Repeat steps 2 and 3 for the third project, the name of the project should open **Repl.it repository** of the project.
    6. Check responsiveness by reducing screen size, all images and content should come one by one in small screen size.

* **About Me**

    1. Check the content in the blog.
    2. Check spelling by online spelling and grammar checker [Grammarly.com](https://app.grammarly.com/).
    Few spelling mistakes were found, which were corrected.

* **Contact**

    1. Check **Email** address by clicking on it, a default email client opens.
    2. Check the **Contact form** by putting the name in the **name section**.
    3. check contact form by putting email id in the **email section**.
    4. check the **project description** section by writing some text in it.
    5. Click the **Send Project Request button**, Check if it opens the Home page.
    6. Click the button without filling any section, A pop up **"Please fill out this field"** opens.

* **Footer**

    1. Check if the footer is always situated at the bottom of the page by scrolling up and down.
    2. Check the download link on the footer, pdf should open in a different window.
    3. Click the **Linkedin** link on the footer, my Linkedin page should open.
    4. Click the **Github** link in the footer, my Github link should open.
    5. Click the **Twitter** link in the footer, Home page of twitter should open.


**Project Barrier**

 The initial CDN links which were attached in the head element was an older version and that started giving the error in Bootstrap. Especially in the navbar. This is later spotted by my Mentor 
 and was corrected after adding new CDN's from [cdnjs.com](https://cdnjs.com/)

**Bug report**

The navbar is not collapsing back after clicking on it, in the mobile view.
***