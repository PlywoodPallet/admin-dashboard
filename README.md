Admin Dashboard

Requirements
- Replicate design file
- Already practiced using flex, Encouraged to use grid as much as possible for practice

TODO
- how to make the page minimum one viewport height? I'd like to fill the window even if content is empty (height: 100vh works but what if content overflows)
- For menu, how to make a large area clickable (text and some padding around it?)
- accessibility - do link images need alt text if the menu text is nearby?
- how to center images in primary menu along center line https://stackoverflow.com/questions/66178773/align-icon-to-text-size
- Make primary nav links change color of svg and text on hover
- When to use rem or em? https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984
- Dashboard text and logo don't align with menu icons. Does adding it to the primary-nav li fix this?
- How to make search bar size dynamic? For some reason width: 100% doesn't work
- Create a branch for converting secondary-nav from grid to flexbox. I'm having a difficult time getting everything positioned in grid
- hover effect for primary nav. onclick effect for secondary nav buttons
- Alignment of items in primary nav and secondary nav is off, would like to align images, buttons, and text to a universal centerline. Align-items: center did move the items, but isn't not perfectly centered
- Is there some sort of vscode extension that will double check my CSS selectors are named correctly? Lots of frustration due to a typo
- how do I disable the <a> tag from being recognized by grid. When it sees it wrap two divs, it considers it one grid element instead of two. My current workaround is settings <a class="grid-container"> but isn't good for readability (better that he div above it gets class="grid-container")
- Make page function buttons bigger
- Encapsulate page sections in <nav> <header> <main> <footer> tags
- Would min-height be useful for project cards?
- Secondary-nav - add padding on right side same as on the left
- this h2 and h3 are only used in content div, is it good practice to make the selectors as specific as possible? 

Project History
- Researched CSS naming conventions https://www.freecodecamp.org/news/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849/
- Researched when to use a id or class. Id is for unique elements, class is for repeat elements
- For some reason one grid was not enough to make the your-projects, announcements, trending layout. I had to make two. Wondering if there is a grid setting I'm missing
- SVGs can be filled with different color using CSS https://stackoverflow.com/questions/22252472/how-to-change-the-color-of-an-svg-element
- Importing fonts: use link instead of @import. Latter defers loading https://stackoverflow.com/questions/12316501/including-google-fonts-link-or-import
- gap is the coolest css property, decreases manually messing with padding and margin
- The more I use CSS, such as flexbox and grid, the more I'm interested in learning responsive design
- Learned how to use z-index to allow a border-box shadow to be visible and not covered up https://css-tricks.com/forums/topic/box-shadow-is-getting-covered-up/
- Tried to make secondary nav with grid but it was too difficult, used flexbox instead
- I've been defaulting to ids, but I should be defaulting to class. Class can be used more than once, will be useful just in case a unique element needs to be repeated later
- Upper right corner is likely a notifications and settings area. Named it as such.
- Created dummy links for all possible links
- Grid "auto" parameter is powerful and should be my default if I'm not sure about proportions, rather than 1fr
- Horizontal dividing line and how to style them https://www.w3schools.com/tags/tag_hr.asp
- The purpose of this exercise was to use grid only, but I broke down and used flex for 1d elements that are tricky to do with grid to save time.
- Did not realize so many websites use a dark gray or light gray as an alternative to black or white text. It gives a subtle structure of a website (like the content card text and announcements text). The resulting lower contrast is easier on the eyes https://uxdesign.cc/designers-should-avoid-pure-black-typography-but-which-dark-gray-should-we-use-2d7faa07083a