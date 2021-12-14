# Code Refactor

Code Refactor improves the codebase of the website 'Horiseon' so that it follows all the accessibility standards. The website is now optimized for search engines.

The improvements done are:
- The 'Search Engine Optimization' link in navigation bar is fixed. Now all links are working.
- Added and replaced semantic HTML tags instead of all divs. This improved the accessibility of the website.
- Added alt attribute to all images to improve accessibility.
- Added a descriptive title to the page.
- When divs were replaced by semantic HTML tags, the corresponding selectors are updated in the stylesheet. e.g. .header (class selector) is changed to header (element selector).
- In stylesheet, CSS selectors are organized to follow  semantic structure of HTML elements.
- CSS properties are consolidated to a single selector wherever possible. e.g. The CSS properties of img and h2 in each of the 3 sections of the class content are now consolidated into a single selector .content h2 and .content img .
- Added proper comments to both HTML file and stylesheet.
