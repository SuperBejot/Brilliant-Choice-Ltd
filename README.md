# Milestone Project 1

## Brilliant Choice Ltd web site

### __Description:__

This website has been created for a construction company called Brilliant Choice Ltd. The company is young and will want to attract new customers. The site is fully responsive and is a kind of portfolio, where, apart from a short description and advertising the company, the most important part is the photo gallery. In this way, the company can show off to new clients the projects it has carried out in the past, as well as the work culture. The guest also has the option of leaving his contact details if he would like to learn more about the company or talk about future cooperation. He will also find here the company address and links to social media such as Facebook or Tweeter where he will find news from the world of Brilliant Choice Ltd.

### __Objectives:__

- To showcase the services Brilliant Choice Ltd has to offer.
- The company will mark its place in the network.
- The company keeps up with the times and is modern.
- The company will gain new customers.
- Expansion of the company's activities on the construction market.

### __Features:__

- In header section we have an interactive company logo and navigation bar that helps you switch between the pages. 
- The navigation bar has a nice mechanic, where when you hover the mouse over any of the buttons, this one will be underlined, and after clicking and redirecting us to the appropriate page, the button will be constantly underlined.
- Then we have another section, which I called "main section" where there is a large picture where you can see and guess what Brilliant Choice Ltd does
- The "about us" section is nothing more than a brief description of the company and what it does.
- The footer section was devoted to links to the company's social media, where with the help of nice and large buttons we can move to the Brilliant Choice Ltd profile on Facebook or Twitter.
- On the Galleria page there are photos that the company can post in order to show off the projects it has made. This is the best way to convince the future client to establish cooperation.
- The third and last page is the Contact Us page, where I have placed a form for clients. After completing the form and leaving his contact details, the customer declares his willingness to talk to Brilliant Choice Ltd. Now all he has to do is wait up to 24 hours and someone from customer service will contact him.
- Below the form is the address and contact details of the company.

### __Technologies Used:__

- HTML5
- CSS3
- Google Fonts: To import font family "Oswald" for paragraphs and "Tilt Warp" for h1, h2 elements into the style.css file which is used on all pages. Added fallback font sans-serif.
- Font Awesome: To add icons for navigation buttons for aesthetic purposes.
- Git: Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- GitHub: GitHub is used to store the projects code after being pushed from Git.

### __Testing:__

- #### Browser testing:
    > - I have tested that this page works using Windows 11 (Asus Nitro 5).
    > - I have tested that this page works in the following browsers: Chrome, Safari.
    > - I have tested this page works on iOS devices using Safari browser (Iphone 13 mini and iPad Air).

- #### Responsivness:
    > To check the responsivness I was using Chrome developer tool.

- #### Validator testing:
The W3C Markup Validator and W3C CSS Validator Services were used to validate all pages of the project to ensure there were no syntax errors in there.
    
    - W3C Markup Validator:

![html_check](/assets/images/html_check.png)

    - W3C CSS Validator:

![CSS_check](/assets/images/CSS_check.png)

    - Lighthouse in Chrome developers tools:

![lighthouse_test](/assets/images/lighthouse_test.png)

- #### Further Testing:
    > * I have tested that the navigation links work and the user is directed to the correct sections of the page.
    > * I tested that the navigation links are underlined when hovering over them.
    > * I have tested that name, surname, email and telephone number are required to submit the form in the contact section.
    > * I have tested that the email input field must contain @ symbol to submit the form in the contact section.
    > * I have tested that the form submit button change text colour when hovering over.

### __Solving bugs:__

- While testing with Chrome developer tools on screens of various sizes, I noticed that the images in the gallery are larger than the screen size. I fixed it in CSS and now one picture takes up 90% of the screen it is displayed on.
- I found that on screens smaller than 1020px wide, the "home" button is unnecessary. Therefore, using @media query, I added a rule that it should not be displayed on screens smaller than 1020px.

### __Deployment:__

The site was deployed to GitHub pages. The steps to deploy are as follows:
- Log in to GitHub and locate the GitHub Repository.
- In the GitHub repository, navigate to the "Settings" tab.
- In Settings, choose "Pages" from the left hand menu.
- Under "Source", select branch "Main" and select folder "(Root)".
- Click Save and the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

### __Acknowledgements:__
- My mentor at Code Institute for helpful feedback.