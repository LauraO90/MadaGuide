# MadaGuide

## Overview of project ##
MadaGuide is a website that encourages users to book a tour guide to explore Madagascar. The website is targeted towards tourists, both local people in Madagascar and international tourists with a variety of tour options and multi-lingual guides available. MadaGuide gives prospective customers a range of information including suggested itineraries and positive testimonials to encourage them to plan and book a fantastic trip with MadaGuide.

## Planning - UX and accessibility considerations ##
![Initial planning](documentation/initial-planning.jpeg)

![Initial design considerations](documentation/initial-design-considerations.jpeg)

## UX ##

MadaGuide has been designed with simplicity in mind to maximise the experience for all users.
MadaGuide is designed using the "mobile first" principle to ensure mobile users have a great experience. Considerations and changes were made to suit larger screens to again provide a great experience, while maximising the space available. Google Developer tools were used at every stage to view the UX on mobile, tablet and larger laptop and desktop screens:
![Responsiveness across screen sizes](documentation/madaguide-responsiveness.png)


## Colour Scheme ##

The colour scheme for MadaGuide is mostly neutral to ensure readability and accessibility, with pops of colour used to reflect the flag colours of Madagascar. The red and green colours of the Madagascar flag can be overpowering and their use has therefore been limited to splashes of colour to draw attention to certain features such as a call to action (CTA).CSS variables were used to avoid repetition and enhance maintainability.

Colours used:

- **#000000** - for primary texts and header/footer
- **#ffffff** - for logo and page background 
- **#309135** - for main headings and styling e.g. box shadow (madagascar-green)
- **#c92d18** - for a call to action e.g. submit button on contact us form (madagascar-red)


## Typography ##

Two Google fonts were used for MadaGuide, both fonts are sans-serif without flourishes to provide style and functionality. Both fonts are widely regarded as accessible and look good.

Fonts used:

- **Lilita One** - for header logo
- **Nunito** - for all other text
- **Font Awesome** - a range of logos used to enhance headings, navigation and footer

## Features ##

### Navigation ###

The Navigation Bar is featured on all four pages. The full responsive navigation bar includes link to Home, Itineraries, Contact Us and Thank You pages and the navigation bar is identical on each page to ensure easy navigation. A menu (“hamburger”) button has been used for mobile screens to reduce the volume of information on this smaller pace and improve accessibility for all users. I added touches of colour to the Navigation Bar (through adding pseudo-class :hover, and a box-shadow) to increase accessibility and include Madagascan flag colours.  This section allows users to easily navigate between pages and therefore enhances the UX of MadaGuide.
![MadaGuide Navigation image](documentation/madaguide-nav.png)


### Hero/landing image ###

The landing includes a stunning photograph of the Avenue of the Baobabs at sunset. This is regarded as Madagascar’s most iconic tourist attraction and has been used to capture the attention of users. It is immediately clear to users what they can expect to see if they plan a tour with MadaGuide.
I tested using an image tag with the CSS attribute object-fit: contain, to display the entire image across all devices, however I needed to limit the height to ensure the heading was above the fold. 
![MadaGuide Hero image](assets/css/images/avenuebaobabs-unsplash.jpg)

### Reasons section ###

The reasons section allows the user to see the benefits of using MadaGuide to plan and book their tour of Madagascar. This section shows them why it is an amazing country to visit, why Madaguide are a great company to book with due to their local knowledge and years of experience. It also offers them testimonials from previous customers who highly praise MadaGuide. 
Icons have been used on each heading to improve the aesthetic of this text section, alongside a background image of a lemur to encourage users to read this section. Lemurs are endemic to the island of Madagascar and will most likely feature on any planned trip by MadaGuide. The image is designed responsively to maximise space on each screen size. 
![Madaguide Reasons image](documentation/madaguide-reasons.png)

### Footer ###

The footer gives the user links to relevant social media sites to connect with MadaGuide and view their social media content. The links have recognisable social media icons for Facebook, Instagram and X that open to a new tab to allow for easy navigation. 
Like the header and navigation section, the footer is identical on each page to ensure uniformity and allow the user to access these links across any page.
![MadaGuide footer image](documentation/madaguide-footer.png)

### Itineraries ###

The itineraries provide the user a range of options they can book with MadaGuide. The user can see exactly what experiences the itineraries offer, and what is included or not included when booking a tour. I created three different itineraries to show the range of experiences users can have when planning a trip with MadaGuide. These tours in the itineraries can be booked, or users can take inspiration from them and book a bespoke trip with MadaGuide too. 
An image of a 4WD has also been included to allow users to understand the type of vehicle that is used for each of these trips and get a sense of the adventure that awaits. 

![MadaGuide Itinerary 1](documentation/madaguide-itinerary1.png)


### Contact Us Form ###

The Contact Us page allows the user to get in touch with MadaGuide to plan their trip to Madagascar. The form requires users to submit their first name, last name and email address. All fields are required, and once submitted users are directed to the Thank You page which ensures they know the form has successfully been submitted, and MadaGuide will be in touch soon. 
The form submit button uses the bright colour (Madagascar-red) to show this is a CTA and both the form and submit button are responsive across devices. 
![MadaGuide Contact Us Form](documentation/madaguide-contact.png)

## Tools and Tech Used ##

## Testing ##

## Deployment ##

## Credits ##

## Acknowledgements ##  
