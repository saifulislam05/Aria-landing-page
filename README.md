# Aria (Major project) ass CSS

## HTML Structure

### Navigation Bar:
![Navigation Bar](link-to-screenshot-image)

- `<nav>`: The navigation bar containing the website logo and navigation links.
  - `.nav-left-side`: Logo container with a clickable logo image.
  - `.nav-right-side`: Container for navigation links and social icons.
    - `<ul class="nav-items">`: Unordered list for navigation links.
      - `<li class="active"><a href="#">Home</a></li>`: Active navigation link.
      - `<li><a href="#intro">INTRO</a></li>`: Navigation link.
      - `<li><a href="#services">SERVICES</a></li>`: Navigation link.
      - `<li><a href="#call-me">CALL ME</a></li>`: Navigation link.
      - `<li><a href="#projects">PROJECTS</a></li>`: Navigation link.
      - `<li><a href="#about">ABOUT <i class="fa-solid fa-caret-down"></i></a></li>`: Navigation link with a dropdown icon.
      - `<li><a href="#contact">CONTACT</a></li>`: Navigation link.
    - `.social-icons`: Container for social media icons.
      - `<a href=""><i class="fa-brands fa-facebook-f"></i></a>`: Facebook icon.
      - `<a href=""><i class="fa-brands fa-twitter"></i></a>`: Twitter icon.
## CSS Styles
### `:root` Variables
- `--primary-color: #14bf98;`: Defines a primary color variable.
- `--secondary-color: #dfe5ec;`: Defines a secondary color variable.
- `--white: #ffffff;`: Defines a white color variable.
- `--black: #000000;`: Defines a black color variable.

### Common styles-----
#### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.
- `font-family: 'Open Sans', sans-serif;`: Specifies the default font for the entire document.


#### HTML (`html`)
- `scroll-behavior: smooth;`: Adds smooth scrolling behavior to anchor links within the HTML document.

#### Container (`div.container`)
- `.container`:
  - `width: 100%;`: Makes the container span the entire width.
  - `max-width: 1140px;`: Sets the maximum width of the container to 1140 pixels.
  - `margin: 0 auto;`: Centers the container horizontally on the page.

#### Headings (`h2`, `h3`, `h4`)
- `font-weight: 700;`: Sets a bold font weight for headings.
- `font-family: 'Montserrat', sans-serif;`: Specifies the font family for headings.

#### Paragraphs (`p`)
- `color: #787976;`: Sets the text color for paragraphs.
- `font-size: 1rem;`: Sets the font size for paragraphs.
- `font-weight: 400;`: Sets the font weight for paragraphs.

#### Links (`a`)
- `text-decoration: none;`: Removes underlines from links.
- `color: var(--white);`: Sets the default text color for links.
- `color: var(--primary-color);` (on hover): Changes the text color of links when hovered.

#### Images (`img`)
- `width: 100%;`: Sets the width of images to 100%.
- `height: 100%;`: Sets the height of images to 100%.

### Nav
#### Navigation Bar (`nav`)
- `display: flex;`: Arranges items in a row.
- `justify-content: space-between;`: Separates items with space.
- `align-items: center;`: Vertically centers items.
- `position: fixed;`: Fixes the navigation bar at the top of the page.
- `width: 100vw;`: Sets the width of the navigation bar to 100% of the viewport.
- `padding: 0.5rem 5rem;`: Adds padding to the navigation bar.
- `background: #113448;`: Sets the background color of the navigation bar.

#### Navigation Items (`ul.nav-items`)
- `display: flex;`: Arranges navigation items in a row.
- `list-style: none;`: Removes list bullets from navigation items.

#### Navigation Links (`li a`)
- `font-size: 0.875rem;`: Sets the font size for navigation links.
- `color: var(--white);`: Sets the text color for navigation links.
- `text-transform: uppercase;`: Converts text to uppercase.
- `font-weight: 600;`: Sets the font weight for navigation links.
- `padding: 0.25rem 0.75rem;`: Adds padding to navigation links.
- `transition: 0.2s ease;`: Adds a smooth transition effect on hover.

#### Active Navigation Link (`li.active a`)
- `color: var(--primary-color);`: Sets the text color for the active navigation link.

#### Social Icons (`.social-icons a`)
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

#### Hovered Social Icons (`.social-icons a:hover`)
- `background: url('/assets/images/hexagon-white.svg') no-repeat;`: Changes the background image on hover.
- `color: var(--primary-color);`: Changes the text color on hover.