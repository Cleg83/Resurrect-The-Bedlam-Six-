# Resurrect The Bedlam Six: Testing

![Resurrect Louis Barabbas & The Bedlam Six shown on a variety of screen sizes](documents/readme-images/home-page-ss.png)

Visit the deployed site here: [Resurrect The Bedlam Six](https://cleg83.github.io/Resurrect-The-Bedlam-Six-Project/).

## CONTENTS

* [Automated testing](#automated-testing)
* [Manual testing](#manual-testing)

## Automated testing

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* [Home Page](documents/testing/w3c/index.png) - Passed

* [Video Page](documents/testing/w3c/video.png) - Passed

* [Gallery Page](documents/testing/w3c/gallery.png) - Passed

* [Contact Page](documents/testing/w3c/contact.png) - Passed

* [Submit Page](documents/testing/w3c/submit.png) - Passed

* [CSS](documents/testing/w3c/css.png) - Passed

- - -

### Lighthouse

Lighthouse in Chrome Devloper tools was used to test the performance, accessibility, best practices and SEO of each page. 

* [Home Page 1](documents/testing/lighthouse/index-lighthouse.png)

* [Home Page 2](documents/testing/lighthouse/index-lighthouse2.png)

* [Video Page](documents/testing/lighthouse/video-lighthouse.png)

* [Gallery Page 1](documents/testing/lighthouse/gallery-lighthouse.png)

* [Gallery Page 2](documents/testing/lighthouse/gallery-lighthouse2.png)

* [Gallery Page 3](documents/testing/lighthouse/gallery-lighthouse3.png)

* [Contact Page](documents/testing/lighthouse/contact-lighthouse.png)

* [Submit Page](documents/testing/lighthouse/submit-lighthouse.png)

#### Anomalies / outliers 

Due to recent changes to Google's third party cookie policy, the best practices scores on the pages with embedded iframes (the home page and the video page) only score 78. 

There is no way of improving this unless the embedded players are removed (not an option in this case) or a third party script is added but as this project is only HTML and CSS, that was also not an option.


## Manual testing

### Home page

##### Header / Navbar 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Band name link | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Home page link (active) | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opens | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opens | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opens| Pass |
| Shop page link | Directs the user to external Bandcamp page | Clicked on link | Opens external Bandcamp page in new tab | Pass |
| Links: hover | The color of all links should change to #a10f0 when hovered | Moved the mouse over each header link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

##### Home page content 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Embedded Bandcamp player | Plays music when the play button is clicked | Clicked button | Music plays | Pass |
| Band member column | Scrolls independently from Bandcamp Player| Scrolled through band members | Column scrolls independently | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link (active) | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Links: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Link icons:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

---


### Video page

##### Header / Navbar 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Band name link | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link (active) | Directs the user to the video page | Clicked on link | Video page opens | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opens | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opens| Pass |
| Shop page link | Directs the user to external Bandcamp page | Clicked on link | Opens external Bandcamp page in new tab | Pass |
| Links: hover | The color of all links should change to #a10f0 when hovered | Moved the mouse over each header link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

##### Video page content 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Video 1 | Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 2 | Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 3| Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 4 | Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 5 | Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 6 | Video plays when play button is clicked | Clicked video play button | Video plays | Pass |
| Video 1 | Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| Video 2 | Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| Video 3 | Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| Video 4| Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| Video 5 | Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| Video 6 | Allows video to play fullscreen | Clicked video fullscreen button | Video expands to full screen and plays | Pass |
| All videos:hover | Border color changes from cream to red on hover | Hovered mouse over each video | Border color changed from red to cream | Pass |
| All videos:not(:hover) | Border color changes from red to cream when mouse stops hovering | Moved mouse away from each video after hovering | Border color changed from cream to red | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link (active) | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Links: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Link icons:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

---

### Gallery page

##### Header / Navbar 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Band name link | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opens | Pass |
| Gallery page link (active) | Directs user to the gallery page | Clicked on link | Gallery page opens | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opens| Pass |
| Shop page link | Directs the user to external Bandcamp page | Clicked on link | Opens external Bandcamp page in new tab | Pass |
| Links: hover | The color of all links should change to #a10f0 when hovered | Moved the mouse over each header link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

##### Gallery page content

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Thumbnail 1 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 2 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 3 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 4 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 5 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 6 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 7 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 8 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 9 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 10 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 11 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| Thumbnail 12 | Correct image opens in new browser tab | Clicked thumbnail link | Correct image opened in new browser tab | Pass |
| All thumbnails: hover | Border color changes from cream to red on hover | Hovered mouse over each thumbnail | Border color changed from red to cream | Pass |
| All thumbnails:not(:hover) | Border color changes from red to cream when mouse stops hovering | Moved mouse away from each thumbnail after hovering | Border color changed from cream to red | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link (active) | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Links: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Link icons:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

---

### Contact page

##### Header / Navbar 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Band name link | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opens | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opens | Pass |
| Contact page link (active) | Directs users to contact page | Clicked on link | Contact page opens| Pass |
| Shop page link | Directs the user to external Bandcamp page | Clicked on link | Opens external Bandcamp page in new tab | Pass |
| Links: hover | The color of all links should change to #a10f0 when hovered | Moved the mouse over each header link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

##### Contact page content

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
Name input field | Allows user to input text | Input text | Field allows user to input text | Pass
Email address input field | Allows user to input email address | Input email address | Field allows user to input text | Pass
Text area | Allows user to input text | Input text | Field allows user to input text | Pass | 
Submit button | Only allows users to submit if all input fields are completed | Click submit button without completing Name field | Button wouldn't allow form submission | Pass |
Submit button | Only allows users to submit if all input fields are completed | Click submit button without completing Email address field | Button wouldn't allow form submission | Pass |
Submit button | Only allows users to submit if all input fields are completed | Click submit button without inputting any text into text area | Button wouldn't allow form submission | Pass |
Submit button | Only allows users to submit if all input fields are completed | Click submit button with all fields complete| Form submitted | Pass |
Submit button | Loads submission response page when clicked | Click submit button with all fields complete| Submission response page loads | Pass |
| Submit button: hover | Background color of submit button transitions to black | Hovered mouse over submit button | Background color of submit button transitioned to black | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link (active) | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Links: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Link icons:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

---

### Form submission page

##### Header / Navbar 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Band name link | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opens | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opens | Pass |
| Contact page link (active) | Directs users to contact page | Clicked on link | Contact page opens| Pass |
| Shop page link | Directs the user to external Bandcamp page | Clicked on link | Opens external Bandcamp page in new tab | Pass |
| Links: hover | The color of all links should change to #a10f0 when hovered | Moved the mouse over each header link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |

##### Form submission page content

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
Click here to return home link | Directs user to the home page | Clicked on link | Home page opens | Pass |
Click here to return home link:hover | Link changes color to black when hovered | Hovered mouse over link | Link changed color to black | Pass |
Click here to return home link:not(hover) | Link color changes back to #a10f0 when mouse stops hovering | Moved mouse away from link after hovering | Link changed color to #a10f0 | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link (active) | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Links: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Links:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to #a10f0 when hovered | Moved the mouse over each footer link to see if the text color changed to #a10f0 | Link changed color | Pass |
| Link icons:not(:hover) | The color of all links should change to black when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
