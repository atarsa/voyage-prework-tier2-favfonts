# Chingu Voyage Pre-Work Solo Project (Tier 2): *Favorite Fonts* #

![Landing Page ScreenShot](./assets/favoriteFontsLanding.png)

## Overview ##

This project is a great opportunity to develop a clean and modern webpage. The *Favorite Fonts* app will be completed accross tiers, with each tier adding a new level of complexity. You are currently on the *Tier 2* repo. You'll be responsible for coding the **HTML**, **CSS**, and **JavaScript** to get the structure, styling, and functionality up and running.

As you add skills to your developer toolbag you'll be able to come back to this project and add in the Tier 3 features. Ultimately you'll have a great portfolio piece, and will have implemented a number of common and in-demand features.

**You May Use Frameworks and/or Libraries of Your Choosing**

## Instructions ##

Tier 2 realizes this project as a fully developed front-end app. A back-end is not necessary. If you would like to add a back-end, consider moving over to the Tier 3 repo.

General instructions for all Pre-Work Projects can also be found in the Chingu Voyage Handbook (URL posted in the #read-me-first channel on Discord).

**Requirements**

*Structure*
- [x] Header with minor navigation *(Logo and Catalog/Featured/Articles/About link list)*
- [x] Nav with Major navigation / page-manipulation *(search, custom text, font-size, dark/light mode, grid/list mode, and reset)*
- [x] Main section for the font cards
- [x] Font cards which display the Font Name, the sample text, and an add button (the font creator is **not** available via the api, so it is not required in tiers 2 or 3)
- [x] Back-to-top button that allows users to click and scroll back up to the top *(there could be up to 959 fonts displayed, so you need this!)*
- [x] Footer section with your developer information

*Style*
- [x] Sample text in each card should be displayed in the corresponding font
- [x] Buttons/links should be evident (make sure the cursor changes, etc.)
- [x] Implement a way to handle overflow from sample text in the font cards, as the font size is adjustable

*Functionality*
- [x] Text typed into the custom text (type something) box should immediately change the sample text in each font card
- [x] The sample text should return to the default sample if the input box (type something) no longer has any input
- [x] Font size chooser should have at least four sizes and should immediately change the sample text font size in each font card
- [x] Implement the clickable 'reset' icon on the far right of the major navigation; it should reset the page as if the page were reloaded *(do not actually reset the page)*
- [x] On load, the page should display fonts sorted by current popularity, as returned by the Google Fonts Developer API *(see below)*
- [x] The search feature should be fully functional and should display matching fonts (it's up to you if you want to do this via a 'submit' or through onchange)
- [x] When the search input is cleared (via reset button or manually), the fonts should automaticaly display sorted by poplarity again

*Other*
- [ ] Your repo needs to have a robust README.md
- [ ] Make sure that there are no errors in the developer console before submitting

**Extras (Not Required)**

- [ ] Make your design fully responsive (small/large/portrait/landscape, etc.)
- [x] Implement the light/dark mode toggle buttons
- [x] Implement the change display icon so you can flip between a grid layout and a list layout for the font cards
- [ ] Make the 'add-font' icon add the font to a list (localHost, Cache API, etc) for front-end persistence; users can then delete the font from the list

## API Information ##

Consider designing the app so that the Google Fonts Developer API is only called once during the app lifetime.

This project utilizes the [**Google Fonts API**](https://developers.google.com/fonts/docs/getting_started) and the [**Google Fonts Developer API**](https://developers.google.com/fonts/docs/developer_api). You will need to register for a free api key in order to complete this project as calls to the developer api are severely capped without one.

Please do *not* use the Google Web Font Loader for Tier 2.

## Example ##
![Tier 2 Gif](./assets/tier2Preview.gif)
