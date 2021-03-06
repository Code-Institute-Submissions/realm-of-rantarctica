# Realm Of Rantarctica

[The live site can be viewed here](https://wondrouswebworks.github.io/realm-of-rantarctica/)

Welcome to my project! Realm of Rantarctica is an interactive game based on the classic card game called **Top Trumps**.  I hope you enjoy reading about the project below.  Please feel free to contact me for any further information or to offer any suggestions. My contact details can be found on my github page.

![alt text](https://res.cloudinary.com/wondrouswebworks/image/upload/v1581074244/realm-of-rantarctica/other/responsive-layout.png "Responsive Layout")

## Contents

- [Realm Of Rantarctica](#realm-of-rantarctica)
  - [Contents](#contents)
  - [UX (User Experience)](#ux-user-experience)
    - [Project Goals](#project-goals)
      - [User Goals](#user-goals)
      - [User Stories](#user-stories)
        - [User Story A](#user-story-a)
        - [User Story B](#user-story-b)
        - [User Story C](#user-story-c)
        - [User Story D](#user-story-d)
        - [User Story E](#user-story-e)
        - [User Story F](#user-story-f)
      - [Site Owner Goals](#site-owner-goals)
    - [User Requirements and Expectations](#user-requirements-and-expectations)
      - [Requirements](#requirements)
      - [Expectations](#expectations)
    - [Design Choices](#design-choices)
      - [Fonts](#fonts)
      - [Icons](#icons)
      - [Images](#images)
      - [Colours](#colours)
        - [#003049 (Prussian Blue)](#003049-prussian-blue)
        - [#D62828 (Amaranth Red)](#d62828-amaranth-red)
        - [#F77F00 (University of Tennessee Orange)](#f77f00-university-of-tennessee-orange)
        - [#FCBF49 (Maximum Yellow Red)](#fcbf49-maximum-yellow-red)
        - [#EAE2B7 (Dutch White)](#eae2b7-dutch-white)
        - [#80D2FF (Light Prussian Blue)](#80d2ff-light-prussian-blue)
  - [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Libraries & Tools](#libraries--tools)
  - [Wireframes](#wireframes)
    - [Differences Between Wireframes and Final Product](#differences-between-wireframes-and-final-product)
      - [Landing Page](#landing-page)
      - [Lore](#lore)
      - [Tutorial](#tutorial)
      - [Select Battleground Screen](#select-battleground-screen)
      - [Battle Screen](#battle-screen)
      - [Post Battle Result Screen](#post-battle-result-screen)
  - [Testing](#testing)
  - [Deployment](#deployment)
    - [The following steps were taken to deploy Realm of Rantarctica on GitHub Pages](#the-following-steps-were-taken-to-deploy-realm-of-rantarctica-on-github-pages)
    - [Cloning Realm of Rantarctica from GitHub to Run Locally](#cloning-realm-of-rantarctica-from-github-to-run-locally)
  - [Bugs](#bugs)
  - [Credits](#credits)
  - [Disclaimer](#disclaimer)

## UX (User Experience)

### Project Goals

This project was created to offer the user a simple, yet engaging and visually appealing gaming experience. The game is geared more towards users with a passion for the fantasy genre, but is intended to be accessible and fun for any user at the same time. A combination of strategy and an interactive and animated game space needs to offer the user a satisfactory user experience whilst generating interest for continued use of the site and other future offerings from the developer.

#### User Goals

- A single page site that displays all game content without needing to navigate elsewhere
- A range of character types to play as
- Various selectable fullscreen backgrounds with vibrant colours
- Clearly visible data for each character's charateristics
- Multiple difficulty levels in the form of limited time for each round
- The option to restart or quit the game at any time
- A summary of the match's most interesting statistics when done
- Playable on all screen sizes and devices

#### User Stories

##### User Story A

*"As a first time player fo the game, I want to be able to access gameplay instructions easily so that I can get start playing with a clear understanding of gameplay mechanics straight away."*

##### User Story B

*"As a repeat player of the game, I want the ability to choose different backgrounds so as to keep the gameplay environment interesting and varied."*

##### User Story C

*"As an experienced gamer, I want a way to increase the difficulty level so that I can continually be challenged while playing the game."*

##### User Story D

*"As a great fan of the fantasy genre, I want a varied selection of characters so that I can get a asense of immersion when playing the game."*

##### User Story E

~~*"As someone with a keen interest in statistics, I want the ability to view match statistics at the end of the match so that I can appreciate my level of performance and try to improve in future matches."*~~

**Not incorporated into the project due to time constraints.**

##### User Story F

*"As a user with multiple devices - both mobile and static - I want the game to display correctly on any screen size so I can play the game on any device wherever I am."*

#### Site Owner Goals

- Deliver on User Stories as far as possible
- Create an engaging and enjoyable fantasy game with replay value
- Gain sufficient user interest to ensure a user base for future releases
- Add more character content and features in future expansions

### User Requirements and Expectations

#### Requirements

- A visually striking landing page
- The option to view information about the game before playing
- Selectable background images to act as battlegrounds
- A range of characters with varying strengths and weaknesses
- Different difficulty levels by means of an adjustable countdown timer
- Basic character animations
- User friendly UI
- Clearly visible character stats
- A counter to show how the player is faring vs the AI
- A summary with various match stats once the game is finished
- The option to replay without having to reload the page

#### Expectations

- Landing page to be engaging and visually striking
- Background information about the game and the world in which it takes place
- Clear instructions on how to play the game
- A screen where selectable backgrounds are displayed
- The option to scroll through or navigate through backgrounds on smaller screens
- A nice range of fantasy characters with no clear emphasis on a particular type
- The option to set a difficulty level by adjusting the amount of time the user has to choose a statistic for any given round of the game
- Characters that have basic animations to be displayed at appropriate times, such as idle, attack and death
- Easy to read stats for all characters, allowing the user to make a quick decision when making their selection
- A display area dedicated to keeping the user informed of their progress throughout the game
- The User Interface (UI) should be clean and easy to understand and use
- Users expect statistics to be displayed at the end of the match
- Users would like the option to play again at the end of a match, without having to go back to the landing page

### Design Choices

Realm of Rantarctica is a game in the fantasy genre. As such, the overall style of the game reflects that in terms of colour, graphical style, font type and page layout. Knowledge gained from previous projects, coupled with user feedback, heavily influenced my decisions for this project.

#### Fonts

In order to fit the fantasy nature of the game, unconventional fonts were selected from **Google Fonts**.  The selected fonts have to be slighty quirky and more cartoony in design, while still being legible. Sample phrases featured in the game were entered in **Google Fonts** to see how they were displayed. Ultimately, the fonts below were selected to be used in clearly defined areas in the game.

- [Girassol](https://fonts.google.com/specimen/Girassol) - used for the game title, modal headings, Select Battleground screen heading and Post Battle screen heading
- [Acme](https://fonts.google.com/specimen/Acme) - used for all button text, modal body text, timer text, Battle screen bottom row containers and Post Battle screen message
- [Mansalva](https://fonts.google.com/specimen/Mansalva) - music and sound volume, currently loaded track, Sound Info modal label, Select Battleground card headers and battle info

#### Icons

All icons used in the Realm of Rantarctica were taken from [CraftPix](https://craftpix.net/), where I have a paid subscription.  Although some content on **CraftPix** is free, the majority of icons require a paid subscription to access.  The license allows me to use and modify any images from **CraftPix** in any number of projects, but not to resell it.  

#### Images

All background and character sprites were taken from [CraftPix](https://craftpix.net/).  I have a paid subscription with **CraftPix**, and the majority of images and sprites used require a paid subscription to download and use. The license allows me to use and edit images as I wish, though the only changes made were resizing, applying filters and joining sprites to allow animation of characters. The question mark image was taken from PNGTREE. See **Credits** section for more details.

#### Colours

I decided on using [this](https://coolors.co/003049-d62828-f77f00-fcbf49-eae2b7) colour palette from **coolors.co**.  All five colours complement each other very well, and should provide a good level of contrast to increase legibility and clearly define different areas of the game display.  A lighter shade of *Prussian Blue* was also selected to add to the colour palette.  The colours and their *intended* uses are listed below:

##### #003049 (Prussian Blue)

- Background colour for all modals
- Background colour in containers displaying character attributes and card count values
- Font colour for level names on the **Select Battleground** screen

##### #D62828 (Amaranth Red)

- Border colour for sections in modals
- Border colour for *Player Attributes, AI Attributes* and *Card Counts*
- Background colour to highlight the players chosen stat with which to battle

##### #F77F00 (University of Tennessee Orange)

- Font colour of the game title on the landing page
- Font colour of the **Select Battleground** heading on the **Select Battleground** screen
- Font colour of the *Battle Info* text on the **Battle** screen
- Background colour for *buttons* which are not icons only on hover/tap
- Font colour of main *modal headings*
- Font colour of the *Post Battle Result* text

##### #FCBF49 (Maximum Yellow Red)

- Background colour for all buttons which are not icons only
- Font colour of *Currently Playing Track* text
- Colour of **Audio** modal's ranged input thumb slider
- Font colour of **Sound Info** modal checkbox label
- Font colour of the **Tutorial** modal section headers
- Background colour of **Select Battleground** card headers
- Font colour of *Attribute* names and player or AI text in *Card Count* containers on **Battle** screen

##### #EAE2B7 (Dutch White)

- Font colour of all modal body text which aren't headings
- Font colour of minimum and maximum volume ranged input values in **Audio** modal
- Border colour of **Select Battleground** card images on hover/tap
- Font colour of *Timer* text on **Battle** screen
- Font colour of *Player Attribute* values
- Font colour of *Player Card Count* value
- Font colour of the player's *Character Name*
- Font colour of the **Post Battle Result** win/lose message

##### #80D2FF (Light Prussian Blue)

- Font colour of the heading for the *Currently Play Track* in the **Audio** modal
- Colour of **Audio** modal's ranged input thumb track
- Font colour of AI-related text in **Tutorial** modal
- Font colour of *AI Attribute* values
- Font colour of *AI Card Count* value
- Font colour of the AI's *Character Name*

## Technologies Used

### Languages

- HTML
- CSS
- JavaScript

### Libraries & Tools

- Git
- Bootstrap
- jQuery
- Google Fonts
- Cloudinary

## Wireframes

All wireframes were designed and produced using [Balsamiq Mockups 3](https://balsamiq.com/). Initially, a greyscale layout was created to optimised the position of elements, whereafter colours and images listed in the **Colours** and **Images** sections above were added to deliver a much more defined representation of what the game should look like. Individual wireframes for desktop, mobile and tablet can be viewed [here](https://github.com/wondrousWebWorks/realm-of-rantarctica/tree/master/wireframes). There are some differences between the wireframes and the final product as tester feedback forced changes to the initial design. These changes are highlighted below.

### Differences Between Wireframes and Final Product

#### Landing Page

- Menu changed from only being icon based to being button based to increase User Experience
- Audio controls toggled with icon added to top left of the screen (displayed on all screens)
- Exit button added to the top right of the screen (displayed on all screens)
- wondrousWebWorks() logo moved to bottom left of the screen

#### Lore

- *How to Play* button removed as it was deemed unneccesary by testers

#### Tutorial

- Called *How to Play* in wireframes, but changed to reflect industry convention
- Next button removed as vertical scrolling modal was used instead to improve UX
- Tutorial sections use Amaranth Red border instead of Light Prussian Blue to provide clearer separation of sections
- Tutorial images now mirror actual game content

#### Select Battleground Screen

- Audio controls replaced with toggle icon
- Exit button added at top right of screen
- Background name background colour changed to Maximum Yellow Red
- Background name font color changed to Prussian Blue
- Background name centered on background image
- *Random Level* button removed and replaced with a background card fulfilling the same purpose
- *Next* button removed as a container with vertical overflow to allow scrolling is used instead

#### Battle Screen

- *VS* text and surrounding bars replaced with timer to use screen estate more efficiently on smaller screens
- *Battle Info* moved to a lower position on the screen to provide centered information to the player
- *Player* and *AI Character Names* moved inside *Attribute* containers to localise character information
- AI placeholder image changed to occupy less screen space
- Timer changed to count down in tenths of a second
- On small mobile devices, *Player* and *AI* attributes are not displayed in one container, but separately at all times
- Horizontal rulers added between *Player* and *AI* attributes to increase legibility

#### Post Battle Result Screen

- Statistics contanier not incorporated due to time constraints
- *Win* or *Lose* images displayed depending on the battle result
- *Win* or *Lose* message displayed depending on the battle result
- *Play Again* added to reload the page on click/tap instead of *Yes* and *No* button options

## Testing

Testing details can be viewed in the TESTING.md file [here](https://github.com/wondrousWebWorks/realm-of-rantarctica/blob/master/TESTING.md).

## Deployment

Realm of Rantarctica was developed in Visual Studio Code, while git and GitHub were used for version control and to host the repository respectively.

### The following steps were taken to deploy Realm of Rantarctica on GitHub Pages

- Navigated to [GitHub](https://github.com/) in the browser
- Signed in to my account
- Searched for **wondrousWebWorks** under **Users**
- Clicked on the **wondrousWebWorks** result to take me to its repositories
- Clicked on the **realm-of-rantarctica** repository to navigate to it
- Clicked **settings** in the top navigation area
- Scrolled down to the **GitHub Pages** area
- From the **Source** dropdown menu, **Master Branch** was selected
- Confirmed selection by clicking.
- Following these steps, *Realm of Rantarctica* was deployed live on GitHub Pages [here](https://wondrouswebworks.github.io/realm-of-rantarctica/)

### Cloning Realm of Rantarctica from GitHub to Run Locally

- Open your favourite browser
- Navigate to the [GitHub](https://github.com/) homepage
- Search for **realm-of-rantarctica** in the search bar
- Click on the only result to be directed to the **realm-of-rantarctica** repository
- Click on the green **Clone or Download** button
- Copy the **URL** in the dropdown box
- Open your preferred **terminal**
- Navigate to your chosen **file location** to which you would like to donwload the project
- Ensure **git** is installed on your system and install it if necessary
- Copy and paste the following code into your terminal in order to clone **Realm of Rantarctica**

`git clone https://github.com/wondrousWebWorks/realm-of-rantarctica.git`

## Bugs

When any sound effect is played on click/tap, an error message is logged to the console stating that the play() promise was interrupted by a new load request.  Sounds effect and music playback perform as expected, despite the error log. Catching and handling the error might be incorporated in future.

Further error messages are logged to the console when a user hovers over elements which should play a sound effect before interacting with the page in any other way.  Once the user interacts with the page - by clicking/tapping anywhere on the page for example - sound effects play as expected once the user has unmuted the sound-effects volume in the **Audio** modal.  This behaviour does not in any way affect the user experience, but may cause concern if observed in the console.  A work-around might be implemented in future.

## Credits

- Image for README.md responsive layouts taken from [Am I Responsive?](http://ami.responsivedesign.is/)
- Character and Battleground images were taken from [CraftPix](https://craftpix.net/) - paid subscription
- Royalty free music from [Fesliyan Studios](https://www.fesliyanstudios.com)
- Code snippets for styling ranged inputs adapted from [BrennaOBrien](https://brennaobrien.com/blog/2014/05/style-input-type-range-in-every-browser.html)
- Function to shuffle an array taken from [Daplie Labs](https://github.com/Daplie/knuth-shuffle/blob/master/index.js) on GitHub
- Question Mark, Crown and Tombstone PNGs taken from [PNGTREE](https://pngtree.com/)
- Sound Effect mp3 files taken from [ZAPSPLAT](https://www.zapsplat.com/)

## Disclaimer

This site is intended for **educational purposes** only, and is not intended for use in any other capacity.
