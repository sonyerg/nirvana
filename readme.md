### HTML Tags I used:

- **link**    Loads external resources like Bootstrap CSS and your `styles.css` file.
- **script**  Embeds JavaScript to handle Kurt Mode toggling and navigation logic.
- **div**     Used as layout containers (for image wrappers, content sections, Bootstrap grid, etc.).
- **img**     Displays Nirvana-related images across the homepage and member pages.
- **a**       Links to external sites (like Wikipedia) and internal pages (`kurt.html`, etc.).
- **button**  Interactive UI controls (like the **Kurt Mode** toggle and **Home** button).
- **p**       Contains the body text about Nirvana and the band members.
- **b**       Emphasizes important names like “Kurt Cobain” and “Krist Novoselic.”
- **i**       Highlights album/song titles like *Bleach* and *Nevermind*.
- **iframe**  Embeds the YouTube video for an interview of the band on the homepage.

### CSS properties I used:

- **background-color** Sets the background color for default and Kurt Mode themes.
- **font-family**      Defines the typeface for text across different modes.
- **color**            Specifies text color (e.g., white for dark mode, red for links).
- **object-fit**       Controls how images scale (e.g., cover or fill without distortion).
- **width/height**     Defines dimensions of images to fit layout and responsiveness.

### Technology Stack

**JavaScript** is used to implement a "Kurt Mode" theme toggle, which changes the site’s appearance to a dark,
grunge-inspired theme and saves the user's preference across page visits using localStorage. And also to
program the home button to navigate to the homepage.

**Bootstrap** is used to make the layout responsive with grid classes like container, row, col-md-4,
and to style buttons and images consistently across different screen sizes using utility classes like btn, img-fluid, and text-center.
