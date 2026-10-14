# FryingNemo — Restaurant Website Prototype

A static website prototype for a fish-and-chips restaurant, adapted from the Stellar template by HTML5 UP. The project presents restaurant information across a home page, menu, about page, location page, and contact form interface.

## Project scope

- Home page with section navigation and links to the supporting pages.
- Menu page displaying food and drink imagery.
- About page presenting a restaurant story.
- Location page with a map image and store imagery.
- Contact page with name, email, and message fields.
- Opening-hours information repeated across the pages.

This is a front-end prototype. No ordering system, payment integration, database, or working message-delivery service is included in the inspected files.

## Technologies

HTML, CSS, JavaScript, jQuery, and the Stellar template's scrolling and responsive utilities. The home page also references Google Fonts.

## Main files

| File | Purpose |
| --- | --- |
| `index.html` | Home page and section navigation. |
| `menu.html` | Menu imagery and a search input. |
| `About us.html` | Restaurant story. |
| `map.html` | Location and map imagery. |
| `contact.html` | Contact form interface. |
| `main.css`, `noscript.css` | Stylesheets supplied in the repository root. |
| `main.js`, `util.js`, and supporting JavaScript | Template behaviour and utilities. |
| `README.txt`, `LICENSE.txt` | Original template credits and licence information. |

## Current implementation status

The repository needs asset-path repairs before it can be presented as a working demo. The HTML references `assets/css/`, `assets/js/`, and `images/`, while the inspected repository lists the corresponding files in its root. Some referenced template imagery is also absent.

The menu links target `nonexistent.html`, which is not present. Its search input calls `myFunction()`, but the menu page does not define that function; search behaviour remains unverified. The contact form posts to `#` and has no configured delivery endpoint. Social links are placeholders.

## Preview and next steps

After correcting asset paths and missing references, preview `index.html` using a local static web server. Check each page, navigation link, image, and browser console before deployment. A build process or package installation is not defined in this repository.

The source review does not establish that the layout works across devices; browser verification is still required.

## Attribution

This project adapts **Stellar by HTML5 UP**, credited to **AJ / @ajlkn** in the source and original README. Retain the original `README.txt`, `LICENSE.txt`, and template notices. The bundled licence is Creative Commons Attribution 3.0 Unported.

The original template README also credits Font Awesome, jQuery, Scrollex, and Responsive Tools. This documentation does not claim that the template or bundled libraries were authored from scratch, or establish ownership of every restaurant image.
