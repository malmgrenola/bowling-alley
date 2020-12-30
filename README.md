# Bowling Alley

Website for a bowling alley where the site's users are customers that would like to bowl and eat.

#### Table of Contents

[UX](#ux)

[Features](#features)

- [Existing Features](#existing-features)
- [Features Left to Implement](#features-left-to-implement)

[Technologies Used](#technologies-used)

[Testing](#testing)

- [Known issues](#known-issues)

[Deployment](#deployment)

[Credits](#credits)

- [Content](#content)
- [Media](#media)
- [Acknowledgements](#acknowledgements)

## UX

The site owners goal is to get more lane bookings and dinner reservations & present the alley and its services to the potential customers.

The website's typical user is a young to midage customer with their cellphone that would like to do activities with friends later the same day or near future.
Another category is a typical midage person, with children, using the website on the computer and would like to arrange a children birthday party or bowl with friends.

- As a customer I would like to see avalible activities and book them, for a great evening out.
- As a user, I want to book a children birthday party, so that I be ensured that my child with friends get a great party.
- As a user I can find to all avalible social media platforms
- as a user I would like to find all contact information so I can locate and contact the company.

Site wireframes are linked within this document.
A collection of all wireframes created can be found in [WIREFRAMES.md](WIREFRAMES.md)

## Features

The wesite contains a clear navigation on every page.
The site is based on a navigational hierarchical tree structur.
Navigation bar is responsive and will fold down to a burger menu when it wont fint the size.

[Navigation bar wireframe example](docs/wireframes/wf-navigation.png)

- Navigation items:
  - Home (logo)
  - Bowling
  - Billiards/Snooker
  - Find us
  - Resturant
  - Booking

Each page includes a footer element containing all the neccesary information needed at a glance for the user. This would include links to social media platforms, address information & opening hours.
Additional elements such as booking rules download, gdpr information, vacancy Section can also be found in the footer.
The footer element is responsive and should flow with the device screen size.
[Footer wireframe example](docs/wireframes/wf-footer.png)

- Footer items:
  - Opening hours
    - Sunday to Thursday 13:00 to 22:00
    - Friday to Saturday 13:00 to 02:00
    - Holidays 13:00 to 02:00
  - Find us
    - Address (link to map)
    - phone
    - email
    - Contact us
  - Social
    - Facebook
    - Instagram
    - Twitter
    - Youtube
    - Tripadvisor
    - Linkedin

Each page needs a hero image acting as identification for the section.
[Hero wireframe example](WIREFRAMES.md#general-layout)

![Index layout](docs/wireframes/wf-index.png)
Index layout

Selected Typfaces:

- Logo: **Playball**, cursive
- Header: **Lato**, sans-serif
- Text: **Raleway**, sans-serif

The sites color schema wireframe

![color schema examples](docs/wireframes/wf-color.png)

### Existing Features

- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

- Showcase photos of people having fun bowling and inspire people to book their own time.
- Provide details about upcoming scheduled events.
- Provide information on the [bowling alley's location](https://www.google.com/maps/place/Radiator+Spring+Gas/@35.529041,-113.2315159,763m/data=!3m1!1e3!4m8!1m2!2m1!1sradiator+springs!3m4!1s0x0:0x2fdf6e3aedfaf45d!8m2!3d35.528886!4d-113.2313894), opening hours, contact details and any external resources.
- Bowling alley products
  - Bowling section - allows users to see prices and navigate to booking form
  - Billiards/Snooker section
  - Resturant section, Could be split up in Lunch, Dinner, etc
  - Children's birthday party Section
- Download booking rules
- Booking form
- Newsletter signup

### Features Left to Implement

- Lane online data presented on site.
- Live site chat with booking possibilities.
- Provide company historical information.
- vacancy section
- Better map intergration
- Tripadvisor reviews and links

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML5]()
- [CSS]()
- [Bootstrap]()
  - Grid feature is used to help layout the website.

## Testing

All HTML and CSS is validated with [W3C Validator](https://validator.w3.org/)

As specified in [User's guide for the W3C Markup Validator](https://dev.w3.org/validator/htdocs/docs/users.html) calls can be made to the validator.

The validation process of this site can be done by validating each page url in this list:

- [validate index.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Findex.html)
- [validate style.css](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Fassets%2Fcss%2Fstyle.css)

Amazon Devie Farm is used for devie testing
Selected devices is tageted:

- Samsung Galaxy A40 (OS 9.0)
- Samsung Galaxy S9 (OS 8.0.0)
- Samsung Galaxy Tab S4 (OS 8.1.1)
- Apple iPhone 11 (OS 13.1.3)
- Apple iPad Pro 11 (OS 12.1)
- Apple iPhone 12 Pro Max (OS 14.3)
- Apple Macbook Pro ([Chrome](https://www.google.com/chrome/), [Safari](https://www.apple.com/safari/), [Firefox](https://www.mozilla.org/en-US/firefox/new/))
- Azus ZenBook ([Chrome](https://www.google.com/chrome/), [Microsoft Edge](https://www.microsoft.com/en-us/edge), [Firefox](https://www.mozilla.org/en-US/firefox/new/))

Login's for accounts to Device services [1Password](https://1password.com)
Please contact [Ola Malmgren](mailto:malmgrenola@gmail.com) for access.

Itterate all user stories in the UX Section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

No automated Tests is setup for this project.

1. Layout:
   1. Navigate to the Main Page And confirm layout.
   2. [Add all Layouts] layout.
   3. Confirm Header & Footer on all pages.
2. Contact form:
   1. Go to the "Find us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

This section mentions how the project looks and works on different browsers and screen sizes.

### Known issues

This section also mentions any interesting bugs or problems you discovered during the testing, also not addressed items.

#### 1 - Social Links

Social icons & links on site has the url's set to generic social media sites and not to any propper social account.

#### 2 - Contact Form

Contact form ends on code Institute "form dump" endpoint and does not redirect correctly to the site with propper feedback.

<!--
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.
-->

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

- Fonts for the website (Raleway, Lato, Playball) is provided from [Google Fonts](https://fonts.google.com/)

- Color inspiration from [Adobe Color](https://color.adobe.com/), [ColorSpace](https://mycolor.space/) & [colormind](http://colormind.io/)
- Wireframes built using [Balsamiq](https://balsamiq.com/)
- The navbar consists modified examples from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/components/navbar/)
- Icons used are linked from [Fontawesome](https://fontawesome.com/)
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)
-

### Media

- The photos used in this site were obtained from ...
- https://www.pexels.com/sv-se/foto/aktivitet-blixtnedslag-boll-bowling-4192/
- https://www.pexels.com/sv-se/foto/blixtnedslag-bowling-bowling-stift-inomhus-344029/
- https://www.pexels.com/sv-se/foto/ljus-mode-man-ansiktslosa-5743695/
- https://unsplash.com/photos/yk2VUa5vtA0
- https://unsplash.com/photos/IoBCIosXkH8
- https://unsplash.com/photos/m4o5RuY1waY
- https://unsplash.com/photos/rrHl2zGZ9E4
- https://www.stockvault.net/photo/203821/bowling-alley
- https://www.stockvault.net/photo/236858/bowling-alley
- https://pixabay.com/photos/bowling-pins-ball-playing-alley-596766/
- https://www.pexels.com/sv-se/foto/sallskapsspel-bollar-skarpedjup-biljard-2017868/
- https://www.pexels.com/sv-se/foto/person-hander-kvinna-flicka-2705756/
- https://www.pexels.com/sv-se/foto/bbq-biff-flask-gourmet-675951/
- https://unsplash.com/photos/ND_kgsnEIeY
-
-

### Acknowledgements

- I received inspiration for this project from X
- https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/
