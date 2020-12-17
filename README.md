# Overwiew

This is my first Milestone Project for Code Insitute.
The project is a website for a restaurant and it uses basic Html5, CSS3 and Bootstrap.
I got inspired by the restaurant I've been working for a year now, so the menus, the pictures and the logos are taken from a real place, with permission from the owners to use their copyrighted material. 
It's important for me to add that the restaurant has a website already, and it can be seen here: [barrobusta.se](https://www.barrobusta.se/). I didn't take any inspiration from it, but the existing website gave me a fun challenge to create a new representation of the place that can reflect fairly its mood and brand.

# Objective

The main focus of this project is to produce a responsive, clean and intuitive product which also contains
 all the useful informations a user would expect to find on a restaurant website. Its target audience is very wide, all genders from 18 years old to 80 years old.

 # Features

 The website is build with page areas, and it contains:
 * A homepage;
 * A menu section with a "special annoucements" board;
 * A photo gallery;
 * An events section;
 * A contacts page with a booking form.

 ## Wireframes
 
 * [Homepage](https://i.imgur.com/lx4ciIv.png)
 * [Menu](https://i.imgur.com/duzxWmt.png)
 * [Gallery](https://i.imgur.com/nKg4NOt.png)
 * [Events](https://i.imgur.com/BnzC0dY.png)
 * [Contacts](https://i.imgur.com/SAmuImq.png)

 # UX and UXD
 Once it's decided how to structure the information that the website will contain, it's important to focus on the user perspective.
 To build an effective user experience there are a few important key points to consider:
 * Familiarity;
 * Consistency;
 * Predictability;
 * User Assistance.
 
 ## Goal of the Business

 ## Goal of the User

# Credits
I started working on a first raw version of this project on October and it can be seen here: [BarRobusta](https://github.com/ClaudiaLie/BarRobusta).
The website main structure is inspired by one of the lessons from Code Institute, The Whiskey Drop landing page tutorial.

## External Credits

* I relied on [W3Schools website](https://www.w3schools.com/) for what concernes:
    * [Direct mail to an address](https://www.w3schools.com/tags/tag_address.asp)
    * [Map tag](https://www.w3schools.com/tags/tag_map.asp)
* I checked suggestions on [Bootstrap website](https://getbootstrap.com/) for what concernes:
    * [The Booking form](https://getbootstrap.com/docs/4.4/components/forms/)
    * [The Carousel Gallery](https://getbootstrap.com/docs/4.0/components/carousel/)
    * I later decided to create a gallery by[playing with responsive images instead of using a Carousel](https://getbootstrap.com/docs/4.0/content/images/#image-thumbnails)
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

# Testing Details

* [README.md file](https://github.com/ClaudiaLie/MS1_BarRobusta/blob/main/README.md)
* [View Website on GitHub](https://github.com/ClaudiaLie/MS1_BarRobusta)

## Testing

To check the vadility of the website's code, I have used:
* [W3C HTML Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

To audit the quality of the webpage I used:
* [Lighthouse](https://developers.google.com/web/tools/lighthouse/?utm_source=devtools)

## Bugs

* The table element wasn't responsive so I've found a nice compromise on [Stack Overflow](https://stackoverflow.com/questions/40512604/bootstrap-table-is-not-responsive) implementing a side scrollbar for smaller screens.
* I wanted to add a map using a Google Maps API, but I found out that unfortunately it can't be an option for this project since Google requests a payment to generate a code. I decided to simply include an image with a map tag that shows the location on a screenshotted map.
* After the first validation of the website, there were no HTML errors, but 7 CSS errors have been found: [Validator](https://i.imgur.com/hFWRIc7.jpg).
    * I fixed the wrong value on the background-size, by changing it to "cover";
    * I checked on [Stack Overflow](https://stackoverflow.com/questions/52490004/what-are-all-of-these-w3c-css-validation-warnings-about) how the "unknown vendor extension" error affects the quality of webpage. I decided to increase the compatibility with older browsers by keeping the snippet as it is right now.
* A CSS validation on the single pages of the website showed the following errors:
    * [Gallery](https://i.imgur.com/UWkEk9M.jpg), so I have added the alt attribute;
    * [Events](https://i.imgur.com/sJiE4q9.jpg), so I've changed the button element with a form element;
    * [Contacts](https://i.imgur.com/V8WJSRi.jpg), so I gave an id to the map image to style it properly, I have deleted the coords in the area element and modified the duplicated id;
    * [Menu](https://i.imgur.com/FPWTWjl.jpg), so I have changed the p element to a menu element.

* The first Lighthouse test showed that I could have improved the performance using the following suggestions:
    * Using a better formats for the header image;
    * Deleting the unecessary JavaScript snippets;

# Links
