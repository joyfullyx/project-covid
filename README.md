## project-covid

## Overview

Welcome to project Covid-19 Vaccine Finder. For this application, you, the user, will be able to find local stores that provide Covid-19 Vaccines.

Through our app you will be prompted to allow your location to be read so that the map we provide for you can display your general area. Following that you will see our main display. Starting with the navigation bar, there is a dropdown menu that provides a link to the Center for Disease Control's detailed information page of each vaccine type. Following that you will see a carousel of images that have a brief profile of each vaccine that you can scroll through. 

Now you get to the main portion of the application where you will be directed to choose a state and enter a zipcode. Upon the click of the button the user will be directed to the map and list of vaccine sites based on the inputted zip code. The user will see that on the map it is generalized to the rough area of the previously allowed location of the user with stethoscope markers on the map. Each stethoscope on the map has a popup when clicked that provide the user with the name of the store name, address, city, and if there are available appointments for the user. On the list the user will be able to also see the same information in addition they will see each what kind vaccine is provided, as long as that information is also provided through our usd API. The store names now also becomes url links to that particular stores vaccine portion of the website for the user to get further contact information if needed. 

At the footer of the page we have provided additional links for the user to refer to, such as the Word Health Organization, Center for Disease Control and Prevention, and the U.S Department of Health & Human Services. 

## Conclusion & Issues that Occurred  

Over the course of this week we were able to create a functional application with small instances of issues here and there. At first we were planning on using GoogleMaps but upon obtaining the API key we found out that GoogleMaps did not have a free API. We then went onto finding Map Box which we found more success in and through their resources we were able to upload our vaccine API information. This is how we were able to provide a visual display for our users on our map. We used the same information on the vaccine API to provide the information on our list that is created based on the state and zip code provided. One issue we came in contact with was that some states, due to the formatting and or corruption of certain states JSON files, were illegible to and unable to get uploaded onto the map. So unfortunately due to this error we are missing the vaccine location information portion on our map for Maryland, Massachusetts, Missouri, New Jersey, and Pennsylvania. However in the event that the user lives in any of those states they can still get a list of information for their local vaccines. Throughout the creation of this application we were able to use many of the skills we were taught since the first week of class. From implementing different HTML, CSS, and JavaScript skills and using third parties to assist in the styling and layouts of the page. We were able to utilize almost all the taught skills and resources to complete our application.

Link to site: [Covid-19 Vaccine Finder](https://igotyu.github.io/project-covid/).

![landing-screen](https://raw.githubusercontent.com/iGotYu/project-covid/develop/images/landing-screen.png)
![map-footer](https://raw.githubusercontent.com/iGotYu/project-covid/develop/images/map-footer.png)
![state-slector](https://raw.githubusercontent.com/iGotYu/project-covid/develop/images/state-selector.png)
![results](https://raw.githubusercontent.com/iGotYu/project-covid/develop/images/results.png)