# Realm of Rantarctica - Testing

In order to ensure the desired level of functionality, a rigarous testing program was set out with strict criteria to be met in order to be deemed successful.  Testing was devided into diffirent areas, including responsiveness, cross-browser compatability, acceptable load times and the intended behaviour of site components.

- [Realm of Rantarctica - Testing](#realm-of-rantarctica---testing)
  - [Responsiveness](#responsiveness)
    - [Desired Result](#desired-result)
    - [Steps Taken to Ensure Result](#steps-taken-to-ensure-result)
    - [Verdict](#verdict)
  - [Cross-browser Compatability](#cross-browser-compatability)
    - [Desired Result](#desired-result-1)
    - [Steps Taken to Ensure Result](#steps-taken-to-ensure-result-1)
    - [Verdict](#verdict-1)
  - [Load Times](#load-times)
    - [Desired Result](#desired-result-2)
    - [Steps Taken to Ensure Result](#steps-taken-to-ensure-result-2)
    - [Verdict](#verdict-2)
  - [Behaviour of Site Components](#behaviour-of-site-components)
    - [Landing Page](#landing-page)
    - [Audio Modal](#audio-modal)
    - [Information Modal](#information-modal)
    - [Select Battleground Screen](#select-battleground-screen)
    - [Battle Screen](#battle-screen)
    - [Post Battle Result Screen](#post-battle-result-screen)

## Responsiveness

### Desired Result

Display correctly on any screen size users are likely to use.

### Steps Taken to Ensure Result

Bootstrap 4 was used extensively when creating Realm of Rantarctica, including its grid system to ensure responsiveness on any screen size.  The decision to create the page to fit on any device screen without the need to scroll on the page created some difficulty in getting it to display correctly.  Scrolling is necessary in some modals and the **Select Battleground** screen, where the CSS *overflow: scroll* property is used to enable scrolling on a portion of the page while the rest of the page remains static.  It also proved necessary to use not only CSS media queries for width as I have done in the past, but for height as well to display the content as intended on mobile devices in both portrait and landscape mode.

Devices tested include, but are not limited to:

- Sony Xperia Xa2
- Samsung J5, S8, S10, Tab S6
- Apple iPhone 6,7 and 10
- Huawei P20, P20 Pro, Mate20 Pro

### Verdict

Realm of Rantarctica adapts to all tested screen sizes and devices and displays as expected.

## Cross-browser Compatability

### Desired Result

Display correctly in any browser users are likely to use.

### Steps Taken to Ensure Result

I tested Realm of Rantarctica throroughly using a range of browsers, and where I did not have access to it - such as Safari - I borrowed Apple devices to test for potential bugs.

Browsers tested include:

- Chrome - desktop and mobile
- Firefox - desktop and mobile
- Opera - dekstop
- Opera Mini - mobile
- Brave - desktop and mobile
- DuckDuckGo - mobile

### Verdict

No obvious bugs were detected in any of the tested browsers. Initially, some of the animations did not perform as expected in Opera, but this was quickly rectified by adding the appropriate CSS selectors to the style.css file. Although some browsers handle viewport height and scroll behaviour differently, no obvious cutt-offs were observed.

## Load Times

### Desired Result

Load images within 1.5 seconds regardless of connection speed.

### Steps Taken to Ensure Result

Full screen background images were initially compressed to allow for faster load times, but the loss of quality and definition was so profound that the original high-definition images were used instead.

Where full-screen images were not required, such as on the Select Level screen, smaller images are fetched from Cloudinary to improve load times.

### Verdict

Acceptable load times were experienced at various connection speeds, with the slowest connection tested being 2 Mb/s in a school with limited speeds for students.  Large background images resulted in a noticable delay in loading the page of about two seconds. However, according to feedback from testers, did not affect the gameplay experience once the background has loaded and no further lenghty load times are required.

On the slowest connection tested, music playback also suffered on occasion, though sound effects worked perfectly on any connection speed.

## Behaviour of Site Components

The game was intentionally devided into distinct sections and testing was performed on each section to confirm the intended behaviour of everything related to a specific section of the site.  Testing information and results for each section is detailed below.

### Landing Page

- Game title displays correctly :heavy_check_mark:
- *Audio* and *Exit* icons scale on hover :heavy_check_mark:
- *Menu* items change background colour on hover/tap :heavy_check_mark:
- All icons and menu items play the expected sound effect on hover :heavy_check_mark:
- Background colour of *Select Difficulty* buttons changes on click/tap :heavy_check_mark:
- Clicking/tapping on *wondrousWebWorks()* logo opens GitHub repository in browser  :heavy_check_mark:
- Clicking/tapping on *Audio* icon launches audio modal :heavy_check_mark:
- Clicking/tapping on *Exit* icon reloads the page :heavy_check_mark:

### Audio Modal

- Heading displays correctly :heavy_check_mark:
- Music range input adjusts music volume and displays the current value :heavy_check_mark:
- Sound Effect range input adjusts sound effects volume and displays the current value :heavy_check_mark:
- Play button shows animation on click/tap and plays the track currently loaded :heavy_check_mark:
- Pause button shows animation on click/tap and pauses the track currently loaded :heavy_check_mark:
- Next button shows animation on click/tap and plays the next audio track :heavy_check_mark:
- Previous button shows animation on click/tap and plays the previous audio track :heavy_check_mark:
- Currently loaded audio track name displays and animates correctly :heavy_check_mark:
- Modal close button closes modal successfully :heavy_check_mark:

### Information Modal

- Heading displays correctly :heavy_check_mark:
- Information text displays correctly :heavy_check_mark:
- Vertical scrolling works correctly :heavy_check_mark:
- Modal close button closes modal successfully :heavy_check_mark:

### Select Battleground Screen

- Heading displays correctly :heavy_check_mark:
- Select Battleground card images display correctly :heavy_check_mark:
- Select Battleground card borders display correctly on hover :heavy_check_mark:
- Select Battleground card text and background colour display correctly :heavy_check_mark:
- Clicking/tapping on Select Battleground card takes the user to the Battle screen and loads the selected or random background :heavy_check_mark:
- Vertical scroll to display all levels works as expected :heavy_check_mark:
- Exit icon displays correctly and returns the user to the Landing Page on click/tap :heavy_check_mark:
- Sounds play on hover of Select Battleground cards, Exit icon and Audio icon :heavy_check_mark:

### Battle Screen

- Player and AI images display correctly :heavy_check_mark:
- AI placeholder image displays correctly :heavy_check_mark:
- Player and AI character names display correctly :heavy_check_mark:
- AI placeholder name displays correctly :heavy_check_mark:
- Battle Info text displays correctly with the appropriate information :heavy_check_mark:
- Timer starts at the correct value to match the player's chosen difficulty :heavy_check_mark:
- Timer counts down as expected :heavy_check_mark:
- Timer pauses on selection of player attribute :heavy_check_mark:
- Timer resets for each round :heavy_check_mark:
- Timer displays correct message when the time is up :heavy_check_mark:
- Player atribute names and values display correctly :heavy_check_mark:
- AI attribute names and values display correctly :heavy_check_mark:
- AI attribute value placeholder displays correctly :heavy_check_mark:
- Player attribute background colour changes on hover/tap :heavy_check_mark:
- Correct sound plays on hover/tap of Player attribute :heavy_check_mark:
- AI attribute values, image and name are displayed when user clicks/taps on selected attribute :heavy_check_mark:
- Player and AI card count text and values display correctly :heavy_check_mark:
- Player and AI card count values update as expected after winning or losing a round :heavy_check_mark:
- Horizontal Rulers display correctly in Player atttributes, AI attributes and Card Count containers :heavy_check_mark:
- Clicking/tapping on *Audio* icon launches audio modal :heavy_check_mark:
- Exit icon displays correctly and returns the user to the Landing Page on click/tap :heavy_check_mark:
- Sounds play on hover of Select Battleground cards, Exit icon and Audio icon :heavy_check_mark:

### Post Battle Result Screen

- Correct sounds play for winning and losing :heavy_check_mark:
- Result image displays correctly :heavy_check_mark:
- Result heading displays correctly :heavy_check_mark:
- Result text displays correctly :heavy_check_mark:
- Play Again button displays correctly :heavy_check_mark:
- Play Again button returns the user to the Landing Page :heavy_check_mark:
- Clicking/tapping on *Audio* icon launches audio modal :heavy_check_mark:
- Exit icon displays correctly and returns the user to the Landing Page on click/tap :heavy_check_mark:
- Sounds play on hover of Select Battleground cards, Exit icon and Audio icon :heavy_check_mark:
