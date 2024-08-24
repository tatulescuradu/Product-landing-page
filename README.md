# FCC Product Landing Page

This project is a product landing page created as part of the freeCodeCamp curriculum. The page showcases a collection of classic books, featuring details about the products, an email signup form, and an embedded video.

## Project Structure

### HTML

The `index.html` file contains the basic structure of the page. It is divided into several sections:
- **Header**: Contains the navigation bar and the logo.
- **Email Section**: A form for users to enter their email addresses.
- **Features Section**: Highlights the key features of the product offering.
- **Audio Section**: Embeds a YouTube video relevant to the products.
- **For Sale Section**: Displays books available for sale with details such as author, price, and an "Add to Cart" button.

### CSS

The `styles.css` file is responsible for styling the page, ensuring a clean and modern look.

#### CSS Variables

The project uses CSS variables to manage color schemes:
- `--white`: Primary background color.
- `--text`: Color for the general text.
- `--pale`: Background color for the body.
- `--green`: Accent color for buttons and icons.
- `--header-text`: Color for header text.

#### Layout and Styling

- **Header**: The header is styled to be fixed at the top, with a logo and navigation links centered.
- **Features**: Each feature is presented with an icon and a description, using flexbox for alignment.
- **For Sale Section**: Each book is presented in a card layout, with a cover image, author, title, and price.

### Media Queries

The project includes several media queries to ensure responsiveness:
- **Screens over 1000px**: Adjusts the width of the embedded video and aligns the product cards side by side.
- **Screens between 450px and 600px**: Adjusts the layout of the cards for better readability on smaller screens.
- **Screens under 600px**: Adjusts the header layout from row to column for better mobile experience.

## How to Run the Project

1. Clone or download this project.
2. Open the `index.html` file in a web browser.

## Contributions

Contributions are welcome! Feel free to fork this project and submit a pull request with any enhancements or suggestions.

---

This project is part of the freeCodeCamp curriculum, designed to help learners practice HTML and CSS by building a product landing page.
