# FreshDeals Breadcrumbs
This project is a multi-page grocery website created while following a [Codecademy](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-improved-styling-with-css/modules/wdcp-22-learn-secondary-navigation-cd0549fb-731f-4d7a-ac10-11a0d8cf854f/projects/ui-breadcrumb-proj) lesson on secondary navigation.

The main focus of the project is implementing breadcrumb navigation with HTML and CSS. The `blueberries.html` page demonstrates both location breadcrumbs and a product-attribute breadcrumb.

## Live Demo
- [Open FreshDeals on GitHub Pages](https://brunorybicki.github.io/FreshDeals-Breadcrumbs/)
- [View the breadcrumb example](https://brunorybicki.github.io/FreshDeals-Breadcrumbs/blueberries.html)

## Features
- **Multi-page Website:** Includes the FreshDeals home page and several supporting pages.
- **Breadcrumb Navigation:** Displays the user's current location in the store hierarchy, from Shop to Groceries and Blueberries.
- **Attribute Breadcrumb:** Displays an additional product attribute separately from the main navigation path.
- **CSS Separators:** Uses CSS pseudo-elements to create separators between breadcrumb items.
- **Custom Styling:** Different breadcrumb types receive distinct visual styles.
- **HTML & CSS Only:** The project does not require JavaScript.

## Project Structure
```text
FreshDeals-Breadcrumbs/
├── index.html
├── about.html
├── bestsellers.html
├── blueberries.html
├── deals.html
├── jobs.html
├── sell.html
└── resources/
    └── css/
        ├── about.css
        ├── base.css
        ├── breadcrumb.css
        ├── index.css
        ├── jobs.css
        ├── reset.css
        ├── sell.css
        └── styled-breadcrumb.css
```

The breadcrumb-specific styling is contained in `resources/css/breadcrumb.css`.

## Usage
To run the project locally:
1. Download or clone the repository.
2. Open `index.html` in a web browser.
3. Navigate to **Organic Blueberries** to view the breadcrumb example.

Some image assets are loaded from Codecademy's content server, as in the original exercise.

## Acknowledgment
This project was built while following a Codecademy lesson on secondary navigation. The original exercise can be found [here](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-improved-styling-with-css/modules/wdcp-22-learn-secondary-navigation-cd0549fb-731f-4d7a-ac10-11a0d8cf854f/projects/ui-breadcrumb-proj).
