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

The submit response page has an SEO score of 82 but this is only a page designed to direct users back to the home page. 


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
| Header links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Header links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active header link: Hover | The color of the header home page link should change to var(--red) when hovered | Moved the mouse over the home page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the header home page link should change to var(--black) when not hovered | Moved the mouse way from the home page link to see if the text color changed to var(--black) | Link changed color | Pass |

##### Home page content 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Embedded Bandcamp player: hover | Background color changes from var(--bg-dark) to var(--bg-light) when hovered | Hovered mouse over player | Background color changes from light to dark | Pass |
| Embedded Bandcamp player: mouse out | Background color changes from var(--bg-light) to var (--bg-dark) when mouse moved away | Moved mouse away from player | Background color changes from dark to light | Pass |
| Embedded Bandcamp player: Play button | Plays music when the play button is clicked | Clicked button | Music plays | Pass |
| Embedded Bandcamp player: Pause button | Pauses music when the pause button is clicked | Clicked button | Music pauses | Pass |
| Embedded Bandcamp player: Links | Opens external Bandcamp page when each link is clicked | Clicked each link | External Bandcamp page opened when each link was clicked | Pass |
|  Embedded Bandcamp player: Track list | User can scroll through the album tracks within the iframe | Scrolled through tracks | All tracks visible with no hidden overflow | Pass |
| Band member article: hover | Background color changes from var(--bg-dark) to var(--bg-light) when hovered | Hovered mouse over article | Background color changes from light to dark | Pass |
| Band member article: hover | Top padding of content increases to push content down from top of container when hovered / in focus | Hovered mouse over article | Top padding increased | Pass |
| Band member article: hover | Article text color changes from var(--cream) to var(--black) when hovered / in focus | Hovered mouse over article | Font changed color from var(--black) to var(--cream) | Pass |
| Band member article: hover | Article text top padding reduces to push it closer to member photo when hovered / in focus | Hovered mouse over article | Top padding of text reduced | Pass |
| Band member article  : mouse out | Background color changes from var(--bg-light) to var (--bg-dark) when mouse moved away | Moved mouse away from article| Background color changes from dark to light | Pass |
| Band member article: mouse out | Top padding of content decreases to push content up when not hovered / in focus | Moved mouse away from article | Top padding decreased | Pass |
| Band member article: mouse out | Article text color changes from var(--black) to var(--cream) when not hovered / in focus | Moved mouse away from article | Font changed color from var(--cream) to var(--black) | Pass |
| Band member article: mouse out | Top padding of the article text increases to push text away from content when not hovered / in focus | Moved mouse away from article | Top padding increased | Pass |
| Band member article | Scroll snaps to each member when scrolled | Scrolled through band members | Snaps to each member when scrolled | Pass |
| Band member article: Summary hidden | Summary displays when band member name is clicked | Clicked each band member name | Summary displayed to show more details | Pass |
| Band member article: Summary visible | Summary disappears when band member name is clicked | Clicked each band member name | Summary disappeared | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link (active) | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Footer menu links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Footer menu links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active footer link: Hover | The color of the footer home page link should change to var(--red) when hovered | Moved the mouse over the footer home page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the footer home page link should change to var(--black) when not hovered | Moved the mouse way from the footer home page link to see if the text color changed to var(--black) | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to var(--red) when hovered | Moved the mouse over each link icon to see if the text color changed to var(--red) | Link changed color | Pass |
| Link icons: mouse out | The color of all links should change to var(--black) when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

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
| Header links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Header links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active header link: Hover | The color of the header video page link should change to var(--red) when hovered | Moved the mouse over the video page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the header video home page link should change to var(--black) when not hovered | Moved the mouse way from the video page link to see if the text color changed to var(--black) | Link changed color | Pass |

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
| All videos:hover | Border color changes from var(--cream) to var(--red) on hover | Hovered mouse over each video | Border color changed from var(--cream) to var(--red) | Pass |
| All videos: mouse out | Border color changes from var(--red) to var(--cream) when mouse stops hovering | Moved mouse away from each video after hovering | Border color changed from var(--red) to var(--cream) | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link (active) | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Footer menu links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Footer menu links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active footer link: Hover | The color of the footer video page link should change to var(--red) when hovered | Moved the mouse over the footer video page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the footer video page link should change to var(--black) when not hovered | Moved the mouse way from the footer video page link to see if the text color changed to var(--black) | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to var(--red) when hovered | Moved the mouse over each link icon to see if the text color changed to var(--red) | Link changed color | Pass |
| Link icons: mouse out | The color of all links should change to var(--black) when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

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
| Header links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Header links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active header link: Hover | The color of the header gallery page link should change to var(--red) when hovered | Moved the mouse over the gallery page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the header gallery home page link should change to var(--black) when not hovered | Moved the mouse way from the gallery page link to see if the text color changed to var(--black) | Link changed color | Pass |

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
| All thumbnails: hover | Border color changes from var(--cream) to var(--red) on hover | Hovered mouse over each thumbnail | Border color changed from var(--cream) to vae(--red) | Pass |
| All thumbnails: mouse out | Border color changes from var(--red) to var(--cream) when mouse stops hovering | Moved mouse away from each thumbnail after hovering | Border color changed from var(--red) to var(--cream) | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link (active) | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Footer menu links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Footer menu links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active footer link: Hover | The color of the footer gallery page link should change to var(--red) when hovered | Moved the mouse over the footer gallery page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the footer gallery page link should change to var(--black) when not hovered | Moved the mouse way from the footer gallery page link to see if the text color changed to var(--black) | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to var(--red) when hovered | Moved the mouse over each link icon to see if the text color changed to var(--red) | Link changed color | Pass |
| Link icons: mouse out | The color of all links should change to var(--black) when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

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
| Header links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Header links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active header link: Hover | The color of the header contact page link should change to var(--red) when hovered | Moved the mouse over the contact page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the header contact home page link should change to var(--black) when not hovered | Moved the mouse way from the contact page link to see if the text color changed to var(--black) | Link changed color | Pass |

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
| Footer menu links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Footer menu links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active footer link: Hover | The color of the footer contact page link should change to var(--red) when hovered | Moved the mouse over the footer contact page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the footer contact page link should change to var(--black) when not hovered | Moved the mouse way from the footer contact page link to see if the text color changed to var(--black) | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to var(--red) when hovered | Moved the mouse over each link icon to see if the text color changed to var(--red) | Link changed color | Pass |
| Link icons: mouse out | The color of all links should change to var(--black) when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |

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
| Header links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Header links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active header link: Hover | The color of the header contact page link should change to var(--red) when hovered | Moved the mouse over the contact page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the header contact home page link should change to var(--black) when not hovered | Moved the mouse way from the contact page link to see if the text color changed to var(--black) | Link changed color | Pass |

##### Form submission page content

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
Click here to return home link | Directs user to the home page | Clicked on link | Home page opens | Pass |
Click here to return home link:hover | Link changes color from var(--red) to var(--black) when hovered | Hovered mouse over link | Link changed color from var(--red) to var(--black) | Pass |
Click here to return home link: mouse out | Link color changes from var(--black) to var(--red) when mouse stops hovering | Moved mouse away from link after hovering | Link changed color from var(--black) to var(--red) | Pass |

##### Footer 

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home page link | Link directs user back to the home page | Clicked on link | Home page reloads | Pass |
| Video page link | Directs the user to the video page | Clicked on link | Video page opened | Pass |
| Gallery page link | Directs user to the gallery page | Clicked on link | Gallery page opened | Pass |
| Contact page link (active) | Directs users to contact page | Clicked on link | Contact page opened | Pass |
| Shop link | Directs the user to external Bandcamp page | Clicked on link | Opened external Bandcamp page in new tab | Pass |
| Footer menu links: hover | The color of all links should change to var(--red) when hovered | Moved the mouse over each header link to see if the text color changed to var(--red) | Link changed color | Pass |
| Footer menu links: mouse out | The color of all links should change to var(--nav-text) when the link is no longer hovered | Moved the mouse away from each header link after hovering | Link changed color | Pass |
|Active footer link: Hover | The color of the footer contact page link should change to var(--red) when hovered | Moved the mouse over the footer contact page link to see if the text color changed to var(--red) | Link changed color | Pass |
|Active header link: mouse out | The color of the footer contact page link should change to var(--black) when not hovered | Moved the mouse way from the footer contact page link to see if the text color changed to var(--black) | Link changed color | Pass |
| Facebook icon link | Directs the user to external Facebook page page | Clicked Facebook link | Opens external Facebook page in new tab | Pass |
| Twitter / X icon link | Directs the user to external Twitter / X page |Clicked Twitter / X link | Opens external Twitter / X page in new tab |  Pass |
| Instagram icon link | Directs the user to external Instagram page |Clicked Instagram link | Opens external Instagram page in new tab | Pass |
| Youtube icon link | Directs the user to external Youtube page |Clicked Youtube link | Opens external Youtube page in new tab | Pass |
| Bandcamp icon link | Directs the user to external Bandcamp page |Clicked Bandcamp link | Opens external Bandcamp page in new tab | Pass |
| Link icons: hover | The color of each link should change to var(--red) when hovered | Moved the mouse over each link icon to see if the text color changed to var(--red) | Link changed color | Pass |
| Link icons: mouse out | The color of all links should change to var(--black) when the link is no longer hovered | Moved the mouse away from each footer link after hovering | Link changed color | Pass |
