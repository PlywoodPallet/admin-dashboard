Admin Dashboard

Requirements
- Replicate design file
- Already practiced using flex, Encouraged to use grid as much as possible for practice

TODO
- how to make the page minimum one viewport height? I'd like to fill the window even if content is empty
- For menu, how to make a large area clickable (text and some padding around it?)
- accessibility - do link images need alt text if the menu text is nearby?
- how to center images in primary menu along center line https://stackoverflow.com/questions/66178773/align-icon-to-text-size
- Make primary nav links change color of svg and text on hover
- When to use rem or em? https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984
- Dashboard text and logo don't align with menu icons. Does adding it to the primary-nav li fix this?
- How to make search bar size dynamic?
- Create a branch for converting secondary-nav from grid to flexbox. I'm having a difficult time getting everything positioned in grid
- hover effect for primary nav. onclick effect for secondary nav buttons
- Alignment of items in primary nav and secondary nav is off, would like to align images, buttons, and text to a universal centerline. Align-items: center did move the items, but isn't not perfectly centered

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