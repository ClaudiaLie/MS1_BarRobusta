# Overwiew

This is my first Milestone Project for Code Insitute.
The project is a website for a restaurant and it uses basic Html5, CSS3 and Bootstrap.
I got inspired by the restaurant I've been working for a year now, so the menus, the pictures and the logos are taken from a real place, with permission from the owners to use their copyrighted material. 
It's important for me to add that the restaurant has a website already, and it can be seen here: [barrobusta.se](https://www.barrobusta.se/). I didn't take any inspiration from it, but the existing website gave me a fun challenge to create a new representation of the place that can reflect fairly its mood and brand.

# UX
## Objective

The main focus of this project is to produce a responsive, clean and intuitive product which also contains
 all the useful informations a user would expect to find on a restaurant website. 
 Its target audience is very wide, all genders from 18 years old to 80 years old.
  <br> 

 To build an efficent website it's important to focus on an efficent design aswell, so there are a few important key points to consider:
 * <b>The user must have an easy navigation.</b> 
    * It's very important that the user doesn't struggle when navigating through the website, so having a standard website structure with a navbar on top and contact details on the footer, makes the user confident on the actions he has to make to explore the page;
 * <b>A consistent design. </b>
    * Having the same color scheme and the same design structure on a website helps to define a brand and, again, give the user a less confusing and chaotic feeling while navigating;
 * <b>Help the user. </b>
    * With some tricks the user can be drawn to an ideal navigation path. Buttons, bold titles and shortcuts can make the experience efficent and less tiring. 

 ## Features

 The website is build with page areas, and it contains:
 * A homepage;
 * A menu section with a "special annoucements" board;
 * A photo gallery;
 * An events section with an events calendar;
 * A contacts page with a booking form.

  The page areas have a consistent design with a top navbar, a bottom page footer and a hero image of a fixed size, that changes only to contextualize the visited page. 
 
 ## Colors

 The color scheme uses the following shades:
 * <b>Rgba(0, 0, 0, 0.5)</b> for the navbar overlay. 
 <br>It gives a gentle shadow effect on the hero image for desktop users, this avoids strong color separations between navbar and the rest of the page;
 * <b>Rgba(70, 70, 70, 0.95)</b> for the navbar on mobile and tablets and it matches the footer color.
 <br> Considering the smaller visual space, the navbar for mobile devices needs to stand out and be easier to read;
 * <b>Rgb(255, 140, 0)</b> for the brand name. 
 <br>It's a bright orange color used for different elements of the website, such as the media links, buttons and page blocks. 
 Orange has been chosen as brand color to give an overall warm and lively feeling about the restaurant.

 ## Wireframes
 
 * [Homepage](https://i.imgur.com/lx4ciIv.png)
 * [Menu](https://i.imgur.com/duzxWmt.png)
 * [Gallery](https://i.imgur.com/nKg4NOt.png)
 * [Events](https://i.imgur.com/BnzC0dY.png)
 * [Contacts](https://i.imgur.com/SAmuImq.png)

 # Strategy
 
 ## Goal of the Business
 * "We want to increase the sales";
 * "We want to expand our customer base";
 * "We want to show that the restaurant can offer an interesting experience";
 * "We want to make easy for everyone to find us, boosting the media engagement";

 ## User Stories/ Goal of the User
 * "I found this restaurant with a web search and I want to know more about it";
 * "I heard about this restaurant and I want to reserve a table";
 * "I want to find a place to have a Wine Tasting";
 * "I am looking for an Italian Restaurant with traditional recepies".

# Credits
I started working on a first raw version of this project on October and it can be seen here: [BarRobusta](https://github.com/ClaudiaLie/BarRobusta).
<br>The website main structure is inspired by one of the lessons from Code Institute, The Whiskey Drop landing page tutorial.

## Images
All images have been taken, with permission of the owners of Bar Robusta, from [Bar Robusta Facebook Page](https://www.facebook.com/barrobusta) as follows:
* [Homepage Hero Image](https://www.facebook.com/barrobusta/photos/1850284181875307);
* [Events section Hero Image](https://www.facebook.com/barrobusta/photos/2695740973996286);
* [Contacts section Hero Image](https://www.facebook.com/barrobusta/photos/2640309512872766);
* [Menu section Hero Image](https://www.facebook.com/barrobusta/photos/2517471571823228);
* [Gallery Hero Image](https://www.facebook.com/barrobusta/photos/1752650904971969);
* Gallery images:
    * [Image n.1](https://www.facebook.com/barrobusta/photos/2644686429101741);
    * [Image n.2](https://www.facebook.com/barrobusta/photos/1732749716962088);
    * [Image n.3](https://www.facebook.com/barrobusta/photos/2365284980375222);
    * [Image n.4](https://www.facebook.com/barrobusta/photos/2208302566073465);
    * [Image n.5](https://www.facebook.com/barrobusta/photos/2783776625192720/);
    * [Image n.6](https://www.facebook.com/barrobusta/photos/2646192708951113);
* [Mobile Homepage Hero Image](https://www.facebook.com/barrobusta/photos/2376811322555921).

## External Credits

* I relied on [W3Schools website](https://www.w3schools.com/) for what concernes:
    * [Direct mail to an address](https://www.w3schools.com/tags/tag_address.asp)
    * [Map tag](https://www.w3schools.com/tags/tag_map.asp)
* I checked suggestions on [Bootstrap website](https://getbootstrap.com/) for what concernes:
    * [The Booking form](https://getbootstrap.com/docs/4.4/components/forms/)
    * [The Calendar table form](https://getbootstrap.com/docs/5.0/content/tables/#overview)
    * [The Carousel Gallery](https://getbootstrap.com/docs/4.0/components/carousel/)
    * I later decided to create a gallery by [playing with responsive images instead of using a Carousel](https://getbootstrap.com/docs/4.0/content/images/#image-thumbnails)
* Calendar date picker is from [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/datetime-local)

## Deployment

* The website is hosted by GitHub Pages, a service offered by GitHub. 
To deploy a website from GitHub Pages the following steps must be followed:
    1. Create a GitHub Account;
    2. Create a Repository, an online storage for the content and files of your website, the name of your Repository must follow the naming convention of GitHub Pages (your-name.github.io);
    3. Use a Git Client (such as GitHub Desktop) to clone your repository and store it in a folder;
    4. Start coding creating an index.html file in your project;
    5. Add, commit and push your changes from your CLI terminal;
    6. After pushing your changes make sure your project is set to Public in the setting section and select a source branch to enable GitHub Pages to publish your repository;
    7. The website is now successfully deployed! The URL will be visible on your repository settings.

# Testing 

## Testing Details

To check the vadility of the website's code, I have used:
* [W3C HTML Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

To audit the quality of the webpage I used:
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools)

## Bugs

* The table element wasn't responsive so I've found a nice compromise on [Stack Overflow](https://stackoverflow.com/questions/40512604/bootstrap-table-is-not-responsive) implementing a side scrollbar for smaller screens.
* I wanted to add a map using a Google Maps API, but I found out that unfortunately it can't be an option for this project since Google requests a payment to generate a code. I decided to simply include an image with a map tag that shows the location on a screenshotted map.
* After the first validation of the website, there were no HTML errors, but 7 CSS errors have been found: [Validator image](https://i.imgur.com/hFWRIc7.jpg).
    * I fixed the wrong value on the background-size, by changing it to "cover";
    * I checked on [Stack Overflow](https://stackoverflow.com/questions/52490004/what-are-all-of-these-w3c-css-validation-warnings-about) how the "unknown vendor extension" error affects the quality of webpage. I decided to increase the compatibility with older browsers by keeping the snippet as it is right now.
* A CSS validation on the single pages of the website showed the following errors:
    * [Gallery](https://i.imgur.com/UWkEk9M.jpg). I have added the alt attribute;
    * [Events](https://i.imgur.com/sJiE4q9.jpg). I've changed the button element with a form element;
    * [Contacts](https://i.imgur.com/V8WJSRi.jpg). I gave an id to the map image to style it properly, I have deleted the coords in the area element and modified the duplicated id;
    * [Menu](https://i.imgur.com/FPWTWjl.jpg). I have deleted the p element and I let the quotes to be enclosed only in two blockquote elements, spacing nicely the two divs.

* The first Lighthouse test showed that I could have improved the performance using the following suggestions:
    * Using a better formats for the header image;
    * Deleting the unecessary JavaScript snippets;

## User Stories Testing
 * "I found this restaurant with a web search and I want to know more about it"
    * Every page of the website contains a simple and easy to use navigation bar, always set on top of the page;  
    * The homepage contains buttons that link to the main interests of the website (reserve a table, menu and events section) to help the user navigation;
    * The images of the website are actual pictures from the location, the idea is to let the user explore the restaurant through a virtual window, and get even more familiar with the place.
 * "I heard about this restaurant and I want to reserve a table"
    * Buttons that link to the booking page repeats through different pages of the website, in order to make easier for the user to get to the reservation;
    * The booking form is shaped to statify the needs of any customer, it shows that the staff is prepared for any food restriction or allergy;
 * "I want to find a place to have a Wine Tasting"
    * The Wine Tasting experience is very popular now, from the homepage the user can read that the wines are imported directly from the producers and that the restaurant works with certificated sommelier only.
    * The Events section has a calendar dedicated only to the Wine Tasting.
 * "I am looking for an Italian Restaurant with traditional recepies"
    * The identity of the restaurant is shown in the homepage, with "About us" section of the webpage, and it highlights the imporance to respect the traditions with a look onto the contemporary world.
    * The Menu section contains links to the full menus;
    * The restaurant offers a special dinner event with traditional recepies and the user can read the full menu from the Menu section.

# Links
* [README.md file](https://github.com/ClaudiaLie/MS1_BarRobusta/blob/main/README.md)
* [View Website on GitHub](https://github.com/ClaudiaLie/MS1_BarRobusta)
* [See the Website](https://claudialie.github.io/MS1_BarRobusta/)
