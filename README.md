# FreshDeals: Blueberries
This project is a grocery product page focused on implementing breadcrumb navigation using HTML and CSS while following a lesson provided by [Codecademy](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-improved-styling-with-css/modules/wdcp-22-learn-secondary-navigation-cd0549fb-731f-4d7a-ac10-11a0d8cf854f/projects/ui-breadcrumb-proj). It demonstrates how breadcrumbs can improve secondary navigation by showing both location and product attribute information.

## Live Demo
View the project on [GitHub Pages](https://brunorybicki.github.io/FreshDeals-Breadcrumbs/).

## Features
- **Breadcrumb Navigation:** Displays the user's current location within the store hierarchy.
- **Location Breadcrumbs:** Shows the navigation path from Shop to Groceries and Blueberries.
- **Attribute Breadcrumb:** Displays an additional product attribute separately from the main navigation path.
- **CSS Separators:** Uses CSS pseudo-elements to create separators between breadcrumb items.
- **Inline Layout:** Breadcrumb items are displayed horizontally for clear navigation.
- **Custom Styling:** Different breadcrumb types receive distinct visual styles.
- **HTML & CSS Only:** The page and breadcrumb navigation are created without JavaScript.

## File Structure
- `index.html`: Contains the page structure, product information, breadcrumb navigation, and footer.
- `breadcrumbs.css`: Defines the breadcrumb layout, separators, and attribute styling.

## Usage
To run the project locally:
1. Download or clone the repository.
2. Open the `index.html` file in a web browser.
3. The FreshDeals product page will load with the breadcrumb navigation displayed above the product banner.

## How It Works
The breadcrumb navigation is created using an unordered list. Each breadcrumb item represents either a location in the site's hierarchy or an attribute of the selected product. CSS is used to display the breadcrumb items inline, and pseudo-elements are used to automatically insert separators between location breadcrumbs. Attribute breadcrumbs are styled differently so they can be visually distinguished from navigation links.

## Customization
You can customize the project by:
- Changing the breadcrumb items in `index.html`.
- Modifying the breadcrumb separator in `breadcrumbs.css`.
- Adjusting breadcrumb colors and typography.
- Changing the styling of attribute breadcrumbs.
- Replacing the product information and images.
- Adding hover states or transitions to breadcrumb links.
- Expanding the page with additional product categories.

## Acknowledgment
This project was built while following a Codecademy lesson on secondary navigation. The original project can be found [here](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-improved-styling-with-css/modules/wdcp-22-learn-secondary-navigation-cd0549fb-731f-4d7a-ac10-11a0d8cf854f/projects/ui-breadcrumb-proj).
