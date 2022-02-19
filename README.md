# HW-Wk1-CodeRefactor
Homework Week 1 - Code Refactor
# <Horiseon-Code-Refactor-2022>

## Site Link

[www.horiseon.com](https://timp1990.github.io/HW-Wk1-CodeRefactor/)

## Description

This project improves upon the existing Horiseon website by making it more accessible and fixing bugs.
The "client" supplied an existing html & css file for their website, which needed to have changes made to achieve the Acceptance Criteria

- Motivation: 
Our client would like their website to be more accessible, and score higher in SEO
- Why did you build this project: 
To make the Horiseon Website more accessible, and fulfill the needs of the client
- What problem does it solve: 
It makes the website more accessible and easier to find on Search engines such as google
- What did you learn: 
About website accessibility, how people with various disabilities intereact with websites, how google chrome makes two websites of each code (one for the GUI and one using the "accessibility tree")

## List of Fixes Conducted

1. Header tag replaces div class header
2. Alt texts added to all img elements
3. Website title changed to client name
4. Nav bar changed from div to nav
5. role and alt text added to "hero div" to provide alt text for banner image
6. In div content the "online-reputation-management" and "social media marketing" had both class and id attributes. Deleted id to clean up.
7. benefit-lead, benefit-cost and benefit-brand all defined in same curly brackets set to cleanup code. 
Please note: this could have also been done by adding the margin-bottom and color items to the benefits class, 
but the separate classes were left to allow for easy labelling of the divs
8. Same as 7. but with benefit-lead img, benefit-cost img and benefit-brand img
9. Benefits Section CSS put below Content Div CSS so that the html and CSS are in the ame order
10. Same as 7. But for ".search-engine-optimization", ".online-reputation-management" and ".social-media-marketing"
11. Same as 8. but with ".search-engine-optimization img", ".online-reputation-management img" and ".social-media-marketing img"
12. Same as 11 but with "content img" and ".content h2"
13. Anchor tags changed to take user down the page to correct section when the nav bar items are clicked.


## Installation

What are the steps required to install your project? 

No steps are required, the website is live and ready to view

## Usage

The website mayy be accessed via a web browser. 
An example of the site is shown in the image below.
![Example Site](assets/images/screenshot.png)

The items in the nav bar (in the tope right hand corner of the image above) may be clicked to scroll down to the appropriate part of the page.

## Credits

- Tim Polo

- USYD & Trilogy

- Google Searches

## License

MIT License

Copyright (c) [2022] [Timothy_Polo]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

CONDITION 1: The client (Horiseon) gives their express permission in writing to alter the code.

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. [https://choosealicense.com/](https://choosealicense.com/).



## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)


## Features

The website allows people to get information about the client's company and capabilities. It also provides links to other relevant pages.

## How to Contribute

[Contributor Covenant](https://www.contributor-covenant.org/) 

## Tests

None.

