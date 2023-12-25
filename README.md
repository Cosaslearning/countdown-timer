# countdown-timer

![Screenshot_1](https://github.com/Cosaslearning/countdown-timer/assets/100014446/d9129276-5fb4-4a6d-83d5-0e666ef0c7d2)

This web project features a countdown timer to the year 2024, providing a visual representation of the time remaining until the specified date. The project utilizes HTML, CSS, and JavaScript to create a visually appealing and dynamic user interface. Additionally, it includes confetti effects for a festive touch when the countdown reaches zero.

**HTML File (index.html):**

- The HTML file sets up the basic structure of the webpage using standard HTML5 markup.
- It includes metadata in the head section, such as character set, viewport settings, and the title of the webpage.
- External resources, like the CSS file and the confetti JavaScript library, are linked using `<link>` and `<script>` tags.
- Within the body, there is a container division (`<div class="container">`) containing headings and countdown details.
- Headings include the year (h1), a subtitle (h3), and a tagline (h4).
- Countdown details are organized within a `<div class="countdown">` container, where each detail (days, hours, minutes, seconds, and "LEFT") has its own division.

**CSS File (style.css):**

- Google Fonts are imported to use the "PT Serif" font throughout the webpage.
- CSS variables are declared in the `:root` selector to define colors used in the styling.
- General styling rules include setting a background image and positioning the container in the center of the viewport.
- The headings section is styled using the `.headings` class, with specific styles for h1, h3, and h4.
- The countdown section is styled with flexbox, setting the width, gap, and height of individual countdown details.
- Each detail is styled using the `.detail` class, with specific styles for the number and subheading.
- The `span.number` class is used to style the countdown numbers with a glass-like effect, a shadow, and a border radius.
- Additional styles are applied to enhance the overall visual appeal of the webpage.

**JavaScript File (script.js):**

- The JavaScript file includes functions for various confetti effects (fireworks, school pride, realistic look, stars, and snow).
- The countdown function calculates and displays the time remaining until the specified end date. When the countdown reaches zero, it triggers confetti effects and displays celebratory messages.
- The script utilizes `setInterval` to update the countdown every second and initially calls the countdown function.

This project creates an engaging New Year countdown timer with confetti effects for a festive touch. The combination of HTML, CSS, and JavaScript results in an interactive and visually appealing user experience. Users can witness a celebration on the arrival of the new year, complete with dynamic countdown updates and animated confetti effects.
