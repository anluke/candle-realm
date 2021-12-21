![CR logo](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/readme-banner.png?raw=true)



This project is a static website for a fictitious Candle Making company, called **Candle Realm**.  
The live website can be found [here](https://anluke.github.io/candle-realm/).

<br />

## Purpose

This website was created to complete the first Milestone Project for the Code Institute's Full Stack Developer course.  
The project was built using the knowledge and skills gained from the HTML & CSS. A full list of technologies can be found in the technologies section of this document.  

Project was built as an idea for a small company selling custom-made candles with natural ingredients but also oferring 'Do-It-Yourself' kits to showcase the simplicity in candle-making and mixing/testing different ingredients.  
The idea is to look simple but informing enough to catch someone's attention in hope to build a relationship.

<br />

## Features
- __Navigation__  

    ![Nav Bar](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/navigation-bar.png?raw=true)

    - Featured on all three pages, the full responsive navigation bar includes links to the Logo that links to the top of the Home page.
  
    - The other navigations links are to the right: Home, About, and Sign Up page and are identical on each page to allow for easy navigation. They also change color upon hover and show active page underlined for easier navigation.

    - The navigation tells the user the name of the company and makes the different sections of the webpage easy to find.  
<br />



- __Hero__  

    ![Hero](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/hero-section.png?raw=true)

    - The Hero section contains a greeting and provides a user with clear information about what the site is and the idea behind the company.

    - The aim for a background was to be peaceful yet welcoming and to blend in well with other colors on the website.

    - Hero section should catch the user's attention and look like a cozy place.    
<br />

- __Main Section__  

    ![Main](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/main-section.png?raw=true)

    - The purpose of the Main Section is to provide a user with information regarding the company and ingredients that we use.  
    It is just below the 'Hero-Section' but it's not taking too much space as the idea is to be inviting and informational about the products.

    - It has another welcoming heading that's notifying a user that we are one of the best suppliers of custom-made products and 'Do-It-Yourself' kits.

    - It also informs the user that all of the products are made locally and by hand. Depending on the user's needs we have everything to get them started.

    - It also has three examples of the most popular types of wax currently in the world.  
    Every ingredient has a description and a picture giving the best example of the difference between the three.  
    It also gives a quick description regarding their individual benefits or cons.

    - At the bottom of the main section is a time-lapse video showing a difference between them in a Real-Life setting.  
    It has a nice melody to it and is also very positive and inviting.  
<br />

- __About Section__

    ![About](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/about-section.png?raw=true)

    - The About section shows the user important information they need to know about the Candle Realm.  
    Explains quickly who we are and why the customer should join us.

    - It has a couple of cards including **Who We Are**, **Why Us?**, **Our History**, and **Contact Us** card.

    - At the bottom of the section is a simple but informational contact card including phone number, email address & company location.  
<br />

- __Sign Up Section__

    ![Sign Up](https://github.com/anluke/candle-realm/blob/main/assets/readme-images/sign-up.png?raw=true)

     - The sign-up section has a form to collect basic details from users so they can get started with Code Realm membership.  

    - The form collects the user's name, last name, and email address.

    - The Sign-Up form has a background image with warm colors matching the layout and giving that warm feeling.

    - The Submit button scales and changes color on hover, adding more functionality to the overall submit form.  


<br />

## Testing

- I tested that this page works in different browsers: Chrome, Firefox, and Safari.

- The page is responsive and contains all the functions across different screen sizes using the dev tools device toolbar.

- I confirmed that header/navbar, hero, main-section, about, sign up and footer are all readable and easy to understand.

- I also confirm that submit form works: requires an entry in every field and also checks if a user has put a correct email address by checking the email address format.


### Bugs

- When I tested my page through **Multi Device Website Mockup Generator** I discovered a slight offset in the hero background image. While writing a Media Query for Laptop devices I had moved the background image left by -1 cm instead of just moving it left to allow for better representation of the Hero image.

```
  #hero {
    background-position-x: -1cm;
  }
```
 - Removing the ```-1 cm``` and replacing it with ```left``` attribute fixed the issue and got the Hero image to respond how I intended.

 ### Validator Testing