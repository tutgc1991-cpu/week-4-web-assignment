# SpendWise Dashboard Shell

## Project Overview

SpendWise Dashboard Shell is a responsive personal finance dashboard created using HTML and CSS.

The purpose of this project is to build the visual foundation of a future budgeting application. The dashboard contains a navigation sidebar, header, financial summary information, and six spending category cards.

This project focuses on modern CSS layout techniques, especially **CSS Grid and Flexbox**, responsive design, CSS custom properties, and small user-interface micro-interactions.

## Files in the Project

### `index.html`

The `index.html` file contains the structure and static content of the SpendWise dashboard.

It includes:

* Sidebar/navigation menu
* Dashboard header
* User information
* Total budget summary
* Total spending summary
* Remaining budget summary
* Six financial category cards:

  * Food
  * Transport
  * Rent
  * Entertainment
  * Savings
  * Utilities
* Progress bars showing spending levels

The HTML uses semantic elements such as `aside`, `nav`, `main`, `header`, `section`, and `article`.

### `style.css`

The `style.css` file controls the visual design and layout of the dashboard.

It uses **CSS Grid** for the main dashboard structure and category-card layout.

It uses **Flexbox** for:

* Sidebar navigation
* Header layout
* User information
* Summary boxes
* Category card content
* Card headings and status information

The stylesheet also uses CSS custom properties defined in `:root` for the application's theme.

Important variables include:

* `--brand-color`
* `--accent-color`
* `--surface-color`
* `--background-color`
* `--primary-text`
* `--secondary-text`

## Responsive Design

The dashboard includes a responsive media query for screens smaller than 768px.

On smaller screens:

* The sidebar and main content use a single-column layout.
* Navigation items become flexible and can wrap.
* The header changes to a vertical layout.
* Summary boxes stack vertically.
* Category cards change to a single-column layout.

The responsive layout can be tested using the browser's **DevTools Device Toolbar**.

## Card Micro-interactions

The dashboard cards include subtle hover and keyboard-focus effects.

When a user hovers over or focuses on a card:

* The card moves slightly upward using `transform`.
* The card receives a stronger `box-shadow`.
* Keyboard users receive a visible focus outline.

The transition lasts **200 milliseconds**, which is below the required 250 milliseconds.

## Dark Theme

As a stretch goal, the project includes:

```css
@media (prefers-color-scheme: dark)
```

The dark theme changes the CSS custom properties for the background, surfaces, text, borders, sidebar, and other interface elements.

This allows the dashboard to automatically adapt when the user's operating system is configured to use dark mode.

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Custom Properties
* CSS Media Queries
* CSS Transitions

## How to Run the Project

1. Clone or download the GitHub repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use the browser's DevTools Device Toolbar to test the responsive layout.
5. Resize the browser window to confirm that the dashboard changes to a single-column layout below 768px.

## Project Structure

```text
SpendWise/
│
├── index.html
├── style.css
└── README.md
```

## Conclusion

The SpendWise Dashboard Shell provides a clean and responsive foundation for a future personal finance capstone project. It demonstrates how CSS Grid and Flexbox can be combined to create a modern dashboard layout while CSS variables make the theme easier to maintain and update.
