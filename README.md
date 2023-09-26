# Aria (Major project) ass CSS
## Hosted Link
You can view the project live at [View Live Project](https://aria-by-saiful-islam.netlify.app/)
## Table of Contents
Click 👆 any section to navigate between that section.
- [Common styles](#common-styles)
- [Nav Section](#nav-section)
- [Header Section](#header-section)
- [About Section](#about-section)
- [Services Section](#services-section)
- [Call Me Section](#call-me-section)
- [Projects Section](#projects-section)
- [Consultants Section](#consultants-section)
- [Contact Section](#contact-section)
- [Footer Section](#footer-section)
## CSS Styles

### `:root` Variables
- `--primary-color: #14bf98;`: Defines a primary color variable.
- `--secondary-color: #dfe5ec;`: Defines a secondary color variable.
- `--white: #ffffff;`: Defines a white color variable.
- `--black: #000000;`: Defines a black color variable.

### Common styles
##### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.
- `font-family: 'Open Sans', sans-serif;`: Specifies the default font for the entire document.


##### HTML (`html`)
- `scroll-behavior: smooth;`: Adds smooth scrolling behavior to anchor links within the HTML document.

##### Container (`div.container`)
- `.container`:
  - `width: 100%;`: Makes the container span the entire width.
  - `max-width: 1140px;`: Sets the maximum width of the container to 1140 pixels.
  - `margin: 0 auto;`: Centers the container horizontally on the page.

##### Headings (`h2`, `h3`, `h4`)
- `font-weight: 700;`: Sets a bold font weight for headings.
- `font-family: 'Montserrat', sans-serif;`: Specifies the font family for headings.

##### Paragraphs (`p`)
- `color: #787976;`: Sets the text color for paragraphs.
- `font-size: 1rem;`: Sets the font size for paragraphs.
- `font-weight: 400;`: Sets the font weight for paragraphs.

##### Links (`a`)
- `text-decoration: none;`: Removes underlines from links.
- `color: var(--white);`: Sets the default text color for links.
- `color: var(--primary-color);` (on hover): Changes the text color of links when hovered.

##### Images (`img`)
- `width: 100%;`: Sets the width of images to 100%.
- `height: 100%;`: Sets the height of images to 100%.

### Nav Section
##### Navigation Bar (`nav`)
- `display: flex;`: Arranges items in a row.
- `justify-content: space-between;`: Separates items with space.
- `align-items: center;`: Vertically centers items.
- `position: fixed;`: Fixes the navigation bar at the top of the page.
- `width: 100vw;`: Sets the width of the navigation bar to 100% of the viewport.
- `padding: 0.5rem 5rem;`: Adds padding to the navigation bar.
- `background: #113448;`: Sets the background color of the navigation bar.

##### Navigation Items (`ul.nav-items`)
- `display: flex;`: Arranges navigation items in a row.
- `list-style: none;`: Removes list bullets from navigation items.

##### Navigation Links (`li a`)
- `font-size: 0.875rem;`: Sets the font size for navigation links.
- `color: var(--white);`: Sets the text color for navigation links.
- `text-transform: uppercase;`: Converts text to uppercase.
- `font-weight: 600;`: Sets the font weight for navigation links.
- `padding: 0.25rem 0.75rem;`: Adds padding to navigation links.
- `transition: 0.2s ease;`: Adds a smooth transition effect on hover.

##### Active Navigation Link (`li.active a`)
- `color: var(--primary-color);`: Sets the text color for the active navigation link.

##### Social Icons (`.social-icons a`)
- `display: flex;`: Arranges social icons in a row.
- `flex-direction: column;`: Arranges social icons in a column.
- `justify-content: center;`: Vertically centers social icons.
- `align-items: center;`: Horizontally centers social icons.
- `width: 1.6rem;`: Sets the width of social icons.
- `height: 1.6rem;`: Sets the height of social icons.
- `color: var(--white);`: Sets the text color for social icons.
- `background: url('/assets/images/hexagon-green.svg') no-repeat;`: Sets the background image for social icons.
- `background-size: contain;`: Sizes the background image to contain within the icon.
- `transition: all .3s;`: Adds a smooth transition effect on hover.

##### Hovered Social Icons (`.social-icons a:hover`)
- `background: url('/assets/images/hexagon-white.svg') no-repeat;`: Changes the background image on hover.
- `color: var(--primary-color);`: Changes the text color on hover.

### Hero Section

##### Hero Container (`section.hero`)
- `padding-top: 14.75rem;` and `padding-bottom: 17.75rem;`: Sets the top and bottom padding of the hero section.
- `background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.5)), url(/assets/images/header-background.jpg);`: Applies a background gradient overlay and an image background to the hero section.
- `background-repeat: no-repeat;`: Prevents the background image from repeating.
- `background-size: cover;`: Scales the background image to cover the entire container.
- `background-position: center;`: Centers the background image horizontally and vertically.

##### Text Container (`div.text-container`)
- `margin: 6.5rem auto 3rem auto;`: Sets margins for the text container.
- `text-align: center;`: Centers the text within the container.

##### Heading (`h1`)
- `color: var(--white);`: Sets the text color for the heading.
- `margin-bottom: 0.5rem;`: Adds margin to the bottom of the heading.
- `font-size: 3.5rem;`: Sets the font size for the heading.

##### Paragraph (`p`)
- `color: var(--secondary-color);`: Sets the text color for the paragraph.
- `font-size: 1.125rem;`: Sets the font size for the paragraph.
- `margin-bottom: 2rem;`: Adds margin to the bottom of the paragraph.

##### Button (`a.btn`)
- `padding: 1rem 2.125rem;`: Sets padding for the button.
- `color: var(--white);`: Sets the text color for the button.
- `text-decoration: none;`: Removes underlines from the button text.
- `background: var(--primary-color);`: Sets the background color for the button.
- `border: 0.125rem solid var(--primary-color);`: Adds a border to the button.
- `font-family: Montserrat, sans-serif;`: Specifies the font family for the button.
- `font-size: 0.75rem;`: Sets the font size for the button.
- `font-weight: 700;`: Sets the font weight for the button.
- `border-radius: 0.25rem;`: Adds rounded corners to the button.
- `-webkit-border-radius: 0.25rem;`: Adds rounded corners for webkit browsers.
- `-moz-border-radius: 0.25rem;`: Adds rounded corners for Mozilla browsers.
- `-ms-border-radius: 0.25rem;`: Adds rounded corners for Microsoft browsers.
- `-o-border-radius: 0.25rem;`: Adds rounded corners for Opera browsers.

##### Hovered Button (`a.btn:hover`)
- `background: transparent;`: Makes the button background transparent on hover.
- `color: var(--primary-color);`: Changes the text color to the primary color on hover.

### Intro Section

##### Intro Container (`section.intro`)
- `padding: 6.875rem 0 3rem 0;`: Sets padding for the intro section.

##### Intro Content (`div.intro-1`)
- `display: flex;`: Arranges the intro content in a row.
- `justify-content: space-between;`: Separates the content with space.
  
##### Text Side (`div.text-side`)
- `width: 40%;`: Sets the width of the text side.
  
##### Heading (`h2`)
- `margin-bottom: 1.375rem;`: Adds margin to the bottom of the heading.

##### Paragraphs (`p`)
- `margin-bottom: 1rem;`: Adds margin to the bottom of paragraphs.
- `line-height: 1.5;`: Sets the line height for paragraphs.
  
##### Testimonial Text (`p.testimonial-text`)
- `font-style: italic;`: Applies italic style to the testimonial text.
  
##### Testimonial Author (`div.testimonial-author`)
- `font-size: 1rem;`: Sets the font size for the testimonial author.
- `font-weight: 700;`: Sets the font weight for the testimonial author.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family for the testimonial author.

##### Image Box (`div.image-box`)
- `width: 55%;`: Sets the width of the image box.
- `overflow: hidden;`: Hides overflow content.
- `border-radius: 0.25rem;`: Adds rounded corners to the image box.
- Vendor-specific prefixes for border-radius.
  
##### Image (`img`)
- `width: 100%;`: Sets the width of the image to 100%.
- `transition: all .3s;`: Adds a smooth transition effect on hover.
- Vendor-specific prefixes for transitions.
  
##### Hovered Image (`img:hover`)
- `transform: scale(1.1);`: Scales the image on hover.
- Vendor-specific prefixes for transforms.

##### Cards Wrapper (`div.cards-wrapper`)
- `display: flex;`: Arranges cards in a row.
- `justify-content: space-between;`: Separates cards with space.
- `align-items: center;`: Vertically centers cards.
- `padding-top: 3rem;` and `padding-bottom: 2.875rem;`: Adds padding to the top and bottom of the cards wrapper.

##### Card (`div.card`)
- `.icon-box` inside card:
  - `width: 6rem;` and `height: 6rem;`: Sets dimensions for the icon box.
  - `background`: Sets a background image for the icon box.
  - `background-position`: Sets the background position to the center.
  - `background-repeat`: Prevents background repetition.
  - `background-size`: Sets the background size.
  - `display: flex;`: Arranges elements within the icon box.
  - `align-items: center;`: Vertically centers elements.
  - `justify-content: center;`: Horizontally centers elements.
  - `margin-bottom: 1rem;`: Adds margin to the bottom of the icon box.
- `svg` inside icon box:
  - `font-size: 2rem;`: Sets the font size for SVG icons.
  - `color: var(--white);`: Sets the color of SVG icons.
- `.card-title` inside card:
  - `margin-bottom: 0.875rem;`: Adds margin to the bottom of card titles.

### Services Section

##### Services Container (`section.services`)
- `padding-top: 6.625rem;` and `padding-bottom: 6.25rem;`: Sets padding for the services section.
- `background: #fbfbfb;`: Sets the background color for the section.

##### Section Title (`div.section-title`)
- `text-align: center;`: Centers the section title.

##### Heading (`h2`)
- `text-align: center;`: Centers the heading.
- `margin-bottom: 3.25rem;`: Adds margin to the bottom of the heading.

##### Services Card Wrapper (`div.services-card-wrapper`)
- `width: 100%;`: Sets the width of the card wrapper.
- `display: flex;`: Arranges cards in a row.
- `justify-content: space-between;`: Separates cards with space.
- `gap: 1rem;`: Adds spacing between cards.
- `flex-wrap: wrap;`: Allows cards to wrap to the next row if there isn't enough space.

##### Card (`div.card`)
- `max-width: 20.875rem;`: Sets the maximum width for the card.
- `background: #fff;`: Sets the background color for the card.
- `border: 1px solid #ebe8e8;`: Adds a border to the card.
- `border-radius: 0.375rem;`: Adds rounded corners to the card.
- Vendor-specific prefixes for border-radius.

##### Card Image (`div.card-image`)
- `overflow: hidden;`: Hides overflow content.
- `border-top-left-radius: 0.375rem;` and `border-top-right-radius: 0.375rem;`: Adds rounded corners to the top of the card image.
- `width: 100%;`: Sets the width of the card image.

##### Card Body (`div.card-body`)
- `width: 100%;`: Sets the width of the card body.
- `padding: 2.25rem 2rem;`: Sets padding for the card body.

##### Card Title (`h3.card-title`)
- `text-align: center;`: Centers the card title.
- `margin-bottom: 0.75rem;`: Adds margin to the bottom of the card title.

##### Card Paragraph (`p`)
- `margin-bottom: 1rem;`: Adds margin to the bottom of paragraphs.

##### Card List (`ul`)
- `margin-bottom: 1.5rem;`: Adds margin to the bottom of the list.
- `list-style: none;`: Removes list bullets from the list.

##### Card List Item (`li`)
- `display: flex;`: Arranges list items in a row.
- `align-items: center;`: Vertically centers list items.
- `margin-bottom: 0.375rem;`: Adds margin to the bottom of list items.

##### Card List Item Icon (`svg`)
- `color: var(--primary-color);`: Sets the color of list item icons.
- `font-size: 0.5rem;`: Sets the font size for list item icons.
- `margin-right: 0.625rem;`: Adds margin to the right of list item icons.

##### Card Price (`p.price`)
- `color: #484a46;`: Sets the text color for the price.
- `font-size: 1rem;`: Sets the font size for the price.
- `font-weight: 700;`: Sets the font weight for the price.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family for the price.
- `text-align: center;`: Centers the price text.

##### Card Price Span (`span`)
- `color: var(--primary-color);`: Sets the color of the price span.

##### Button Container (`div.button-container`)
- `text-align: center;`: Centers the button container.

##### Button (`a.btn`)
- `padding: .7rem 1.875rem;`: Sets padding for the button.
- `background: var(--primary-color);`: Sets the background color for the button.
- `color: var(--white);`: Sets the text color for the button.
- `text-decoration: none;`: Removes underlines from the button text.
- `font-size: 0.75rem;`: Sets the font size for the button.
- `font-weight: 700;`: Sets the font weight for the button.
- `border: 0.125rem solid var(--primary-color);`: Adds a border to the button.
- `border-radius: 0.25rem;`: Adds rounded corners to the button.
- Vendor-specific prefixes for border-radius.
- `transition: all 0.3s;`: Adds a smooth transition effect on hover.
- Vendor-specific prefixes for transitions.

##### Hovered Button (`a.btn:hover`)
- `background-color: var(--white);`: Changes the background color of the button on hover.
- `color: var(--primary-color);`: Changes the text color of the button on hover.
### Accordion Section

##### Accordion Container (`section.accordian`)
- `width: 100%;`: Sets the width of the accordion section to 100%.
- `height: 34.625rem;`: Sets the height of the accordion section to 34.625rem.
- `display: flex;`: Uses a flex display for positioning content.

##### Image Side (`div.image-side`)
- `width: 50%;` and `height: inherit;`: Sets the dimensions for the image side, with a width of 50% and the height is inherited.
- `background`: Sets the background image for the image side with properties like `url(/assets/images/accrodian-1bg.jpg)`, `background-size: cover;`, `background-position: center center;`, and `background-repeat: no-repeat;`.

##### Content Side (`div.content-side`)
- `width: 50%;`: Sets the width of the content side to 50%.

##### Accordion Container (`div.accordion-container`)
- `padding-top: 6.375rem;`: Adds padding to the top of the accordion container with a value of 6.375rem.
- `width: 88%;` and `max-width: 28rem;`: Sets the maximum width for the accordion container to 28rem and a width of 88%.
- `margin-left: 5rem;`: Adds margin to the left of the accordion container with a value of 5rem.

##### Heading (`h2`)
- `margin-bottom: 1.625rem;`: Adds margin to the bottom of the heading with a value of 1.625rem.

##### Accordion Items (`div.item`)
- `margin-bottom: 2rem;`: Adds margin to the bottom of each accordion item with a value of 2rem.

##### Circle Numbering (`span.circle-numbering`)
- `display: inline-block;`: Displays the circle numbering inline.
- `width: 2.25rem;` and `height: 2.25rem;`: Sets the dimensions for the circle numbering with a width and height of 2.25rem.
- `margin-right: 0.875rem;`: Adds margin to the right of the circle numbering with a value of 0.875rem.
- `border`: Sets a border for the circle numbering with properties like `0.125rem solid #484a46;`.
- `border-radius: 50%;`: Adds a rounded border to create a circle.
- `color: #484a46;`: Sets the text color for the circle numbering to #484a46.
- `font: 700 1rem/2.125rem "Montserrat", sans-serif;`: Defines font properties, including font weight, size, line height, and font family.
- `text-align: center;`: Sets the text alignment to center.
- `vertical-align: middle;`: Vertically aligns the circle numbering.
- `cursor: pointer;`: Changes the cursor to a pointer on hover.
- `transition`: Adds a smooth transition effect with properties like `all 0.2s ease;`.

##### Accordion Title (`span.accordion-title`)
- `display: inline-block;`: Displays the accordion title inline.
- `margin-top: 0.125rem;` and `margin-bottom: 0.25rem;`: Adds margin to the top and bottom of the accordion title.
- `color: #484a46;`: Sets the text color for the accordion title to #484a46.
- `font-size: 1.25rem;`: Sets the font size for the accordion title to 1.25rem.
- `font-weight: 700;`: Sets the font weight for the accordion title to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family for the accordion title.
- `vertical-align: middle;`: Vertically aligns the accordion title.
- `cursor: pointer;`: Changes the cursor to a pointer on hover.
- `transition`: Adds a smooth transition effect with properties like `all 0.2s ease;`.

##### Hovered Circle Numbering and Title (`.item:hover .circle-numbering` and `.item:hover .accordion-title`)
- Changes the background color and text color of the circle numbering and title on hover.

##### Accordion Paragraph (`p.accordion-para`)
- `margin-left: 3.125rem;`: Adds margin to the left of the accordion paragraph with a value of 3.125rem.

##### Active Item (`.active .accordian-heading .circle-numbering` and `.active .accordian-heading .accordion-title`)
- Changes the appearance of the circle numbering and title for the active item.

##### Accordion Section End

### Tab Section

##### Tab Section Container (`section.tab-section`)
- `width: 100%;`: Sets the width of the tab section to 100%.
- `height: 36.125rem;`: Sets the height of the tab section to 36.125rem.
- `display: flex;`: Uses a flex display for positioning content.

##### Image Side (`div.image-side`)
- `width: 50%;` and `height: inherit;`: Sets the dimensions for the image side, with a width of 50% and the height is inherited.
- `background`: Sets the background image for the image side with properties like `url(/assets/images/accrodian-2bg.jpg)`, `background-size: cover;`, `background-position: center center;`, and `background-repeat: no-repeat;`.

##### Content Side (`div.content-side`)
- `width: 50%;`: Sets the width of the content side to 50%.

##### Tab Content Container (`div.tab-content-container`)
- `padding-top: 6.375rem;`: Adds padding to the top of the tab content container with a value of 6.375rem.
- `width: 88%;` and `max-width: 28rem;`: Sets the maximum width for the tab content container to 28rem and a width of 88%.
- `float: right;` and `margin-right: 5rem;`: Floats the container to the right and adds margin to the right with a value of 5rem.

##### Tab Items (`div.tab-items`)
- `display: flex;`: Arranges tab items in a row.
- `gap: 2rem;`: Adds a gap of 2rem between tab items.
- `margin-bottom: 1.5rem;`: Adds margin to the bottom of tab items with a value of 1.5rem.

##### Tab Item (`div.tab-items .item`)
- `display: flex;`: Displays tab items as flex elements.
- `align-items: center;`: Vertically aligns tab item content.
- `cursor: pointer;`: Changes the cursor to a pointer on hover.

##### Tab Item Icon (`div.tab-items .item svg`)
- `color: #c1cace;`: Sets the color of the tab item icon.
- `font-size: 1rem;`: Sets the font size for the tab item icon to 1rem.
- `margin-right: .525rem;`: Adds margin to the right of the icon with a value of 0.525rem.
- `transition`: Adds a smooth transition effect with properties like `all 0.2s ease;`.

##### Tab Item Text (`div.tab-items .item span`)
- `color: #c1cace;`: Sets the color of the tab item text.
- `font-size: 1.375rem;`: Sets the font size for the tab item text to 1.375rem.
- `font-weight: 700;`: Sets the font weight for the tab item text to 700.
- `transition`: Adds a smooth transition effect with properties like `all 0.2s ease;`.

##### Active Tab Item (`.tab-items .item.active *`)
- Changes the color of the active tab item's icon and text to `var(--primary-color)`.

##### Hovered Tab Item (`.tab-items .item:hover *`)
- Changes the color of the tab item's icon and text to `var(--primary-color)` on hover.

##### Tab Content Panel (`div.tab-content-panel`)
- `color: #484a46;`: Sets the text color for the tab content panel to #484a46.
- `font-size: 1.25rem;`: Sets the font size for the tab content panel to 1.25rem.
- `font-weight: 700;`: Sets the font weight for the tab content panel to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family for the tab content panel.
- `margin-bottom: .5rem;`: Adds margin to the bottom of the tab content panel with a value of 0.5rem.

##### Tab Content Text (`p`)
- `color: #787976;`: Sets the text color for the tab content text to #787976.
- `font-size: 1rem;`: Sets the font size for the tab content text to 1rem.
- `font-weight: 400;`: Sets the font weight for the tab content text to 400.
- `font-family: "Open Sans", sans-serif;`: Specifies the font family for the tab content text.
- `margin-bottom: 1rem;`: Adds margin to the bottom of the tab content text with a value of 1rem.

##### Tab Content Link (`p a`)
- `color: var(--primary-color);`: Sets the text color for the tab content link to `var(--primary-color)`.

##### Progress Title (`p.progress-title`)
- `color: #484a46;`: Sets the text color for the progress title to #484a46.
- `font-size: 0.875rem;`: Sets the font size for the progress title to 0.875rem.
- `font-weight: 600;`: Sets the font weight for the progress title to 600.
- `font-family: "Open Sans", sans-serif;`: Specifies the font family for the progress title.
- `margin-bottom: .25rem;`: Adds margin to the bottom of the progress title with a value of 0.25rem.

##### Progress Bar (`div.progress`)
- `height: 1.375rem;`: Sets the height of the progress bar to 1.375rem.
- `margin-bottom: 1.375rem;`: Adds margin to the bottom of the progress bar with a value of 1.375rem.
- `background: #f9fafc;`: Sets the background color of the progress bar to #f9fafc.
- `border-radius`: Adds a border-radius to the progress bar with properties like `0.125rem`.

##### Progress Bar Fill (`div.progress .progress-bar`)
- `height: 100%;`: Sets the height of the progress bar fill to 100%.
- `background`: Sets the background color of the progress bar fill using a linear gradient.
- Width for each progress bar is adjusted via separate classes (`.progress-1`, `.progress-2`, `.progress-3`).

##### Tab Section End
``
### Customer Testimonial Section

##### Testimonial Section Container (`section.testimonial`)
- `padding: 6.375rem 0 6.5rem 0;`: Sets padding for the testimonial section.
- `text-align: center;`: Aligns text content to the center.

##### Testimonial Section Title (`testimonial h2`)
- `margin-bottom: 0.75rem;`: Adds margin at the bottom of the title.

##### Testimonial Section Paragraph (`testimonial .p-heading`)
- `width: 55%;`: Sets the width of the paragraph to 55%.
- `margin: 0 auto 3.5rem auto;`: Adds margin to the paragraph.

##### Testimonial Arrows (`.left-arrow, .right-arrow`)
- `width: 1.375rem;`: Sets the width of the arrow icons to 1.375rem.

##### Swiper Container (`.swipper`)
- `width: 100%;`: Sets the width of the swiper container to 100%.
- `position: relative;`: Positions the swiper container relative to its normal position in the document flow.

##### Swiper Wrapper (`.swipper-wrapper`)
- `display: flex;`: Displays the swiper items as flex elements.
- `overflow: scroll;`: Adds scroll overflow to the swiper wrapper.
- `gap: 55px;`: Adds a gap of 55px between swiper items.

##### Swiper Wrapper Scrollbar (`swipper-wrapper::-webkit-scrollbar`)
- `width: 0;` and `height: 0;`: Hides the scrollbar in Webkit browsers.

##### Swiper Card (`.swipper-card`)
- `min-width: 319.667px;`: Sets a minimum width for the swiper card.
- `margin-right: 20px;`: Adds margin to the right of swiper cards.

##### Customer Image (`swipper-card .customer-image img`)
- `width: 6rem;` and `height: 6rem;`: Sets the width and height of the customer image.
- `margin: 0 auto 0.5rem auto;`: Adds margin to the customer image.
- `border-radius: 50%;`: Sets a border-radius of 50% to make the image circular.

##### Testimonial Text (`.testimonial-text`)
- `margin-bottom: 0.625rem;`: Adds margin at the bottom of the testimonial text.
- `font-style: italic;`: Sets the text style to italic.
- `word-wrap: break-word;`: Allows long words to be broken and wrap onto the next line if needed.

##### Testimonial Author (`.testimonial-author`)
- `color: #484a46;`: Sets the text color for the testimonial author.
- `font-size: 1rem;`: Sets the font size for the testimonial author to 1rem.
- `font-weight: 700;`: Sets the font weight for the testimonial author to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family for the testimonial author.

##### Swiper Buttons (`.swipper-btn`)
- `position: absolute;`: Positions the swiper buttons absolutely.
- `top: 50%;`: Sets the top position of the swiper buttons to the center.
- `cursor: pointer;`: Changes the cursor to a pointer.
- `font-size: 1.5rem;`: Sets the font size for the swiper buttons to 1.5rem.
- `color: #787976;`: Sets the color of the swiper buttons.
- `font-weight: 400;`: Sets the font weight for the swiper buttons to 400.

##### Swiper Left Button (`.swipper-left-btn`)
- `left: -2rem;`: Positions the left swiper button to the left with a margin of -2rem.

##### Swiper Right Button (`.swipper-right-btn`)
- `right: -2rem;`: Positions the right swiper button to the right with a margin of -2rem.

##### Customer Testimonial Section End
### Call Me Section

##### Call Me Section Container (`section.call-me`)
- `padding-top: 7rem;` and `padding-bottom: 5.625rem;`: Sets padding for the top and bottom of the call me section.
- `background: #153e52;`: Sets the background color to a dark blue.
- `display: flex;`: Displays the call me section as a flex container.

##### Call Me Section Container (`.call-me .container`)
- `display: flex;`: Displays the container as a flex container.
- `justify-content: space-between;`: Aligns the child elements with space between them horizontally.

##### Left Side (`call-me .left-side`)
- `width: 50%;`: Sets the width of the left side to 50%.
- `margin: 1.375rem 1.75rem 0 3rem;`: Sets the margins for the left side.

##### Call Me Section Title (`call-me .left-side h2`)
- `color: var(--white);`: Sets the text color to white.
- `margin-bottom: 1.375rem;`: Adds margin at the bottom of the title.

##### Call Me Section Paragraph (`call-me .left-side p`)
- `color: #dfe5ec;`: Sets the text color to a light gray.
- `margin-bottom: 1rem;`: Adds margin at the bottom of the paragraph.

##### List Item (`call-me .left-side .list-item`)
- `margin-bottom: 0.375rem;`: Adds margin at the bottom of each list item.
- `display: flex;`: Displays list items as flex elements.
- `align-items: center;`: Aligns items vertically at the center.

##### List Item SVG (`left-side .list-item svg`)
- `color: var(--primary-color);`: Sets the color of the list item SVG to the primary color.
- `font-size: 0.5rem;`: Sets the font size of the SVG.

##### List Item Text (`left-side .list-item span`)
- `color: #dfe5ec;`: Sets the text color to a light gray.

##### Form Side (`form-side`)
- `width: 50%;`: Sets the width of the form side to 50%.

##### Form (`form-side .form-wrapper form`)
- `width: 100%;`: Sets the width of the form to 100%.
- `display: flex;`: Displays the form as a flex container.
- `flex-direction: column;`: Arranges form elements in a column.
- `gap: 1.25rem;`: Adds a gap between form elements.

##### Input Items (`form-side .form-wrapper .input-item`)
- `border: 1px solid #39728f;`: Sets a border for input items.
- `background: #2a5d77;`: Sets the background color of input items.
- `color: var(--white) !important;`: Sets the text color to white.
- `padding: 1rem 1.25rem;`: Adds padding to input items.
- `font-size: 0.875rem;`: Sets the font size of input items.
- `font-weight: 400;`: Sets the font weight of input items.
- `font-family: "Open Sans", sans-serif;`: Specifies the font family.
- `border-radius: 0.25rem;`: Adds border-radius to input items.
- `-webkit-border-radius: 0.25rem;`, `-moz-border-radius: 0.25rem;`, `-ms-border-radius: 0.25rem;`, `-o-border-radius: 0.25rem;`: Browser-specific border-radius properties.
- `outline: none;`: Removes the default input focus outline.

##### Input Placeholder (`form-side .form-wrapper .input-item::placeholder`)
- `color: var(--white);`: Sets the color of input placeholders to white.

##### Term and Condition (`call-me .form-side .form-wrapper .term-condition`)
- `color: #dfe5ec;`: Sets the text color for the term and condition text.
- `a`: Styling for anchor links within the term and condition text.
  - `color: #dfe5ec;`: Sets the color of anchor links.
  - `text-decoration: underline;`: Adds an underline to anchor links.

##### Call Me Button (`form-side .form-wrapper form .btn`)
- `padding: 1rem 1.25rem;`: Sets padding for the button.
- `background: var(--primary-color);`: Sets the background color to the primary color.
- `color: var(--white);`: Sets the text color to white.
- `font-size: 0.75rem;`: Sets the font size.
- `font-weight: 700;`: Sets the font weight to 700.
- `cursor: pointer;`: Changes the cursor to a pointer.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family.
- `border: 0.125rem solid #14bf98;`: Adds a border to the button.
- `border-radius: 0.25rem;`: Adds border-radius to the button.
- `-webkit-border-radius: 0.25rem;`, `-moz-border-radius: 0.25rem;`, `-ms-border-radius: 0.25rem;`, `-o-border-radius: 0.25rem;`: Browser-specific border-radius properties.

##### Call Me Button Hover (`form-side .form-wrapper form .btn:hover`)
- `color: var(--primary-color);`: Changes the text color to the primary color on hover.
- `background: transparent;`: Makes the background transparent on hover.

##### Call Me Section End

### Projects Section

##### Projects Section Container (`section.projects`)
- `padding-top: 6.5rem;` and `padding-bottom: 7rem;`: Sets padding for the top and bottom of the projects section.

##### Section Title and H2 (`projects .section-title, .projects h2`)
- `text-align: center;`: Centers the text inside the section.

##### Filter Tabs (`projects .filter-tabs`)
- `width: fit-content;`: Sets the width of the filter tabs container to fit its content.
- `margin: 0 auto;`: Centers the filter tabs horizontally.
- `margin-top: 2.5rem;`: Adds margin at the top of the filter tabs.
- `display: flex;`: Displays the filter tabs as flex elements.
- `gap: 0.875rem;`: Adds a gap between filter tabs.

##### Filter Tab (`projects .filter-tabs .tab`)
- `text-transform: uppercase;`: Converts the text to uppercase.
- `padding: 0.3125rem 1.375rem;`: Sets padding for the filter tabs.
- `color: #7b7e85;`: Sets the text color to a grayish tone.
- `background: #f1f4f7;`: Sets the background color for the filter tabs.
- `font-weight: 700;`: Sets the font weight to 700.
- `font-size: 0.75rem;`: Sets the font size to 0.75rem.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family.
- `border-radius: 0.25rem;`: Adds border-radius to the filter tabs.
- `-webkit-border-radius: 0.25rem;`, `-moz-border-radius: 0.25rem;`, `-ms-border-radius: 0.25rem;`, `-o-border-radius: 0.25rem;`: Browser-specific border-radius properties.
- `transition: all 0.2s ease;`, `-webkit-transition: all 0.2s ease;`, `-moz-transition: all 0.2s ease;`, `-ms-transition: all 0.2s ease;`, `-o-transition: all 0.2s ease;`: Adds a transition effect on hover.

##### First Filter Tab (`projects .filter-tabs .tab:first-child`)
- `color: var(--white);`: Sets the text color to white.
- `background: var(--primary-color);`: Sets the background color to the primary color.

##### Filter Tab Hover (`projects .filter-tabs .tab:hover`)
- `color: var(--white);`: Sets the text color to white on hover.
- `background: var(--primary-color);`: Sets the background color to the primary color on hover.

##### Projects Wrapper (`projects .projects-wrapper`)
- `margin-top: 1.5rem;`: Adds margin at the top of the projects wrapper.
- `display: grid;`: Displays the projects as a grid.
- `grid-template-columns: repeat(4, 1fr);`: Sets the grid to have four columns.

##### Single Project (`projects .projects-wrapper .single-project`)
- `position: relative;`: Positions the single project relatively.
- `text-align: center;`: Centers the text inside the single project.
- `overflow: hidden;`: Hides overflowing content.
- `z-index: 1;`: Sets the z-index of the single project to 1.
- `cursor: pointer;`: Changes the cursor to a pointer.
- `transition: all 0.3s ease;`, `-webkit-transition: all 0.3s ease;`, `-moz-transition: all 0.3s ease;`, `-ms-transition: all 0.3s ease;`, `-o-transition: all 0.3s ease;`: Adds a transition effect on hover.

##### Single Project Hover (`projects .projects-wrapper .single-project:hover`)
- `img`: Styling for the image within the single project.
  - `transform: scale(1.2);`: Scales the image to 1.2 times its original size on hover.

##### Single Project Before Pseudo-element (`projects .projects-wrapper .single-project::before`)
- `content: "";`: Adds an empty content.
- `position: absolute;`: Positions the before pseudo-element absolutely.
- `top: 0;`, `left: 0;`, `width: 100%;`, `height: 100%;`: Sets the dimensions of the before pseudo-element to cover the entire single project.
- `background: rgba(0, 0, 0, 0.4);`: Sets the background color to a semi-transparent black.
- `opacity: 0;`: Sets the opacity to 0 initially.
- `z-index: 2;`: Sets the z-index of the before pseudo-element to 2.
- `transition: opacity 0.3s ease;`, `-webkit-transition: opacity 0.3s ease;`, `-moz-transition: opacity 0.3s ease;`, `-ms-transition: opacity 0.3s ease;`, `-o-transition: opacity 0.3s ease;`: Adds a transition effect on opacity.

##### Single Project Image (`projects .projects-wrapper .single-project img`)
- `z-index: -1;`: Sets the z-index of the image to -1.
- `transition: all 0.3s ease;`, `-webkit-transition: all 0.3s ease;`, `-moz-transition: all 0.3s ease;`, `-ms-transition: all 0.3s ease;`, `-o-transition: all 0.3s ease;`: Adds a transition effect on hover.

##### Single Project Title (`projects-wrapper .single-project .project-title`)
- `position: absolute;`: Positions the title absolutely.
- `top: 50%;`, `left: 0;`, `width: 100%;`: Centers the title horizontally and stretches it to the full width.
- `font-size: 1.125rem;`: Sets the font size to 1.125rem.
- `font-weight: 700;`: Sets the font weight to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family.
- `color: var(--white);`: Sets the text color to white.
- `z-index: 4;`: Sets the z-index of the title to 4.
- `opacity: 0;`: Sets the opacity to 0 initially.
- `transition: all 0.3s ease;`, `-webkit-transition: all 0.3s ease;`, `-moz-transition: all 0.3s ease;`, `-ms-transition: all 0.3s ease;`, `-o-transition: all 0.3s ease;`: Adds a transition effect on opacity.

##### Single Project Title Hover (`projects .projects-wrapper .single-project:hover .project-title`)
- `opacity: 1;`: Sets the opacity of the title to 1 on hover.

##### Projects Section End

### Consultants Section

##### Consultants Section Container (`div.consultants`)
- `padding-top: 6.375rem;` and `padding-bottom: 3.375rem;`: Sets padding for the top and bottom of the consultants section.
- `background: #fbfbfb;`: Sets the background color for the consultants section.
- `text-align: center;`: Centers the text inside the section.

##### Teams Wrapper (`consultants .teams-wrapper`)
- `width: 100%;`: Sets the width of the teams wrapper to 100%.
- `display: flex;`: Displays the teams as flex elements.
- `justify-content: space-between;`: Distributes the space evenly between team members.
- `margin-top: 3.5rem;`: Adds margin at the top of the teams wrapper.
- `padding: 0 1rem;`: Adds padding to the left and right of the teams wrapper.

##### Team (`consultants .teams-wrapper .team`)
- `width: 12.75rem;`: Sets the width of each team member.
- `.member-image`: Styles for the member image.
  - `width: 100%;`: Sets the width of the member image to 100%.
  - `margin-bottom: 1.5rem;`: Adds margin at the bottom of the member image.
  - `overflow: hidden;`: Hides overflowing content.

##### Team Image (`consultants .teams-wrapper .team img`)
- `transition: all 0.5s ease;`, `-webkit-transition: all 0.5s ease;`, `-moz-transition: all 0.5s ease;`, `-ms-transition: all 0.5s ease;`, `-o-transition: all 0.5s ease;`: Adds a transition effect on hover.
- Hover effect (`consultants .teams-wrapper .team img:hover`):
  - `transform: scale(1.2);`, `-webkit-transform: scale(1.2);`, `-moz-transform: scale(1.2);`, `-ms-transform: scale(1.2);`, `-o-transform: scale(1.2);`: Scales the image to 1.2 times its original size on hover.

##### Team Member Name (`teams-wrapper .team .member-name`)
- `margin-bottom: 0.25rem;`: Adds margin at the bottom of the member name.
- `font-size: 1.125rem;`: Sets the font size to 1.125rem.
- `font-weight: 400;`: Sets the font weight to 400.

##### Team Job Title (`teams-wrapper .team .job-title`)
- `margin-bottom: 0.75rem;`: Adds margin at the bottom of the job title.
- `color: #484a46;`: Sets the text color to a dark gray.
- `font-size: 1rem;`: Sets the font size to 1rem.
- `font-weight: 700;`: Sets the font weight to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family.

##### Social Icons (`teams-wrapper .team .social-icons`)
- `width: fit-content;`: Sets the width of the social icons container to fit its content.
- `margin: 0 auto;`: Centers the social icons horizontally.

##### Consultants Section End

### About Section

##### About Section Container (`section.about`)
- `padding-top: 6.875rem;` and `padding-bottom: 5.25rem;`: Sets padding for the top and bottom of the about section.

##### About Section Container (`div.container`)
- `display: flex;`: Displays the container as a flex container.
- `justify-content: space-between;`: Creates space between the image side and content side.

##### Image Side (`div.image-side`)
- `width: 42%;`: Sets the width of the image side to 42%.

##### Content Side (`div.content-side`)
- `width: 50%;`: Sets the width of the content side to 50%.
- `padding-top:0 .5rem;`: Adds padding at the top of the content side.

##### Section Title (`div.section-title`)
- Styles for the section title.

##### H2 (`div.content-side h2`)
- `margin-bottom: 1.375rem;`: Adds margin at the bottom of the heading.

##### Paragraph (`div.content-side p`)
- `margin-bottom: 1rem;`: Adds margin at the bottom of paragraphs.

##### List (`div.content-side .list`)
- `margin-bottom:1.5rem ;`: Adds margin at the bottom of the list.
- `display: flex;`: Displays the list as flex elements.
- `flex-direction: column;`: Sets the direction of the list items to a column.
- `gap: .5rem;`: Adds spacing between list items.

##### List Item Icons (`div.content-side .list .list-item svg`)
- `color: var(--primary-color);`: Sets the color of list item icons to a primary color.
- `font-size: .5rem;`: Sets the font size of list item icons to .5rem.
- `margin-right: 0.625rem;`: Adds margin to the right of list item icons.

##### Counter (`div.content-side .counter`)
- `display: flex;`: Displays the counter as flex elements.
- `justify-content: space-between;`: Creates space between counter cells.

##### Counter Cell (`div.content-side .counter .cell`)
- `width: 9.5rem;`: Sets the width of counter cells to 9.5rem.
- `display: flex;`: Displays the counter cell as flex elements.
- `align-items: center;`: Aligns content vertically in the center.

##### Counter Number (`div.content-side .counter .cell .number`)
- `color: var(--primary-color);`: Sets the color of the counter number to a primary color.
- `font-size: 2.875rem;`: Sets the font size of the counter number to 2.875rem.
- `font-weight: 700;`: Sets the font weight of the counter number to 700.
- `font-family: "Montserrat", sans-serif;`: Specifies the font family.
- `display: inline-block;`: Displays the counter number as an inline-block.
- `margin-bottom: 0.375rem;`: Adds margin at the bottom of the counter number.

##### Counter Info (`div.content-side .counter .cell .counter-info`)
- `margin-left: 0.5rem;`: Adds margin to the left of the counter info.
- `font-size: .875rem;`: Sets the font size of the counter info to .875rem.
- `display: inline-block;`: Displays the counter info as an inline-block.

##### About Section End

### Contact Section

##### Contact Section (`section.contact`)
- `padding-top: 6.875rem;` and `padding-bottom: 5.625rem;`: Sets padding for the top and bottom of the contact section.
- `background-color: #fbfbfb;`: Sets the background color of the contact section.

##### Contact Section Container (`div.container`)
- `display: flex;`: Displays the container as a flex container.
- `justify-content: space-between;`: Creates space between the left side and form side.

##### Left Side (`div.left-side`)
- `width: 50%;`: Sets the width of the left side to 50%.
- `margin: 1.375rem 1.85rem 0 3rem;`: Sets margin for the left side.

##### Section Title (`div.section-title`)
- Styles for the section title.

##### H2 (`div.left-side h2`)
- `margin-bottom: 1.375rem;`: Adds margin at the bottom of the heading.

##### Paragraph (`div.left-side .para`)
- `margin-bottom: 1rem;`: Adds margin at the bottom of paragraphs.

##### List (`div.left-side .list`)
- `margin-bottom:0.375rem ;`: Adds margin at the bottom of the list.
- `display: flex;`: Displays the list as flex elements.
- `flex-direction: column;`: Sets the direction of the list items to a column.
- `gap: .5rem;`: Adds spacing between list items.

##### List Item Icons (`div.left-side .list .list-item svg`)
- `color: var(--primary-color);`: Sets the color of list item icons to a primary color.
- `font-size: 0.875rem;`: Sets the font size of list item icons to 0.875rem.
- `margin-right: 0.625rem;`: Adds margin to the right of list item icons.

##### List Item Text (`div.left-side .list .list-item .text`)
- `font-size: 1rem;`: Sets the font size of list item text to 1rem.
- `margin-right: 1rem;`: Adds margin to the right of list item text.
- `display: inline-block;`: Displays list item text as an inline-block.
- `text-decoration: underline;`: Underlines list item text.
- `color: #787976;`: Sets the color of list item text.

##### Follow Text (`div.left-side .follow-text`)
- `margin: 2.25rem 0 1rem 0;`: Adds margin around the follow text.

##### Social Icons (`div.left-side .social-icons a`)
- `width: 3.25rem;` and `height: 3.25rem;`: Sets the width and height of social icons.
- `font-size: 1.5rem;`: Sets the font size of social icons.

##### Form Side (`div.form-side`)
- `width: 50%;`: Sets the width of the form side to 50%.

##### Input Items (`div.contact .form-side .form-wrapper .input-item`)
- Styles for input items, including text inputs and the textarea.
- `border: 1px solid #dadada;`: Sets a border around input items.
- `background: var(--white);`: Sets the background color to white.
- `color: #787976 !important;`: Sets the text color.
- `padding: 1rem 1.25rem;`: Adds padding around input items.
- `font-size: 0.875rem;`: Sets the font size.
- `font-weight: 400;`: Sets the font weight.
- `font-family: "Open Sans", sans-serif;`: Specifies the font family.
- `border-radius: 0.25rem;`: Adds border-radius to input items.
- `outline: none;`: Removes the default outline.

##### Input Items Hover (`div.contact .form-side .form-wrapper .input-item:hover`)
- Styles for input items on hover, including a border color change.

##### Textarea (`div.contact .form-side .form-wrapper textarea`)
- Styles for the textarea input item.
- `height: 8rem;`: Sets the height of the textarea.

##### Input Item Placeholder (`div.contact .form-side .form-wrapper .input-item::placeholder`)
- `color: #787976;`: Sets the color of input item placeholders.

##### Term and Conditions (`div.contact .form-side .form-wrapper .term-condition`)
- Styles for the term and conditions text.
- `color: #787976;`: Sets the text color.

##### Term and Conditions Links (`div.contact .form-side .form-wrapper .term-condition a`)
- `color: #787976;`: Sets the link color.
- `text-decoration: underline;`: Underlines the links.

##### Contact Section End

### Footer Section

##### Footer (`footer`)
- `padding-top: 5rem;`: Sets padding for the top of the footer.
- `background-color: #113448;`: Sets the background color of the footer.

##### Footer Content Wrapper (`div.footer-content-wrapper`)
- `width: 100%;`: Sets the width of the footer content wrapper to 100%.
- `display: flex;`: Displays the content wrapper as a flex container.

##### About Aria (`div.about-aria`)
- `width: 50%;`: Sets the width of the "About Aria" section to 50%.

##### H4 (`footer-content-wrapper h4`)
- `color: var(--white);`: Sets the text color of headings to white.
- `margin-bottom: 0.75rem;`: Adds margin at the bottom of headings.

##### Paragraph (`footer-content-wrapper .about-aria p`)
- `color: #dfe5ec;`: Sets the text color of the paragraph.
- Styles for the "Few Words About Aria" paragraph.

##### Footer Navs Wrapper (`div.footer-navs-wrapper`)
- `width: 50%;`: Sets the width of the "Footer Navs Wrapper" to 50%.
- `display: flex;`: Displays the navs wrapper as flex elements.
- `justify-content: space-between;`: Creates space between the navs.

##### Navs (`div.footer-navs-wrapper .navs`)
- Styles for the navigation links.
- `color: #dfe5ec;`: Sets the text color of the navigation links.
- `text-decoration: underline;`: Underlines the navigation links.
- `display: block;`: Displays navigation links as block elements.
- `margin-bottom: .5rem;`: Adds margin at the bottom of navigation links.

##### Copy Rights (`p.copy-rights`)
- `color: #dfe5ec;`: Sets the text color of the copyright text.
- `text-align: center;`: Aligns the copyright text to the center.
- `margin-top: 3rem;`: Adds margin at the top of the copyright text.

##### Footer Section End

