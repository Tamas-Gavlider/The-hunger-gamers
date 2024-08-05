
# Hunger Gamers

Hunger Gamers is a responsive website allowing users to view on range of devices.<br> The purpose of the page is to get people together and  have a few carefree hours while playing video games and enjoying our delicious food. The weekend events will guarantee the fun for everyone.

![Responsivenes](/docs/testing/Screenshot%202024-08-03%20at%2012.47.14.png)

[View Hunger Gamers on Github Pages](https://tamas-gavlider.github.io/The-Hunger-Gamers/)

## Web Page goal

* To be able to view the site on a range of device sizes.
* Create a community where gaming enthusiasts can come together.
* Provide details of the upcoming events.
* Offer delicious food.
* Connect people through social network platforms

## Design

The website uses black,red and yellow colours due to their strong visual impact <br>
and symbolic meanings:

* **Black:** Often associated with elegance, and modernity.
* **Red:** Conveys excitement, energy, and passion.
* **Yellow:** Represents happiness, optimism, and energy.

These colours together create a bold, and energetic vibe.

## Wireframe 

Wireframes were created for mobile, tablet and desktop.

[Home Page for phone and tablet](/docs/wireframe/Index.html%20phones&tablet.png)<br>
[Home Page for desktop](/docs/wireframe/Index%20desktop.png)<br>
[Menu](/docs/wireframe/Menu.png)<br>
[Events](/docs/wireframe/Events.png)<br>
[Registration](/docs/wireframe/Registration.png)

### Typography 

Google Font Silkscreen is being used for the website. The pixelated style used on<br>
webpage refers to classic video games, evoking nostalgia and retro feel.

### Images

All background images were downloaded from [Pexels.com](https://www.pexels.com).

### Features 

The website is comprised of four pages, three of which are accessible from the navigation menu (home page, menu page & registration page).<br>
The fourth page is a confirmation page which is shown once a user submits the form on the events page.
* All pages on the website have:
  * Fully responsive header with navigation links which allow the user to navigate through the site. The navigation links background color will change to yellow if the user hover over the navigation elements. The text Hunger Gamers is in the center of the page above the navigation links.<br>The navigation links to the websites pages (Home,Menu,Events) and the text Hunger Gamers will be visible on both cellphones and dekstops. This was implemented to keep the website design same/slightly different if user accessing the website on multiple devices. Less change in design will promote a good user experience.
  * A footer which contains social media links. The name of the social media platforms were used instead of the social media icons to keep the retro feeling with the pixelated fonts.
* Home page
  * With a Nintendo Nes console as background image.The first thing that user will notice is the console image and the text of "Speedruns & Game Marathons". 


## Technologies used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libraries & Programs Used 

Balsamiq - Used to create wireframes.

Git - for Version Control.

Github - To save and store the files for the website.

Google Fonts - To import the fonts used on the website.

Font Awesome - For the icon logo.

Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

[Am I Responsive?](https://ui.dev/amiresponsive) - To show the website image on a range of devices.

[Cloudconvert](https://cloudconvert.com/jpg-to-webp) - To convert images to webp format.

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
1. Find the repository for this project, The-Hunger-Gamers.
1. Click on the Settings link.
1. Click on the Pages link in the left hand side navigation bar under "Code and Automation".
1. In the Source section, choose main from the drop down select branch menu. Select Root  from the drop down select folder menu.
1. Click Save. Your live Github Pages site is now deployed at the URL shown.

## Local Development

**How to Fork**

To fork the The-Hunger-Gamers repository:

1. Log in (or sign up) to Github.
1. Go to the repository for this project, Tamas-Gavlider/The-Hunger-Gamers.
1. Click the Fork button in the top right corner.

**How to Clone**

To clone the The-Hunger-Gamers repository:

1. Log in (or sign up) to Github.
1. Go to the repository for this project, Tamas-Gavlider/The-Hunger-Gamers.
1. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
1. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
1. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

I have used Chrome Developer tool while building the web page and troubleshoot any issues immediately. 

The following issues were raised during my mid project meeting with my mentor:

   * The background images were not converted to webp format. Due to the image size the Lighthouse gave low performance score.  
   * The source code contained too many unnecessary whitespace.
   * The mentor brought to my attention that the "Last Name" input is not required on the Events page. It is not required on purpose. User might have a long last name so skipping that field can save them time. 

   ## W3C Validator

   The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file. No errors were found, however there was a warning sign due to the imported google font.
  * [Index HTML](/docs/testing/validator/Index.html-%20validator.png)<br>
  * [Menu HTML](/docs/testing/validator/Menu.html-%20validator.png)<br>
  * [Events HTML](/docs/testing/validator/Events.html-%20validator.png)<br>
  * [Registration HTML](/docs/testing/validator/Registration.html-validator.png)<br>
  * [CSS](/docs/testing/validator/CSS%20validator.png)<br>
  * [Warning sign](/docs/testing/validator/Warning%20sign.png)<br>

  ## Full Testing

  I performed the following testing using a number of browsers (google chrome, safari, mozilla firefox,edge) and devices (Macbook Pro 15 inch, iMac 21.5 inch, iPhone 11, iPhone 6s and a 15 inch Dell laptop).<br>
  I also went through each page using google chrome developer tools to ensure that they responsive on all different screen sizes.<br>
  [Tested screens](/docs/testing/Tested%20screen%20sizes.png)<br>
  Links:
  1. Test each link on the index page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the menu page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the events page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  1. Test each link on the registration page. Each link worked as expected, and any links leading to external pages opened correctly in a seperate browser tab.
  Registration form:
  1. I tried to submit the form without filling in any input fields. The form worked correctly and directed users to fill in the name field. I then filled in the name field and tried to submit the form. Again the form worked correctly and directed the user to fill out the email field. I filled out the name and email forms and tried to submit the form. The form worked correctly and asked the user to select one of the options from the radio button.










