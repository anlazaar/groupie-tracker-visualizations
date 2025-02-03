# Groupie Tracker Visualizations

## Overview

The Groupie Tracker Visualizations project is designed to manipulate and display data from an API in an aesthetically pleasing and interactive way. The goal is to provide an intuitive and visually engaging experience for users by adhering to Schneiderman's 8 Golden Rules of Interface Design. This project focuses on human-computer interaction, CSS styling, and clean HTML and CSS linking.

## Features

- **Responsive Design**: The layout adjusts for different screen sizes using media queries.
- **Interactive Elements**: Includes features like filters, range sliders, and navigation buttons.
- **Card-Based Layout**: Information is displayed in a grid of cards, which adjust their layout based on screen size.
- **Error Handling**: Provides user-friendly error pages with clear feedback.
- **Map Integration**: A section dedicated to displaying maps with embedded data.

## Design Principles

The design of this project follows the principles of good web design with a focus on:

1. **Consistency**: The design elements (buttons, cards, typography) maintain a consistent visual language.
2. **Informative Feedback**: Users receive clear feedback upon actions, such as button hovers or form interactions.
3. **Error Handling**: In case of errors, an informative error card is shown to guide the user.
4. **Responsive Layout**: The layout adjusts to different screen sizes, ensuring a pleasant experience on both mobile and desktop devices.
5. **Visual Hierarchy**: The use of color, font sizes, and spacing ensures important elements are easily noticeable.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/groupie-tracker-visualizations.git
   cd groupie-tracker-visualizations
   ```

2. Open the `index.html` file in your preferred browser.

## Usage

Once the project is open in your browser:

- The **cards** section will display the data, each with an image and associated details.
- Use the **filter** options to refine the displayed data based on various criteria.
- Navigation buttons appear fixed at the bottom-right for easy access to previous/next sections.
- The **map** section will show geographical data with a map interface.
- The **error page** will be displayed in case of an issue, providing clear guidance to the user.

## CSS Styling

The CSS aims to provide a dark theme with contrasting golden accents. Key CSS features include:

- **Card Layout**: Each card is styled with a shadow effect, padding, and a hover animation.
- **Buttons**: Styled with a transition effect for smooth interaction feedback.
- **Filters**: A section for filtering data based on user input, with smooth transitions.
- **Navigation**: Fixed-position buttons for easy navigation.

### Example of Styles:
```css
/* Card styling */
.card {
  background-color: #333;
  border-radius: 10px;
  padding: 2rem;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.8);
}

/* Button Styling */
button {
  padding: 0.6rem 1rem;
  font-size: 1rem;
  background: #333;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s, transform 0.3s;
}

button:hover {
  background: goldenrod;
  transform: translateY(-2px);
}
```

## Guidelines for Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Commit your changes and push them to your branch.
4. Open a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Schneiderman’s 8 Golden Rules of Interface Design for guiding the UX.
- The creative use of CSS for interactive and responsive design elements.

---
