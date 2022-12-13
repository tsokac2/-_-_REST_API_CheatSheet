<h1 align="center">New Irish Life</h1>

Web-based travel guide for providing correct information on how easily start living and working in Ireland.
Finding work, a place to stay where to buy good cheap food in Ireland can be difficult but with the correct preparation,
advice, and planning this task can be made a lot easier.
This website is a great starting point.

![Website Main Mockup](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Main.png)

## Table of Contents
* [User Experience Design (UX)](#UX)
    * [User Story](#User-Story)
    * [Design process](#Design-process)
* [Features](#FEATURES)
    * [Home](#HOME)
    * [Trip](#TRIP)
    * [Work](#WORK)
    * [Life](#LIFE)
    * [Tips](#TIPS)
    * [Sign Up](#SIGN-UP)
    * [Login](#LOGIN)
    * [Profile](#PROFILE)
    * [Add Tip](#ADD-TIP)

* [Technologies used](#TECHNOLOGIES-USED)
* [Testing](#TESTING)
* [Deployment](#DEPLOYMENT)
* [Credits](#Credits)

****

# UX

**Story:**
<h4 align="center">Four years ago, one Croatian landed in Dublin, Ireland. On the web, 
there was a lot of info about life in Ireland, but not essentials information in one place.
</h4>
<h3 align="center">Well, not anymore!</h3>

### User Story

**As a new Irish resident, I want all _NECESSARY AND IMPORTANT_ information for my [New Irish Life](http://new-irish-life-3-0.herokuapp.com/home) in one place and available from any device connected to the internet, so I can organize my life in a fun and simple way.**

**In the [Trip](http://new-irish-life-3-0.herokuapp.com/trip) section, I want to have quick access to the most popular online travel brands and quick links pointing me to _"FLIGHTS"_, _"HOTELS"_, _"CAR HIRE"_, and brands _" REVIEWS"_.**

**I the [Work](http://new-irish-life-3-0.herokuapp.com/work) section, I want to have quick access to the most popular recruitment websites and quick links pointing me to _"JOB SEARCH"_, _" EXPECTED SALARIES"_, _"COMPANIES"_ and agency _" REVIEWS"_.**

**I the [Life](http://new-irish-life-3-0.herokuapp.com/life) section, I want to have quick access to the most up-to-date rental website links pointing me to _"SHARE ROOMS"_, _"STUDENTS"_, _" APPARTMENT TO BUY"_, and holiday options, most popular mobile network providers, and most popular grocery shops.**

**Straight after arrival at Dublin Airport if I click on a [Trip](http://new-irish-life-3-0.herokuapp.com/trip) section I want to see Google Maps with some option for bus, train, or tram stations with visible markers in different colors for the fastest navigation.**

**I the [Tips](http://new-irish-life-3-0.herokuapp.com/tips) section,  I want to read posts from other users and their pieces of advice for the best traveling routes, work opportunities, study options, and good food places.**

**By frequently referring to New Irish Life content, I want to have the ability to [create](http://new-irish-life-3-0.herokuapp.com/registration) my profile for full New Irish Life usage.**

**In the [Sign Up](http://new-irish-life-3-0.herokuapp.com/registration) process, I want to have the ability to register with my Username, Email, and password-strength of my choice. During the registration process, I want to be alerted if my Username and Email are unique or already in use.**

**In the [Login](http://new-irish-life.herokuapp.com/login) process, I want to login with my Username and Password and be redirected to my Profile page with a welcoming message, where I can see my details: Username, Email, Join Date. I want to have an option to DELETE my profile with a pop-up warning and confirmation message.**

**When I log out I want to see a successful logout message and be redirected to the [Home](http://new-irish-life-3-0.herokuapp.com/home) page.**

**As an active user, I want to have the choice to create Tips from my experience living in Ireland and have an option for 4 categories: Trip, Work, Study, and Food. If I want to update my Tips I want to see an update or delete option for all of my posted tips.**

**As not an active user I want the ability to search [Tips](http://new-irish-life-3-0.herokuapp.com/tips) from other users with targeting tips title or tips description for specific keywords.**

**I want to stay up-to-date with all fresh information regarding work and lifestyle by subscribing to my email for newsletter services. I want to know if my email is valid when I'm submitting my request for newsletter services.**

**When I'm submitting my name and email for newsletter services I want to receive a message that my request is submitted with the confirmation message.**

**When I'm browsing through the website I want to access each URL directly so it feels like a single app website.**

**With [New Irish Life](http://new-irish-life-3-0.herokuapp.com/home), all of this is possible!**


### Testing User Stories from User Experience (UX)
* Definition by **HOME** section - As a First Time Visitor, I want to easily understand the main purpose of the site and my benefit of the [New Irish Life](http://new-irish-life-3-0.herokuapp.com/home):
  * Upon entering the site user can see a clear navigation bar and company logo.
  * The main purpose is represented with a short introduction paragraph and hero image gallery.
  * Website content is pointed with four visual design cards for each section of the site.
  * Footer is well structured and offers links for the main site section and full operating Newsletter form service.
  * Users can share [New Irish Life](http://new-irish-life-3-0.herokuapp.com/home) on four social media links presented in the bottom part of the footer.
  * The main navigation menu and footer are replicated through all main sections of the website.

* Definition by **TRIP** section - As a First Time Visitor, I want to easily understand section purpose with a short and fun intro paragraph and slide-show intro gallery:
  * Users can choose the most popular online travel brands to organize in card elements.
  * Each card element contains the main link, the brand website screenshot, the **_"Quick links..."_** option, and a brand description.
  * Users can have access to the best Irish public transportation services.
  * Users can navigate through embedded Google Map with colorful markers representing the most important bus stations, train stations, and tram stations in Dublin, Ireland.

* Definition by **WORK** section - As a First Time Visitor, I want to easily understand how to start a job search process with the best possible preparation for the Irish work market:
  * Users can quickly understand where to start the job search process.
  * Users can understand what kind of [CV](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/downloads/Tomislav%20Sokac_CV.pdf) template is necessary for a successful job search mission.
  * Users can find the best option for online education with the best offers.

* Definition by **LIFE** section - As a First Time Visitor, I want to easily find the best online rental marketplaces, the most popular mobile networks provider, and large-chain grocery shops
  * Users can choose one of the four most popular Irish online rental portals with quick links for share accommodation or buy options.
  * Users can quickly decide for best mobile network providers regarding broadband speed, bill pay offers, Tv broadband offers.
  * Users can check the four largest grocery shop chains with previous user reviews, best deals, work offerings.

* Definition by **SIGN UP** section - As a First Time Visitor, I want to see straight up what kind of details are needed for a successful registration:
  * By entering Username, the user can see if chosen Username is already taken or is below 2 characters, or it is completely valid.
  * By entering an Email address, the user can see if the email address is valid or already in use, or is completely valid.
  * By entering the password, the user must confirm the password for additional data security.

* Definition by **LOGIN** section - After the first successful registration, I want to be redirected to the login page and enter my username and password:
  * By entering the Username and password and if either input details are invalid, the user is receiving a warning message.
  * By entering the correct username and password the user is redirected to the profile page.

* Definition by **PROFILE** section - After the first successful login, I want to be redirected to my profile page: 
  * On the profile, page the user can see the following details: Username, Email, and Joining Date.
  * User has the choice to DELETE their profile.
  * If the user clicks on the DELETE button, a pop-up message is appearing for delete confirmation.
  * If the user clicks "YES" to confirm the delete process, the user is redirected to the HOME page with the message:  **_"Your profile is deleted!"_**.

* Definition by **TIPS** section - As a First Time Visitor, I want to easily read through other users tips and tricks regarding work, commuting, study options, and restaurants choices:
  * A user can search posts with keywords targeting tip title and tip description witch will result in redirecting to a search result page.
  * By focusing on tips categories titles, users can quickly navigate and read from desired column section.
  * If the user is logged in, users can **_Create_**, **_Update_**, and **_Delete_** tips.
  * When the user creat tip, the user is redirected to the **TIPS** section with the success message **_Tip successfully added!_**


### Design process
**1.** Draft all main sections - **HOME**, **TRIP**, **WORK**, **LIFE**, **TIPS**, **SIGN UP**, **LOGIN**, and **PROFILE**.

**2.** Brief list of all pop-ups and alert messages and their front-end placement.

**3.** List all color pallets - usage - background color, font color, border.

**4.** List all font styles for best UX, regarding user profile details, movie quotes, post titles, and descriptions.

**5.** A list of free images from the free-image web platforms for each project section.

**6.** Draft web-page layout using Adobe Photoshop and Balsamiq for the main layout and Adobe Illustrator for layout components such as Logo, borders, navigation elements.

**7.** List possible Fowtawesome Icon for best UX in picture experiences and a draft of custom icons.

**8.** Plan Python and Flask implementation into project root infrastructure folder.

**9.** List Semantic Mark-up to structure HTML code.

**10.** List CSS folder structure for SASS Pre-processor configuration.

**11.** List of preferable Python packages for best possible performance and UX. 

**12.** Plan database collections structure - user collection details, user tips collection details, and tips categories list

**13.** Plan and implement Google Maps API for orientation purposes.

**14.** Plan and implement Emailjs API service for Newsletter form.

**15.** Take notes for all major development issues, their solutions, challenges, project credits, and SLACK community guidance.


### Wireframes
* **HOME** section general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Home.png)
* **TRIP**, **WORK**, and **LIFE** sections general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Trip.png)
* **TRIP**, **WORK**, and **LIFE** - **_"Quick links"_** cards general idea for Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_MW.png)
* **TRIP GOOGLE MAPS** section general idea - for Large and Small screens devices [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Trip_Maps.png)
* **TIPS** section general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Tips.png)
* **SIGN UP** section general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Registration.png)
* **LOGIN** section general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Login.png)
* **PROFILE** section general idea - for Large and Small screens devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_Profile.png)
* **FOOTER** section general idea - for Small devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_MF.png)
* **MAIN MENU** section general idea - CSS Grid elements - for Small devices - [View](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/W3_MM.png)

### Main Layout
* MENU: HOME | TRIP | WORK | STUDY | TIPS  --LOGO--  SIGN UP | LOGIN - after user login - +TIPS | PROFILE | LOGOUT
* MAIN SECTIONS: Website features - HOME, TRIP, WORK, LIFE,  SIGN UP, LOGIN - +TIPS | PROFILE
* FOOTER: Footer Menu links - Newsletter Subtraction - Social Media links - Copyrights

****

# FEATURES

## HOME
Simple introduction of web page purpose and what value it is bringing to an end-user.

Formatted in three main sub-sections:
* Movie reference pitch - from -  _"The Hobbit: An Unexpected Journey"_
* Welcoming **_"Hero"_** area with picture composition
* Quick box-model overview of the web page main sections
* Footer section including; Mirroring top left menu for **HOME**, **TRIP**, **WORK**, **LIFE**, **TIPS**, followed with **Newsletter** user email subscribe services form [View Screenshot](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/email.png) and finishing with social networks links for user sharing purposes
* The Footer section is replicated across all website sub-section pages for better UX

## TRIP
Section introduction with intro reference and **"call-to-action"** headings

Formatted in two main sub-sections:
* **_CHOOSE WISELY_** Flights booking web services
* **_HOP ON_** Ireland public transportation's most popular options and guidelines
* **Quick Links...** quick link option for precise user search in specified link area - [View Screenshot](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/quicklinks.png)
* **Google Maps** with a tracker for public transportation and _"Hot"_ locations in Dublin city with 3 markers in different colors for **Dublin Bus**, **Dart Train**, and **Luas** services - [View Screenshot](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/googlemap.png)

## WORK
Introduction and quick links of the most popular Irish online recruitment sites with an additional section for online education possibilities

Formatted in two main sub-sections:
* **_START HERE_** Most popular job search services for the Irish job market
* **_BACK TO SCHOOL_** Most popular online courses and full-time education institutions
* **_Quick Links..._** quick link option for precise user search in specified link area - [View Screenshot](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/quicklinks_work.png)

## LIFE
Section with life essentials factors after moving to Ireland

Formatted in three main sub-sections:
* **_ACCOMMODATION_** Online rental agencies
* **_MOBILE NETWORKS_** Mobile/internet networks providers
* **_GROCERY SHOPS_** Irish Top food chains for grocery shopping
* **_Quick Links..._** Quick link option for precise user search in specified link area - [View Screenshot](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/quicklinks_life.png)

## TIPS
Section with tips and useful advice from other users

Formatted in three main sub-sections:
* **_TIPS_** Introduction and purpose of the tips section
* **_SEARCH_** Ability to search posted tips by referring to tip title and tip description
* Ability for active user to see their posted tips with **_"Your tip"_** marker ribbon and option for **_UPDATE_** or **_DELETE_** the active user tips

## SIGN UP
Section with the option to _create_ a user profile for full website management

Formatted in three main sub-sections:
* **_Create Account_** Registration form including inputs fields for; _Username_, _Email_, _Password_, Confirm Password_ and _Sign Up_ button
* Overview of the website purpose displayed in four cards - **_Trip_**, **_Work_**, **_Life_**, **_News_**
* Home hero area with photo composition styling

## LOGIN
Section with the option to _login_ to a user profile for full website management

Formatted in three main sub-sections:
* **_Already a member_** Login form including inputs fields for; _Username_, _Password_, and _Login_ button
* Overview of the website purpose displayed in four cards - **_Trip_**, **_Work_**, **_Life_**, **_News_**
* Home hero area with photo composition styling

## PROFILE
Section for user profile details and delete option

Formatted in three main sub-sections:
* **_Profile info_** User details listed in the following order; _Username_, _Email_, _Joined Date_
* Option for the user to **_DELETE_** profile
* Overview of the website purpose displayed in four cards - **_Trip_**, **_Work_**, **_Life_**, **_News_**
* Home hero area with photo composition styling

## ADD TIP
Section for active users to write and upload useful tips

Formatted in three main sub-sections and functionalities: 
* Active user has an option to chose from 4 tips categories: **_Trip_**, **_Work_**, **_Study_**, **_Food_**
* Active user has an option to **_CREATE_** appropriate title for the posted tip
* Active user has an option to **_UPLOAD_** appropriate title description
* After successful tip **_POST_** user is receiving a message for successful tip **_UPLOAD_**
* Overview of the website purpose displayed in four cards - Trip, Work, Life, News
* Home hero area with photo composition styling


## CROS-PROJECT FEATURES
The Main Menu is placed on to header and footer part of the website.

The  Main Menu bar is designed for large and small devices for the best UX.

Welcoming **Home** _"Hero"_ section; **Home** image composition section followed with four cards with _Trip_, _Work_, _Study_, and _News_ headings are replicated through the website.

### Features Left to Implement

Expansion plan:
* Implementing comments section for the users, regarding specific website content.
* Implementing "update your profile" functionality for active users.
* Implementing file upload functionality for all tips categories such as _*.PDF files_, _image files_, _direct links_. 
* Implement section for all necessary documentation in Ireland, regarding and PPS number, Bank Account option.
* Implement section regarding social events and gathering for necessary user connection expansion.
* Offer **_" Jobs Adds"_** section for recruitment agencies  - a connection between end-user and possible employer or recruitment agent.

****

# TECHNOLOGIES USED

## # [HTML](https://en.wikipedia.org/wiki/HTML)
**Semantic elements**: _nav_, _section_, _footer_, _div_(content division element), _span_(inline container), _i_ (text element)

## # [CSS3](https://en.wikipedia.org/wiki/CSS)
**Modules:** Borders, Background and text-effects, Flexible Box Layout, CSS Grid Layout, CSS Transitions, CSS Image Values & Replaced Content, CSS Values & Units

## # [SASS PRE-PROCESSOR](https://sass-lang.com/)
**TOOLS INCLUDED:**
* SASS interpolation
* SASS Mixings - Responsive layout functions
* SASS Variables
* SASS Nesting
* SASS Compiler

**COMPILER IMPLEMENTATION:**
* Open Command Prompt
* Navigate to the root project folder
* Enter commands in the following order:
  * `npm init --yes` - **PRESS ENTER**
  * `npm i -g node-sass` - **PRESS ENTER**
  * In `{} package.json` file under the `"scripts"` type the **[FOLLOWING](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/sass_01.png)**
* To start **SASS Compiler** enter the following command: `npm run watch` - **PRESS ENTER**
* If no errors the compilation process _NPM SERVER_ will start with the following console log message:
    ```
    > new@1.0.0 watch C:\Users\Tomislav\Desktop\new
    > node-sass -o assets/css assets/scss/index.scss -w
    ```
_**SASS IMPLEMENTATION AND FOLDER STRUCTURE**_
* Create the following folder structure:
  * assets/scss/abstracts - global SASS **variables** and **mixins** function
  * assets/scss/base - global styles for html, body and special helper classes
  * assets/scss/components - carousel image slideshow, small screen navigation menu
  * assets/scss/layout - styling for _HOME_, _TRIP_, _WORK_, _LIFE_, _TIPS_, _SIGN UP_, _LOGIN_
  * assets/scss/_index.scss - referencing all `*.scss` files in folder structure, **[EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/sass_02.png)**
  * **SASS RESPONSIVE Mixins** function **[EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/sass_03.png)**
* All files in the above folders **MUST** be named with the following naming conventions: `_filename.scss`

## # [NODE.JS](https://nodejs.org/en/)
* Use for NPM `package.json` file implementation into the project root

## # [NPM](https://www.npmjs.com/)
* Package manager - Use package - `node-sass`

## # [JAVASCRIPT](https://www.javascript.com/)
Features: _Dom Events_, _Validation of User’s Input_, _Else and If Statement_, _Handling Events_,  _In-Built Function_

## # [JQUERY](https://fonts.google.com/)
**APPLIED jQuery DOM EVENTS** for highlighting **_"Quick Links"_** cards elements

_TRIP_, _WORK_, and _LIFE_ sections are containing **_Quick Links_** card elements.

Every card element contains the _MAIN LINK_ source to the external services provider and a **_"Quick Links..."_** button element for loading detailed links when the user chose the services provider destination. **[EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/quicklinks_life.png)**

**_base.html_** template contains `<div class="blur">` just after opening tag for the background _"fade-out"_ effect

**jQuery DOM Events** used for the above-mentioned cards element functionality:

* Element with id **#showLinks1** was clicked
* `var thisCardLinkShow = "." + this.id + "-grid";` checking for `<div>` element with class `.showLinks1-grid`
* `$(thisCardLinkShow).show(300)` referring to `this` element to `.show()` with speed of 300 milliseconds
* `$(".blur").fadeIn(400)` loading background "blur" effect with speed of 400 milliseconds
* `$(thisCardLinkShow).addClass("rel-card");` adding class `.addClass("rel-card")` to element that is referring to `this` element
* `$("#Card1").addClass("wrap-rel");`  adding class `.addClass("rel-card")` to element with id **Card1**

The process is replicated for the `<button id="#hideLinks1">` element with the id of `#hideLinks1` for the "hiding" effect with `.removeClass("wrap-rel");` - **[SOURCE CODE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/cards.js)** from lines **9 - 14** 

If user click anywhere on the screen _"loaded"_ elements will _"hide"_ and that is achieved with following `.click()` DOM effect on `<div class="blur>`.
`.blur` element contains absolute position properties with a z-index of 1000: **[SOURCE CODE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/cards.js)** from lines **34 - 38** 

**FULL SOURCE CODE:** for jQuery Cards DOM Events **[cards.js](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/cards.js)**

## # [BOOTSTRAP v4.5.2](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
* Bootstrap was used to assist with the responsiveness and styling of the website
* Mani layout control - responsive layout usage - helper classes included - example -  .mt, .pt, .d-none .d-md-block, .col, col-sm, col-md, col-lg, etc...

## # [PYTHON 3.9.2](https://www.python.org/)
* Used for project back-end logic, to run **[app.py](https://github.com/tsokac2/newIrishLife.3.0/blob/main/app.py)**, **[forms.py](https://github.com/tsokac2/newIrishLife.3.0/blob/main/app.py)**, **[test.py](https://github.com/tsokac2/newIrishLife.3.0/blob/main/app.py)** files for full website functionalities
* Python Modules used (Full list in **[requirements.txt](https://github.com/tsokac2/newIrishLife.3.0/blob/main/requirements.txt)**):
  * _Flask==1.1.2_
  * _dnspython==2.1.0_
  * _Flask-Login==0.5.0_ 
  * _Flask-PyMongo==2.3.0_
  * _Flask-WTF==0.14.3_
  * _Jinja2==2.11.2_
  * _mongoengine==0.22.1_
  * _pymongo==3.11.3_
  * _Werkzeug==1.0.1_
  * _WTForms==2.3.3_

## # [MongoDB](https://www.mongodb.com/1)
* Used to create the document-based databases(collections)
* Used as data storage for this users registration and login details
* Used as data storage for user post(tips) details

**IMPLEMENTATION STEPS:**
* Create MongoDB Account
* Create Cluster
* Select Cluster  > **Collections** > **+ Create database** > **Create Collection**
* MongoDB Collection Object format schema examples:
  * Collection: **_categories_**
  ```
    {
      _id: ObjectId("unique-value")
      tip_category: "Trip"
    }
  ```
  * Collection: **_tips_**

   ```
    {
      _id: ObjectId("unique-value")
      tip_category : "Food"
      tip_title: "Food Glorisu Food"
      tip_description: "Best burger is bunsen burger"
      date_added: 2021-02-28T11:25:00.557+00:00
      created_by: "John"
    }
  ```
  * Collection: **_users_**

  ```
  {
    _id: ObjectId("unique-value")
    username : "John"
    email: "john@email.com"
    password: "unique-value"
    date_created: 2021-02-28T11:25:00.557+00:00
  }
  ```
**DATABASE SECURITY**
DB connection details are stored in an env.py for development, for security reasons, this is not uploaded to GitHub so that database and connection details are not visible to the public and end-users.

## # [HEROKU](https://www.heroku.com)
* Cloud platform service used for hosting a "live" version of the project

## # [GOOGLE CDN's](https://fonts.google.com/) and [GOOGLE API](https://developers.google.com/maps/gmp-get-started#quickstart)
* Google Fonts - **[Merienda](https://fonts.google.com/specimen/Merienda?preview.text=&preview.text_type=custom&query=mer)**
* Google Fonts - **[Lato](https://fonts.google.com/?preview.text=&preview.text_type=custom&query=LATO)**
* Google Fonts - **[Josefin](https://fonts.google.com/specimen/Josefin+Sans?preview.text_type=custom)**

**GOOGLE API IMPLEMENTATION STEPS:**
  * Pick Google Maps product **[More info](https://developers.google.com/maps/gmp-get-started#quickstart)**
  * Create a project.
  * Set up a billing account.
  * Enable APIs associated with the products you picked.
  * Create an API key-  documentation source - **[API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)**
  * API keys for frontend-only applications cannot be hidden like is stated on the following link [Hide API Keys](https://gist.github.com/derzorngottes/3b57edc1f996dddcab25), developers **[Comment](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/API_Secure.png)**

**SCRIPTS INTEGRATION:**
  * In `<head>` element place `<scripts>` in following order:

    ```
    <script src="assets/js/markerclusterer_compiled.js"></script>
    <script defer src="https://maps.googleapis.com/maps/api/js?key="YOUR API KEY"&callback=initMap"></script>
    <script src="assets/js/maps.js"></script>
    ```
  * Create `<div>` element with ID `<div id="map">` render map place
  * Marker Cluster CDN - **[SOURCE](https://cdnjs.com/libraries/js-marker-clusterer)**
  * Creating call-back function in `<script src="assets/js/maps.js"></script>` - **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/maps.js)** from lines **1 - 36** 

* `function initMap() {..}` maps location on a major scale in this case Dublin, Ireland
* `google.maps.event.addDomListener(window, "resize", function() {...}` adding Google Maps DOM listener
* `let busMarkerIcon = {...}` creating custom map marker with `scaledSize` property
* `const Bus747Stop = new google.maps.Marker({...});` pointing to Bus Stop for 747 Dublin Bus line for Dublin Airport

**FULL SOURCE CODE:** GOOGLE MAPS API **[maps.js](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/maps.js)**

## # [EMAILJS](https://dashboard.emailjs.com/sign-in)
**IMPLEMENTATION**
* Add New Service - Gmail
* Email Templates - Create New Template
* Use following syntax for form attributes, syntax {{form_name}}
* SENT **[Email](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/email_01.png)** content from a user
* Select the Auto-Reply option and place the following: **_SUBJECT**: On behalf of all of us from New Irish Life, welcome onboard!_
* **WELCOMING** **[Email](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/email_02.png)** content sent to the user after successful submission

**SCRIPTS INTEGRATION:**
 * Before closing **`<head>`** element place following **CDN** script tag:
    * `<script src="https://cdn.jsdelivr.net/npm/emailjs-com@2/dist/email.min.js"></script>`
  * Place following call-back function after **CDN** link

  ```
  <script type="text/javascript">
        (function() {
        emailjs.init("user_hI6S08d1aK1XKKU2VWtOI");
        })();
  </script>
  ```
  * Check `User ID` under "Integration" option on EmailJS dashboard
  * Create `sendEmail` function **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/emailnews.js)** from lines **88 - 103** 

**FROM VALIDATION DEVELOPMENT**
* Create **[EventTarget](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget)** method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target, in this case `newsletter()` function - **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/emailnews.js)** from lines **1 - 3** 
*  Create 2 validation function for UX purposes, `validateName()` and `validateEmail()` function.
* `validateName()` function is _**returning**_ Boolean value `true` or `false` that is stored in empty variable `var valid;` depending of a user input string value - **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/emailnews.js)** from lines **5 - 22**
* Implement call-back functions regarding what kind of input value was submitted by a user.
* `pushSuccessFor()` function is adding a `.success` class to the input element when user input is valid - **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/emailnews.js)** from lines **55 - 58**
* User email validation is stored in the `validateEmail()` function with a call-back function that is checking user email - **[SOURCE](https://www.w3resource.com/javascript/form/email-validation.php)**
* To get a valid email id we use a regular expression
* Regular Expression Pattern : `/^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/`
* `testEmail()` function:

  ```
    function testEmail(email) {
        return /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/.test(email);
    };
  ```

* To submit user data to the server we are declaring `send()` function in variable `var send = function(){...};` and calling that function when submit `<button>` is triggered - **[CODE EXAMPLE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/js/emailnews.js)** from lines **60 - 76**

* Validation tests are covered in **[TESTING.MD](https://github.com/tsokac2/newIrishLife.3.0/blob/main/TESTING.md)** file

## # [JASMINE BEHAVIOR-DRIVEN JavaScript](https://jasmine.github.io)
* Full testing and implementation process described in **[TESTING.MD](https://github.com/tsokac2/newIrishLife.3.0/blob/main/TESTING.md#Jasmine)** file 

## # [FONTAWESOME](https://fontawesome.com/) 
* Use mostly for menu items and across projects elements

## # [GIT](https://git-scm.com/)
* A distributed version control system

## # [GITHUB](https://github.com/)
* Project files hosting platform

## # [IDE Visual Studio Code](https://code.visualstudio.com/)
* Project code editor 

## # [ADOBE PHOTOSHOP](https://www.adobe.com/)
* Images preparation - Logo Design

## # [ADOBE ILLUSTRATOR](https://www.adobe.com/)
* Logo Design 

## # [BALSAMIQ WIREFRAMES](https://balsamiq.com/) 
* Wireframes Design

## # [AM I Responsive?](http://ami.responsivedesign.is/)
* Multi-Device Website Mockup Generator was used to create the project Mockup image

****

# TESTING

### Strategy and planning
* Testing is required on all features and user stories documented in this README.
* All clickable links must redirect to the correct pages
* HTML Code must pass through the [W3C HTML Validator](https://validator.w3.org/#validate_by_uri).
* CSS Code must pass through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
* JavaScript code must pass through the [JSHint Validator](https://jshint.com/).
* Python Code must pass through [PEP8 Validator](http://pep8online.com/).
* Python Code must pass through the [Unit testing framework](https://docs.python.org/3/library/unittest.html).


### Test Cases and Description

![Test Cases](https://github.com/tsokac2/newIrishLife.3.0/blob/main/static/wireframes/test_cases.PNG)


### Regression Testing
All features previously tested during development in a local environment must be regression tested in production on the live website.

### Assumptions and Dependencies
Testing is dependent on the website being deployed live on Heroku.

### Out of Scope
Only test cases listed under High-Level Test Cases will be performed as part of this testing effort.

### Test Results
All processed test and result are described in details **[HERE](https://github.com/tsokac2/newIrishLife.3.0/blob/main/TESTING.md)**

****

# DEPLOYMENT

**[PROJECT LINK](http://new-irish-life-3-0.herokuapp.com/)**

### LOCAL PROJECT SETUP:
* Create a new repository on [GitHub](https://github.com)
* Create a project folder on the local device
* Start [CMD](https://en.wikipedia.org/wiki/Cmd.exe) on the local device and navigate to the root folder of the project
* Initialize project root folder with the following CMD command: `git init`
* Create _README.MD_ file with CMD command: `echo #New Irish Life > README.md`
* Initiate `git add .` command in CMD project root folder
* Initiate commit `git commit -m "Test first commit"` command in CMD project root folder
* Create a connection with the local device and GitHub repository with the CMD command 
  ```
  git remote add origin https://github.com/username/project_repo_name.git
  ```
* Initiate push command `git push -u origin master`
* Make regular commits after every project change with proper commit message more info in [Git Commit Message](https://chris.beams.io/posts/git-commit/#separate)
* Use `git push` command in CMD for code commits 

## DEPLOYMENT TO HEROKU
### Create application:
**1.** Navigate to **[HEROKU](https://id.heroku.com/login)** and log in

**2.** Click on the _New_ button

**3.** Select Create a _New App_

**4.** Enter the app name

**5.** Select region

### Configure connection to Github Repository
**1.** Click the **_Deploy_** tab and select **_GitHub - Connect to GitHub_**

**2.** Select GitHub

**3.** Enter the repository name for the project and click search

**4.** When repo has been found, click the connect button

### Set environment variables:
* Click the **_Settings_** tab and then click the **_Reveal Config Vars_** button and add the following:

  **1.** KEY: IP | VALUE: _0.0.0.0_

  **2.** KEY: PORT | VALUE:  _5000_

  **3.** KEY: _MONGO-DBNAME_ | VALUE: _your-data-base-name_

  **4.** KEY: _MONGO-URI_ | VALUE: _(mongo URI - This can be found in MongoDB by going to clusters > connect > connect to your application and substituting the password and dbname that you set up in the link)_

  **5.** KEY: _SECRET-KEY_ | VALUE: _your-secret_key_ - [Random Key Generator](https://randomkeygen.com/)

### Enable automatic deployment:
**1.** Select _Deploy_ tab and click _Enable Automation Deploys_

**2.** Click the _Deploy_ button

**3.** When the app is created check the logs for deployment errors, if none, click the _"View"_ button

### LOCAL HOSTING
**Note:** The project will not run locally with database connections unless the user sets up an `env.py` file configuring the following
* _IP_
* _PORT_
* _MONGO-URI_
* _MONGO-DBNAME_
* _SECRET-KEY_

**_These details are private and not disclosed in this repository for security purposes._**

Once the project has been loaded into an IDE of choice, run the following command in the shell to install all the required packages:

`pip install -r requirements.txt`

When the project is fully configured to start _localhost_ server, in CMD navigate to project root folder and start a server with the following command: `python app.py`

In the web browser of your choice type: `localhost:5000` to preview the project

****

# CREDITS
* Intro pitch - [*"The Hobbit: An Unexpected Journey"*](https://en.wikipedia.org/wiki/The_Hobbit_(film_series))
* Website images source - [UNSPLASH](https://unsplash.com/s/photos/smartphone)
* Website images source - [PIXABAY](https://pixabay.com/photos)
  * [User: wiredsmartio](https://pixabay.com/users/wiredsmartio-14931632/)
  * [User: geralt](https://pixabay.com/users/geralt-9301/)
  * [User: ds_30](https://pixabay.com/users/ds_30-1795490/)
  * [User: pexels](https://pixabay.com/users/pexels-2286921/)
  * [User: firmbee](https://pixabay.com/users/firmbee-663163/)
  * [User: wokandapix](https://pixabay.com/users/wokandapix-614097/)
  * [User: publicco](https://pixabay.com/users/publicco-5009832/)

* Home page icons - [Flaticon](https://www.flaticon.com/)

### CODE
* [Bootstrap Carousel Fade Effect](https://silvawebdesigns.com/how-to-change-the-bootstrap-4-carousel-to-a-fade-transition-instead-of-slide/)
* [Resizing Google Maps markers](https://stackoverflow.com/questions/15096461/resize-google-maps-marker-icon-image)
* [Jasmine-jQuery: Set of jQuery helpers](https://bowercdn.net/c/jasmine-jquery-2.1.1/lib/jasmine-jquery.js)

### ACKNOWLEDGEMENTS
Special thanks to the following people for their help with my project:

* Slack user [Daisy McGirr](https://github.com/Daisy-McG) for inspiration on how to write README.MD for M3.
* Slack user [Simon Vardy](https://github.com/simonjvardy) for giving me an idea of using data to be displayed on the user profile page.
* Slack user [Ed Bradley](https://github.com/Edb83?tab=repositories) - for testing project functionality, spotting couple CSS issues, and the idea of uploading images on S3 AWS as a project migration possibility.
* **Anna Teresa Villanueva** for always fun and informative mentorship sessions.

****