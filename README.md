# Dental Care

## Overview 

This project is designed to highlight the services of a fictional Dental Practice.
Using HTML & CSS the aim is provide an overview of the practice, the services on offer and testimonials from existing customers.
The purpose of the web page is to attract new customers and provide an efficient website for existing customers to request new appointments.


## UX 

### Project Goals

The main goal of DentalCare is to provide an informative and concise site for prospective customers who are looking for a reliable local dentist. The site is also designed to provide a way for existing customers to request an appointment for various dental services remotely.
DentalCare there is aimed at to main audiences: New and/or Existing Customers.

#### New Customer goals are:

- Informative Site.
- Comprehensive Services.
- Clearly Presented Information.
- Evidence of Customer Satisfaction.
- Clear Form to provide contact details.

#### Existing Customer goals are:

- Site that is intuitive to navigate.
- Quick review of existing services available.
- Hassle free ability to request an appointment.

#### DentalCare addresses these goals by:

- Following a clearly defined step-by-step design philosphy from initial concept right through to deployment.
- Having visual queues to site specific information.
- Clear indication on highlighted/clickable links.
- Information being presented in concise manner.
- Uniform design across the site.
- Site presented in a manner consisted with clinical feel.

#### Developer and Business Goals

- Development of a site that is visually consistent with customer expecations of a Dental/Clinical setting.
- Encourage prospective and existing customers to engage with the business.
- Display of ability to build a site using HTML, CSS & Bootstrap.
- Ensure that site is fully responsive using the mobile-first design philosophy.
- Customising technologies used to give site a unique feel.


### User stories

#### As a visiting customer I would:

1. Want to be able to nagivate through the website intuitively.
2. Need to be able to quickly review the dental services available to see if they are appropriate to my needs.
3. Want to be able to view the site across multiple devices e.g. while not at home on desktop or laptop.
4. Like to review any existing customer feedback.
5. Want the site to be consistent with visual feedback across the site indicating mouseover/cursor behaviour.
6. Want to contact dental care for any business related enquiries.

#### As an admin user I would:

1. Want the site to address the business goals.
2. Need to easily redevelop the site should any individual section needs updating.
3. Code that was easy to read and understand.
3. Be able to share the repository for collaborative purposes.

### Design Choices

The overall feel of the site is one designed to present both professionally and provide a clinical feel. As a result the design choices are detailed below:

#### Fonts

The main font used is Roboto this font family was chosen for its readability across desktop and mobile devices.

The secondary font is sans serif and this is used as a generic font where Roboto is not available.

#### Icons 

- These icons used were for their relatability to the corresponding headings so they can be universally understood.

#### Colours

- The colours chosen are of an pale torqouise color on grey for the nav bar, text and links/buttons. These were chosen as they contrast well and are consistent with providing a clinical feeling.

#### Styling

- Images, links and buttons were rounded to give a softer overall presentation as opposed to sharp edges.

#### Wireframes

Wireframes were created using Balsamiq as part of the planning process.

Link: [Wireframes](/assets/Wireframes/MilestoneProject1.bmpr)


## Features 

### Existing Features

- Navigation Bar: Collapsable for use across devices of smaller screen sizes i.e. smart phones.
- Navigation Bar: **Sticky** to remain at the top of the page when scrolling down through the site.
- Main Page: About us section with quick overview of the other pages on the site.
- Services Page: Highlighting the types of dental services available, with links to testimonials and contact us page.
- Testimonials Page: Highlighting recent customer reviews, with links to services and contact us page.
- Contact Us Page: Form fillable contact page allowing customers to get in touch while leaving contact details.
- Footer: Fully responsive footer with full business contact details included as well as links to respective social media sites.

### Features Left to Implement

- Services Page: Modal for each service allowing for detailed expansion on services offered.


## Technologies Used

* HTML5 - A markup language used to organise and define the content to be displayed.
* CSS3 - Style sheet language use to style the presentation of content detailed in the markup language.
* [Bootstrap](https://getbootstrap.com/) - A CSS framework use to develop fully responsive mobile-first site.

## Testing

### Features

* Navigation bar is collapsable across smaller devices.
* Navigation bar expands correctly and navigation links work.
* Navigation bar is stuck to the top when scroll down on all pages.
* All links (navigation, body text and social media) work.
* Hover effect displays correctly in body text links, contact us form and social media links.
* Images correctly resize and stack correctly across smaller screen sizes.
* Body text on Features Testimonials pages correctly stack across smaller screen sizes.
* Footer correctly positioned at bottom of page and responsive across smaller screen sizes stacking in the correct order.
* Contact Us Form does not accept submission unless required details are inputted i.e. Name, Email and Contact Number, whereas free text area is optional.

### Validation

* W3C Markup validation - No errors found.
* V3C CSS validation - No errors found.
* Lighthouse (ChromeDevtools).

### User Stories Testing from UX section

#### As a visiting customer I would:

1. Want to be able to nagivate through the website intuitively.
    1. Website has navigation bar included with collapsable menu for smaller screen sizes.
    2. Navigation menu has related icons which are also displayed on corresponding pages.
    3. Navigation bar sticks to top of screen when scrolling for ease of use.
    4. Home Page displays information clearly and has a short expansion of menu items below picture.
    5. Menu items are darker when on the active page.
    6. Visual effect created for site links and submit button.
    7. Social media hover effect for social media links with their corresponding brand colours.
2. Need to be able to quickly review the dental services available to see if they are appropriate to my needs.
    1. Link to services page can be found on navigation bar and as left hand link on main page.
    2. List of services displayed both broadly and with bullet pointed detail.
3. Want to be able to view the site across multiple devices e.g. while not at home on desktop or laptop.
    1. Site has been designed with a mobile-first design philosophy using Bootstrap alongsite the HTML and CSS.
4. Like to review any existing customer feedback.
    1. Testimonials section given it's own page and highlighting recent customer reviews to enhace customer confidence.
5. Want the site to be consistent with visual feedback across the site indicating mouseover/cursor behaviour.
    1. Clickable links and the submit button on contact us page display the same visual cue of the curved bar filling up on mouseover/click.
    2. Spacing of images and white space consistent throughout the site across a range of devices.
6. Want to contact dental care for any business related enquiries.
    1. Contact Us form on contact page provided and fully responsive across all mobile devices tested in Chrome Browser.

#### As an admin user I would:

1. Want the site to address the business goals.
    1. Colour scheme selected to be consistent with business with a healthcare setting.
    2. Site details services and testimonials both with links to contact us form requesting the customer to get in touch.
    3. Contact us form does not allow submission until contact details are supplied i.e. Name, Email and Phone Number allowing the business to get back in touch with the customer.
    4. Site coded in HTML and CSS and Bootstrap framework used to make the site fully responsive with mobile-first design philosophy.
    5. Site tested for it's responsiveness in Chrome Browser across mobile devices listed and for its responsiveness at varying desktop resolutions.
    6. Custom CSS code added to customise content from Bootstrap e.g. Submit Button.
2. Need to easily redevelop the site should any individual section needs updating.
    1. Main sections HTML and CSS separated by commented code.
3. Code that was easy to read and understand.
    1. HTML and CSS used standard markup and syntax.
    2. HTML and CSS has been arranged using **Alt+Shift+F**
3. Be able to share the repository for collaborative purposes.
    1. Detailed in deployment section.

### Bugs

1. Significant whitespace found beneath footer when viewing on iPad Project
- Resolution added in min-height value to css


## Deployment

This project was developed using the GitPod IDE, committed to git and pished to GItHub using the built in function within GitPod.

To deploy this page to GitHub Pages from it's GitHub repository, the following steps were taken:

1. Log into GitHub.
2. From the list of repositories on the screen, select SamiIshmael/DentalCare.
3. From the menu items near the top of the page, select Settings.
4. Scroll down to the Github Pages section.
5. Under Source click the drop-down menu labelled None and select Master Branch.
6. On selection Master Branch the page is automatically refreshed, the website is now deployed.
7. Scroll back down to the GitHub Pages section to retrieve the link to the deployed website.

At the time of submitting this Milestone project the Development Branch and Master Branch are identical.

### How to run this project locally

To clone this project into Gitpod you will need:

1. A GitHub account. [Create a GitHub account here](https://github.com/).
2. Use the Chrome browser.

Then follow these steps:

1. Install the [Gitpod Browser Extensions for Chrome](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki?hl=en).
2. After installation, restart the browser.
3. Log into Gitpod with your gitpod account.
4. This project uses the **Code Institute Student Template** found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
5. Click **Use this template** and give your repository a name.
6. Navigate to the [Project GitHub repository](https://github.com/SamiIshmael/DentalCare).
7. Click the green "Gitpod" button in the top right corner of the repository.
8. This will trigger a new gitpod workspace to be created from the code in github where you can work locally.
9. To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:<br /> `python3 -m http.server`<br />
10. A blue button should appear to click: Make Public,
11. Another blue button should appear to click: Open Browser.

To clone this project from Github:

1. This project uses the **Code Institute Student Template** found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
2. Click **Use this template** and give your repository a name.
3. Follow this link tot he [Project GitHub repository](https://github.com/SamiIshmael/DentalCare).
4. Using the right hand menu click the Code drop-down and select either "Clone" or "Download".
5. Selecting the Clone HTTPs section, copy the clone URL for the repository.
6. In your local IDE open Git Bash.
7. Change the current working directory to the location where you want the cloned directory to be made.
8. Type `git clone`, and then paste the URL you copied in Step 3.
9. To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:<br /> `python3 -m http.server`<br />
10. A blue button should appear to click: Make Public,
11. Another blue button should appear to click: Open Browser.

## Credits

### Media

#### Icons

* [House](https://fontawesome.com/icons/home?style=solid), [Tooth](https://fontawesome.com/icons/tooth?style=solid), [Comments](https://fontawesome.com/icons/comments?style=regular) and [Telephone](https://fontawesome.com/icons/phone?style=solid) icons all sourced from [Font Awesome](https://fontawesome.com/).
* Social Media icons for [Facebook](https://fontawesome.com/icons/facebook?style=brands), [Twitter](https://fontawesome.com/icons/twitter?style=brands) and [YouTube](https://fontawesome.com/icons/youtube?style=brands) all sourced from [Font Awesome](https://fontawesome.com/).

#### Images

All images sourced from [PX Fuel](https://www.pxfuel.com/)
* [Dentist.jpg](https://www.pxfuel.com/en/free-photo-oiviq)
* [GeneralDentistry.jpg](https://www.pxfuel.com/en/free-photo-jrquy)
* [SpecialistDentistry.jpg](https://www.pxfuel.com/en/free-photo-osxgt)
* [TeethWhite.jpg](https://www.pxfuel.com/en/free-photo-ovtgf)
* [Smile1.jpg](https://www.pxfuel.com/en/free-photo-jvyxv)
* [Smile2.jpg](https://www.pxfuel.com/en/free-photo-jqgpd)
* [Smile3.jpg](https://www.pxfuel.com/en/free-photo-jmbnf)
* [contact.jpg](https://www.pxfuel.com/en/free-photo-qlldn)

#### Colours

Brand colours for social media (Facebook,Twitter and YouTube) mouseover effects were obtained from [US Brand Colors](https://usbrandcolors.com/)

#### Content

* [Hover.css](https://ianlunn.github.io/Hover/) Used for Link and Button sweep effect.
* Grey sub-heading divider code was obtained from [Codepen.io](https://codepen.io/scottzirkel/pen/yNxNME).
* [Autoprefixer](https://autoprefixer.github.io/) was used for CSS.

### Acknowledgements

Thanks to my mentor Rohit Sharma for his guidance and support during my project.