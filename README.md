# ADAM BEACHVOLLEY

The app is a website for a beachVolleyBall club in the city of Amsterdam.
It is especially important now, as beachVolleyBall is an outdoor sport that is allowed despite the health restriction.
The goal is to is to provide a clear information about what this club can offer to the visitors or future members.
The owner of the website will be able to inform his members and viewers, the future events like tournament, trainings and special days.

This website has many purpose: 
- Promote beach volley Ball in Amsterdam
- Increase the amount of new members
- Inform everybody about events (tournament, beach day etc...)

 
## UX

| User ID| as a/an| I want to be able to....| So that i can...| 
| :----: | :--- | :--- | :--- |
| 1| Visitor| to have clear nagigation info| to see what i came for| 
| 2| Visitor| to become member of the club| send my details to get a subscription| 
| 3| Visitor| to visit the website with my phone | watch the picture, or subscribe| 
| 4| Visitor| to read intuitively the content of the site| I have well structured design| 
| 5| Visitor| to see what was the previous events| I can watch photo from previous events | 
| 6| Member|Know the new event coming up| So i can participate at those events| 
| 7| Owner| receive visitor detail| receive email from interested visitor| 
| 8| Owner| To provide info about event| so i can add a banner with the next event| 
| 9| Owner| I want to add pictures and info| I can change the details of the images, and infos| 


## Features

#### Top menu
* NavBar-desktop: The Navbar is at the top and show a Logo and a brand-logo (revert to index-page) that  the following menus: Home/Gallery/Contact (in all pages)
* NavBar for mobile: The navbar for mobile show a Logo (revert to index-page) has a hamburger menu trigger by Javascript specific bootstrap feature. This feature toggle the list of menu  Home/Gallery/Contact (in all pages)

#### Home-page 
* Hero image: showing a beautifull picture about beachVolleyBall
* Descriptive text: Text providing information about the website purpose
* Informative cards: Cards built to have an informative text with an image about what the club is offering. This in order to create an optimal user experience.
* footer: footer created for the copyright.

#### Gallery-page: 
* Past-event images: This section has been created to provide images of the past events or any event related to the website.
They are built to divide the screen size per 3 until the screen goes under 576px

#### Contact-page
* Contact Form:  allow the visitor to enter their email for further info about membership

### Future Features
* Register new member in DB from the form.
* Create a structre or new page for the future events
* Create a login the the member with training plan and free-fields planning

## Technologies Used

#### Languages
* [HTML5](https://www.w3schools.com/html/default.asp)
* [CSS3](https://www.w3schools.com/css/default.asp)
* [Javascript](https://www.w3schools.com/js/default.asp)
#### Libraries and Framework
* [Bootstrap](https://getbootstrap.com/)
* [Google Fonts](https://fonts.google.com/)
* [JQuery](https://api.jquery.com/)
### Tools
* [Gitpod](https://www.gitpod.io/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)


## Testing

### - Navigation:
| Test| Action| Expected Result| Test Result| 
| :--- | :----: | :--- | ---: |
| Home-page| click | Go to the index.html from "home" menu| Passed| 
| Logo menu| click| Go to the index.html from "logo"&"brand-logo menu | Passed| 
| Gallery menu| click| Go to the gallery.html from "Gallery" menu| Passed| 
| Contact menu| click| Go to the contact.html from "Contact" menu| Passed| 
| Subscribe| click| Go to the contact.html from "subscribe" menu| Passed| 
| Form| enter text & click| entering email and password and submit| Passed| 


### - Responsiveness:
| Test| Action| Expected Result| Test Result| 
| :--- | :----: | :--- | ---: |
| Main menu|screen sizing| the 3 menus on at the right become hamburger menu under 576px| Passed| 
| hamburger Menu| click| toggle the 3 main menus| Passed| 
| Brand-logo| screen sizing| Brand-logo (Adam beachVolley) disapear under 576px| Passed| 
| Welcome title| screen sizing| size reduced and left-aligned under 576px| Passed| 
| Informative cards | screen sizing| change layout from 3 cards to 1 under 576 px| Passed| 
| Card-title| screen sizing| size reduced under 992px| Passed| 
| Past-event images| screen sizing| change layout from 3 images to 1 under 576 px| Passed| 
| Images| screen sizing| All images are resizing as the screen does (fluid)| click| when all fields are correctly entered with a valid credit card number, payment should be executed| Passed| 
| Images text| screen sizing | left-aligned when size is under 576px| Passed| 

### Browser Compatibility:
| Test| Action| Expected Result| Test Result| 
| :--- | :----: | :--- | ---: |
| Chrome| Testing model| work as testing| Passed| 
| Firefox| Check Features and Responsiveness| Same as Chrome| Passed|
| Edge| Check Features and Responsiveness| Same as Chrome| Passed|

## Deployment


To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/Befa79/my-css-project), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **Befa79/my-css-project**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.

At the moment of submitting this Milestone project the Development Branch and Master Branch are identical. 

### How to run this project locally

To clone this project into Gitpod you will need:
1. A Github account. [Create a Github account here](https://github.com/)
2. Use the Chrome browser 

Then follow these steps:
1. Install the [Gitpod Browser Extentions for Chrome](https://www.gitpod.io/docs/browser-extension/)
2. After installation, restart the browser
3. Log into [Gitpod](https://gitpod.com) with your gitpod account.
4. Navigate to the [Project GitHub repository](https://github.com/AJGreaves/portrait-artist)
5. Click the green "Gitpod" button in the top right corner of the respository
6. This will trigger a new gitpod workspace to be created from the code in github where you can work locally.

To work on the project code within a local IDE such as VSCode, Pycharm etc:
1. Follow this link to the [Project GitHub repository](https://github.com/AJGreaves/portrait-artist).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open the terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).



## Credits

- http://www.beeveestrand.nl/ (inspiration)
- https://follybeachchairrentals.com/rentals/same-day-rentals/ (logo)
- https://stackoverflow.com/ (filter css style )
- https://unsplash.com/ (images)

Thanks for the tutor team for their help
Thanks to my mentor Brian for the help
