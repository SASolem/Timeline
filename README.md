# Project Overview
![Project Logo](/TimelineCover.jpg)

![Visit My Project on Netlify](https://nenorvalls-timeline.netlify.app/)


# CSS Styling for a Timeline Webpage

This README explains the CSS code used to style a timeline webpage. The HTML structure and elements are styled to create an aesthetically pleasing and responsive design.

## File Structure

- `index.html`: The HTML document for the timeline webpage.
- `index.css`: The CSS file containing the styles discussed in this README.

## CSS Explanation

### `body`

The `body` rule styles the entire page. It sets the font family to Arial and sans-serif, removes default margins and padding, ensures the page fills the entire viewport height, and applies the "rainbow" animation for background color.

### `@keyframes rainbow`

This animation gradually changes the background color in a rainbow pattern at different percentages of the animation duration, creating a visually appealing effect.

### `.timeline`

Styles the main timeline container. It sets the background with a purple-to-orange gradient, defines the maximum width, margin, padding, border radius, box shadow, and border. It also limits the maximum height.

### `.timeline-header`

Styles the header of the timeline, arranging its content using flexbox with space-between alignment. It adds a bottom border for separation.

### `.timeline-info`

Styles the container for timeline information. It has a partially transparent background, padding, border radius, text alignment, width, maximum width, and is centered. It also adds a border.

### `.time-line-container`

Styles the container for time-related information, adjusting margins.

### `.time-line-container h1`

Styles the `<h1>` element inside the time container, changing the font size and margin.

### `.time-line-container .span`

Styles a `<span>` element inside the time container, setting font size and margins.

### `.timeline-info span`

Styles the `<span>` elements within the timeline info container, setting the font size.

### `.timestamp`, `.timestamp span`

Styles the timestamp elements, applying padding, border radius, text alignment, and removing the border.

### `.update-container`

Styles the container for updates, using flexbox for a vertical layout.

### `.update`

Styles individual update elements, setting width, maximum width, padding, border radius, margins, text alignment, border, and a background color with a box shadow.

### `button#showAllButton`

Styles the "Show All Updates" button. It specifies the background color, text color, border properties, padding, border radius, cursor style, and positioning.

## Responsiveness

The CSS code includes a media query for screens with a maximum width of 600 pixels. This media query adjusts various properties, including font sizes, padding, margins, and dimensions, to ensure a more responsive design for smaller screens.
