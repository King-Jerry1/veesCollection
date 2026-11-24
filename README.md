# Vee's Collection

**Vee's Collection** is a fashion accessories e-commerce website concept focused on jewelry, wristwatches, glasses, and other stylish accessories. The project is designed with a clean, elegant, and premium black-and-gold visual identity.

## Project Overview

The website provides visitors with a simple way to:

- Browse featured fashion accessories.
- Explore products by category.
- View product details and prices.
- Add products to a shopping cart.
- Update item quantities or remove items.
- Review the cart total.
- Make an order enquiry through WhatsApp.

## Product Categories

- Jewelry
- Wristwatches
- Glasses
- Fashion accessories

## Technology Stack

This project uses:

- **HTML5** – website structure
- **CSS3** – styling and responsive layout
- **JavaScript** – product display and shopping-cart interactions
- **LocalStorage** – saving cart contents in the browser
- **Font Awesome** – icons (if included)
- **Google Fonts** – typography (if included)

No frontend framework is required.

## Project Structure

```text
vees-collection/
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
    ├── logo.png
    ├── banner.png
    └── product images...
```

Your actual filenames may differ. Update the image paths in the HTML and CSS to match the files in your `images` folder.

## Getting Started

### 1. Install Visual Studio Code

Download and install Visual Studio Code from:

https://code.visualstudio.com/

### 2. Open the project

1. Create a folder named `vees-collection`.
2. Open Visual Studio Code.
3. Select **File → Open Folder**.
4. Choose the `vees-collection` folder.

### 3. Create the project files

Create these files in the project folder:

- `index.html`
- `style.css`
- `script.js`
- `README.md`

Create an `images` folder for the logo, banner, and product photographs.

### 4. Link the CSS and JavaScript

In `index.html`, make sure the stylesheet is linked inside the `<head>`:

```html
<link rel="stylesheet" href="style.css">
```

Load the JavaScript before the closing `</body>` tag:

```html
<script src="script.js"></script>
```

### 5. Run the website

You can open `index.html` directly in a browser. For a more convenient development workflow, install the **Live Server** extension in VS Code, then right-click `index.html` and select **Open with Live Server**.

## Customisation

Before publishing the website:

1. Add your real product names, descriptions, prices, and photographs.
2. Replace placeholder contact details with the correct business contact information.
3. Add your business logo and banner to the `images` folder.
4. Check that every image path matches its actual filename.
5. Update delivery, return, and customer-service information to reflect your business policies.
6. Test the layout on mobile phones, tablets, and desktop screens.

## WhatsApp Order Enquiries

If the website uses WhatsApp checkout, replace the placeholder phone number in `script.js` with the business WhatsApp number.

Use the international format with the country code, without a plus sign, spaces, or dashes. For example, a Nigerian number should begin with `234`.

**Important:** A WhatsApp checkout link sends an order enquiry to WhatsApp. It does not process online payments or automatically confirm an order.

## Current Scope and Limitations

The initial version is a frontend website. Product and cart information may be stored in the visitor's browser using LocalStorage.

Unless separately implemented, this version does not include:

- A server or online database
- Customer accounts and login
- An administrator dashboard
- Automatic stock management
- Online payment processing
- Automatic order fulfilment or tracking

These features can be added in a later development phase using a backend, database, and payment provider.

## Testing Checklist

- [ ] Website opens without errors.
- [ ] Navigation links work.
- [ ] Product images load correctly.
- [ ] Category filters show the correct products.
- [ ] Products can be added to the cart.
- [ ] Cart quantities can be changed.
- [ ] Items can be removed from the cart.
- [ ] Cart totals calculate correctly.
- [ ] Cart contents remain after refreshing the page.
- [ ] WhatsApp checkout opens the correct business number.
- [ ] Website displays properly on mobile and desktop.

## Deployment

When the website is ready, it can be published using a static hosting service such as:

- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

A custom domain can also be connected after deployment.

## Future Improvements

Possible future upgrades include:

- Product search and sorting
- Individual product pages
- Customer registration and login
- Admin dashboard for managing products
- Database-backed inventory
- Secure online payments
- Order history and tracking
- Customer reviews and ratings

## Brand Identity

**Brand name:** Vee's Collection  
**Tagline:** Elegance in Every Detail.  
**Main colours:** Black, gold, cream, and white  
**Product focus:** Jewelry, wristwatches, glasses, and fashion accessories

---

© Vee's Collection. All rights reserved.
"# veesCollection" 
