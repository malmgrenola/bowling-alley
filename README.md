# Bowling Alley

Website for a bowling alley where the site's users are customers that would like to bowl and eat.

#### Table of Contents

[UX](#ux)

[Features](#features)

- [Existing Features](#existing-features)
  - [Site content](#site-content)
  - [Style Information](#style-information)
- [Features Left to Implement](#features-left-to-implement)

[Technologies Used](#technologies-used)

[Testing](#testing)

- [Known issues](#known-issues)

[Development & Deployment](#development--deployment)

[Credits](#credits)

## UX

The site owners goal is to get more lane bookings and dinner reservations & present the alley and its services to the potential customers. The current avalible activities is bowling, billiards, birtday party bowling & eat & drink in the restaurant.

The website's typical user is a young to midage customer with their cellphone that would like to do activities with friends later the same day or near future.
Another category is a typical midage person, with children, using the website on the computer and would like to arrange a children birthday party or bowl with friends.

- As a customer I would like to see avalible activities and book them, for a great evening out.
- As a user, I want to book a children birthday party, so that I be ensured that my child with friends get a great party.
- As a user I can find to all avalible social media platforms
- as a user I would like to find all contact information so I can locate and contact the company.
- as a user I can find the restaurant meny.
- as a mobile user I can quickly find links to social media accounts so I can stay up to date on any platform.

Site wireframes:

- [Index page](docs/wireframes/wf-index.png)
- [Activities page](docs/wireframes/wf-activities.png)
- [Find us page](docs/wireframes/wf-findus.png)
- [Restaurants page](docs/wireframes/wf-restaurant.png)
- [Bookning page](docs/wireframes/wf-booking.png)

## Features

The wesite contains a clear navigation on every page.
The site is based on a navigational hierarchical tree structur.
Navigation bar is responsive and will fold down to a burger menu when it wont fit the size.
On mobile (samll screen) devices hamburger menu should contain quick access to social media links.
Current page is highlighted in the navigation bar.

[Navigation bar wireframe example](docs/wireframes/wf-navigation.png)

- Navigation items:
  - Home (logo)
  - Bowling
  - Billiards/Snooker
  - Find us
  - Restaurant
  - Booking

Each page includes a footer element containing all the neccesary information needed at a glance for the user. This would include links to social media platforms, address information & opening hours.
Additional elements such as booking rules download, gdpr information, vacancy Section could also be found in the footer at a later stage.
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
  - Social
    - Facebook
    - Instagram
    - Twitter
    - Youtube
    - Tripadvisor
    - Linkedin

Each page needs a hero image acting as identification for the section.
Where needed the hero image also contains the page header.

### Existing Features

- Provide information on the [bowling alley's location](https://www.google.com/maps/place/Radiator+Spring+Gas/@35.529041,-113.2315159,763m/data=!3m1!1e3!4m8!1m2!2m1!1sradiator+springs!3m4!1s0x0:0x2fdf6e3aedfaf45d!8m2!3d35.528886!4d-113.2313894), opening hours & contact details.
- Bowling alley activities
  - Bowling section - allows users to see prices and navigate to booking form
  - Billiards section - allows users to see prices and navigate to booking form
  - Children's birthday party Section
- Restaurant section - allows users to see menu
- Booking form
- Newsletter signup

#### Site content

##### Bowling content

Here at Bowling Alley you and your friends can enjoy bowling on the greatest lanes with the finest equipment.
All our lanes are oiled daily to max out your bowling experience. Our bowling balls span from the lightest 6lb to the heaviest 14lb with grip sizes all the way from XXS to XXL and we have all sizes of shoes you would ever need. For the youngest the shoes are velcro fastening ones.

Price per lane and hour is **USD 35**. max 6 people per lane and shoes are included in the price.

It is possible to order drinks and snacks from the bar at any time.
Water is always available without charge.

**Book your bowling today!**

##### Bowling birthday party content

Book the awesome birthday party here at Bowling Alley. We will make the party fantastic, fun, easy and unforgettable!
The kids get unlimited bowling, unlimited drinks and unlimited snacks during the birthday event.
There is always a dedicated Party Host available.

Price per birthday party is **USD 25** per person.

**Book a birthday party today!**

##### Billiards content

Enjoy classic billiards! On Bowling Alley you can play billiards and Snooker. Table's and accessories have the highest available standard.

Price per table is **USD 35**. max 4 people can play per table.

It is possible to order drinks and snacks from the bar at any time.
Water is always available without charge.

**Book a table now!**

##### Find us content

Bowling Alley
115 AZ-66, Seligman,
AZ 86337
USA

Phone: 555 123 456
Email: fun@bowlingalley.not

[maplink](https://maps.googleapis.com/maps/api/staticmap?center=Seligman,+Arizona+86337,+USA/@35.5295059,-113.2333092,889m/data=!3m2!1e3!4b1!4m12!1m6!3m5!1s0x0:0x2fdf6e3aedfaf45d!2sRadiator+Spring+Gas!8m2!3d35.5288858!4d-113.2313893!3m4!1s0x80cd050269ced2e9:0xb8f756f748e0b206!8m2!3d35.5295262!4d-113.2314753&size=400x200&scale=2&format=png&key=AIzaSyDtEf1XrnrAJYLbOolhUng71M01typu1Yo+)

##### Restaurant content

**Dine**
Never be hungry! Our restaurant offers menus that will leave you speechless.
Try our burgers or chicken wings!
Our restaurant is Open!
**Download menu**

**Wine**
You can always find a good spot for a glass of wine in our bar area.
The selection of good wines is frequently updated but we always keep your favourites available.
**Download menu**

#### Style Information

##### Selected Typfaces:

- Logo: **Playball**, cursive
- Header: **Lato**, sans-serif
- Text: **Raleway**, sans-serif

##### Color Schema

The sites color schema wireframe

![color schema examples](docs/wireframes/wf-color.png)

```
/* Bowling alley colors */
.bowling-ally-1-hex {
  color: #3f0061;
}
.bowling-ally-2-hex {
  color: #003c61;
}
.bowling-ally-3-hex {
  color: #18614a;
}
.bowling-ally-4-hex {
  color: #613901;
}
.bowling-ally-5-hex {
  color: #61291a;
}
```

### Features Left to Implement

- Add footer elements such as booking rules download, gdpr information, vacancy Section.
- Propper backend for newsletter signup & booking form

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML5](https://www.w3.org/TR/html52/)
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
- [Bootstrap](https://getbootstrap.com/)
  - Grid feature is used to help layout the website.
  - Modal is used to catch forms, since forms backend is not implemented yet
- [Google Maps static API](https://developers.google.com/maps/documentation/maps-static)
  - For the find us map (key is restricted)

## Testing

All HTML and CSS is validated with [W3C Validator](https://validator.w3.org/)

As specified in [User's guide for the W3C Markup Validator](https://dev.w3.org/validator/htdocs/docs/users.html) calls can be made to the validator.
This site validator test are specified below in this section.

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

1. Validator tests, confirm no errors on each file listed.

   1. [validate style.css](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Fassets%2Fcss%2Fstyle.css)
   2. [validate index.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Findex.html)
   3. [validate activities.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Factivities.html)
   4. [validate booking.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Fbooking.html)
   5. [validate findus.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Ffindus.html)
   6. [validate landing-booking.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Flanding-booking.html)
   7. [validate landing-newsletter.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Flanding-newsletter.html)
   8. [validate restaurant.html](http://validator.w3.org/check?uri=https%3A%2F%2Fmalmgrenola.github.io%2Fbowling-alley%2Frestaurant.html)

2) Layout & External links:
   1. confirm that the user can see and book all avalible activities (including birthday party) on `activities.html`, `index.html` & `landing-newsletter.html` in the activities section.
   2. confirm all social media icons correctly linked and opens a blank page on `footer` section on every page, `findus.html` & the hamburger menu on a mobile device.
   3. confirm correct opening hours on `index.html` in the opening hours section & on `footer` section on every page.
   4. confirm correct contact information and links (street, tel & email) opens a blank page on `footer` section on every page, `findus.html` & `index.html`.
   5. confirm correct download of menu & that it opens a blank page on `restaurant.html`
   6. confirm that there is no missing images on all pages (use devtools / network).
3) Forms:
   1. navigate to local `index.html` -> newsletter signup section.
   2. confirm that faulty address feedbacks error to the user.
   3. confirm that submit takes user to `landing-newsletter.html`
   4. navigate to local `booking.html`.
   5. confirm faulty input in all form elements.
   6. confirm that submit takes user to `landing-booking.html`
4) Lighthouse Scoring
   1. open devtools / lighthouse in google chrome and press "Generate report" for Desktop device & Mobile Devices.
   2. Confirm results and correct if needed.

### Known issues

This section mentions interesting bugs or problems discovered during the testing, also not addressed items.

#### 1 - Social Links

Social icons & links on site has the url's set to generic social media sites and not to any propper social account.

#### 2 - Newsletter & Booking form Form

Newsletter signup & booking form ends up in on a fake landing page & nothing is sent to server side at all.

#### 4 - Address information

All address, email & phone information on website is a fake.

#### 5 - Download menu

The menu is currently without propper content.

#### 6 - switch between landscape and portait

On some devices the switch between landscape and portait missaligns the scrollbar.

#### 6 - CSS Warnings

`-moz-transition`,`-webkit-transition` & `-o-transition` is still in `style.css` file even if it seems like they could most likley be removed.

Based on comments, for example [here](https://stackoverflow.com/questions/52490004/what-are-all-of-these-w3c-css-validation-warnings-about) and the fact that `code institute` keeps them in their examples, decision is to not remove code at this point.

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

## Development & Deployment

Development on this site happens primary on branch [main](https://github.com/malmgrenola/bowling-alley/tree/main).
branch [main](https://github.com/malmgrenola/bowling-alley/tree/main) also acts as staging enviorment.

If you would like to contribute please fork repo and open pull requests.
Before opening pull requests, please confirm all items in [Testing](#Testing) section in this document.

Deployment is done by opening a Pull Request and merge to branch 'production'.

This site is currently deployed with gitHub Pages.
The branch 'production' and the "/(root)" folder is used.
Deployment url: https://malmgrenola.github.io/bowling-alley/

How to deploy is found [here](https://pages.github.com/).

local development can be previewed as local files in browser without any http-server.

### Tools

Any text IDE can be used. [Atom](https://atom.io/) (with [prettier](https://atom.io/packages/prettier-atom)) is recomended.

[Adobe Photoshop](https://www.adobe.com/se/products/photoshop.html) is used to enhance and optimize images.
[Adobe Illustrator](https://www.adobe.com/se/products/illustrator.html) is used to design and export menu to pdf.

## Credits

### Content

- Fonts for the website (Raleway, Lato, Playball) is provided from [Google Fonts](https://fonts.google.com/)
- Color inspiration from [Adobe Color](https://color.adobe.com/), [ColorSpace](https://mycolor.space/) & [colormind](http://colormind.io/)
- Wireframes built using [Balsamiq](https://balsamiq.com/)
- The navbar consists of modified code examples from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/components/navbar/)
- Icons used are linked from [Fontawesome](https://fontawesome.com/)

### Media

The photos used in this site were obtained from:

- [pexels-skitterphoto-4192.jpg](https://www.pexels.com/sv-se/foto/aktivitet-blixtnedslag-boll-bowling-4192/)
- [pexels-matthias-zomer-344029.jpg](https://www.pexels.com/sv-se/foto/blixtnedslag-bowling-bowling-stift-inomhus-344029/)
- [derek-martin-m4o5RuY1waY-unsplash.jpg](https://unsplash.com/photos/m4o5RuY1waY)
- [pexels-tomaz-barcellos-2017868.jpg](https://www.pexels.com/sv-se/foto/sallskapsspel-bollar-skarpedjup-biljard-2017868/)
- [pexels-elina-sazonova-2705756.jpg](https://www.pexels.com/sv-se/foto/person-hander-kvinna-flicka-2705756/)
- [pexels-snapwire-675951.jpg](https://www.pexels.com/sv-se/foto/bbq-biff-flask-gourmet-675951/)
- [ray-reyes-ND_kgsnEIeY-unsplash.jpg](https://unsplash.com/photos/ND_kgsnEIeY)
- [pexels-cottonbro-5018987.jpg](https://www.pexels.com/sv-se/foto/natt-vanner-middag-bord-5018987/)
- [pexels-rajesh-tp-1633578.jpg](https://www.pexels.com/sv-se/foto/brod-bullar-burger-kott-1633578/)
- [pexels-samaraagenstvo-feeria-2399097.jpg](https://www.pexels.com/sv-se/foto/barn-fest-firande-flickor-2399097/)
- [pexels-gratisography-519.jpg](https://www.pexels.com/sv-se/foto/annons-ljus-neon-reklam-519/)
- [brittani-burns-MdN5h3QCiTw-unsplash.jpg](https://unsplash.com/photos/MdN5h3QCiTw)
- [luana-azevedo-Wv6xmYikFFQ-unsplash.jpg](https://unsplash.com/photos/Wv6xmYikFFQ)

The Download menu feature were obtained from:

- https://www.freepik.com/free-vector/restaurant-menu-template_787035.htm

### Acknowledgements

I received inspiration for this project from:

- https://www.hollywoodbowl.co.uk/
- https://www.strikebowling.com.au/
- https://www.amf.com/
- https://pinstackbowl.com/
- https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/
- https://stackoverflow.com/questions/39367946/duplicate-an-element-and-overlay-it-using-css
