# MediHome

A responsive, multi-page medicine and wellness shopping demo for a college project. It uses plain HTML, CSS and JavaScript and can be published with GitHub Pages without a build step.

## Preview locally

Open `index.html` directly in a browser, or use VS Code Live Server for a local web preview. Pages link to one another using ordinary `.html` files.

## Demo features

- Home page with responsive navigation, category dropdowns, a three-slide auto-advancing hero carousel, promotional banners and compact product cards.
- Separate pages for Kids Care, Personal Care, Women’s Care, Health & Nutrition, Health Devices, Ayurveda, About, Contact, Profile, Login/Signup, Cart and Wishlist.
- Search products, browse categories, sort category products, save wishlist items, update cart quantities and navigate the hero carousel with arrows, dots or a mobile swipe.
- Demo login/profile, contact/newsletter forms and checkout confirmation.
- Cart, wishlist, profile and sample order data are stored in the browser's local storage only.
- Some product cards use selected branded pack photos; remaining demo cards use illustrative stock photography. Product names, prices and offers are still for demonstration only.

## GitHub Pages behavior

- This is a static site: it needs no PHP, MySQL, XAMPP, Node build, or environment variables to publish.
- Internal pages and assets use relative paths, so they work under a project URL such as `https://USERNAME.github.io/REPOSITORY/`.
- Search, navigation, carousel, cart, wishlist, profile, demo login, and sample order history run in the visitor's browser. Cart/profile/order data stays in that browser's local storage and does not sync to other devices.
- Login, contact, newsletter, checkout, and tracking are demo interactions only. There is no real account service, message delivery, payment, or shipment.
- Product photos and Google Fonts are loaded from external HTTPS services, so those visuals need an internet connection.

## Publish with GitHub Pages

1. Create a GitHub repository and push these project files to its default branch (`main`, or whichever branch you choose).
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you pushed and `/ (root)`, then save.
5. Wait for GitHub Pages to publish and open the site URL shown in the Pages settings.

## Demo and safety note

This is a front-end student demo. Products and prices are illustrative. Login/signup, contact, newsletter and checkout actions do not use a backend or transmit data. The demo does not sell real medicines, process payments or provide medical advice. Do not use its local demo login as a real account system.
