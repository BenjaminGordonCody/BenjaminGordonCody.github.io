# A Portfolio Website
## Brief
This website was started as part of the Code Nation "Develop" course, a level 2 course that covered the basics of HTML and CSS. I was able to finish it as part of the Code Nation "Master" course, a level 4 course covering full-stack web development.

I wanted the website to have a bright, playful look that was a bit softer than "tech" pages often are. I wanted to lean into the idea that software development and data science are both forms of craft, and  to utilise elements that spoke to the personal and tactile qualities of craft that we might not think of as part of the 'big data' world. The colours, shapes and patterns I chose were chosen for their resemblance to the sugar and tissue papers used in scrap-booking and collage. Similarly, the use of card-box layouts, animation and hand-drawn elements was meant to create the sense of overlapping papers that haven't been glued down yet. 

The mobile version of the site is simplified to contain less textures, no animation, and a "burger bars" menu interface. This was to ensure usability on low-end devices, and also to avoid a sense of clutter in the smaller screen.

## Code Structure
Each page has 3 major div containers; foreground, unique content, and background. These are seperated along the z-axis in CSS. The generic content in foreground and background containers is supplied by a shared javascript function, so that any updates to this material wouldn't require multiple edits.  Animation is largely achieved by editing the "onhover" behaviour of page elements. Where this has proved difficult (for instance, when foreground elements eclipse target background elements) javasript event-listeners are used to simulate the same behaviour. 

## Improvements
- The structure of this CSS is sprawling, and the next stage in refactoring it (if I decide to) will be seperating the different elements into a few smaller CSS files. 

