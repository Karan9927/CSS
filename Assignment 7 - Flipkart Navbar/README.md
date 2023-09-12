## Hosted Link
[Link for Flipkart Navbar](https://karan9927.github.io/CSS/Assignment%207%20-%20Flipkart%20Navbar/)
## Navbar Container (`<div class="navbar">`)
![image](https://github.com/Karan9927/CSS/assets/115612744/a30c85ff-6e70-4cef-a1af-47b9e6eb2517)

- Contains the entire navbar.

## Main Content (`<div class="main">`)
![image](https://github.com/Karan9927/CSS/assets/115612744/98289267-05ed-4caa-9624-556a333d0a7c)
![image](https://github.com/Karan9927/CSS/assets/115612744/b23d2dd6-7485-403f-b691-518dad13a338)

- Contains the main content of the navbar, including the Flipkart logo, search bar, buttons, and product cards.

### Flipkart Logo (`<div class="flipkart">`)
![image](https://github.com/Karan9927/CSS/assets/115612744/33ae1f2f-c4e8-4279-b83b-8948ffbfc877)
![image](https://github.com/Karan9927/CSS/assets/115612744/f6e8c084-a123-4f62-baa9-35c1b21cc406)
- Displays the Flipkart logo and associated text.
  - `<img src="svg-edited.png" alt="Flipkart" title="Flipkart" />`: Flipkart logo image.
  - Text content with spans and an image.

### Search Bar (`<div class="searchbar">`)
![image](https://github.com/Karan9927/CSS/assets/115612744/f0753562-e273-48b9-947a-04d212ec1577)
![image](https://github.com/Karan9927/CSS/assets/115612744/a7cd881a-7381-4ba8-b91e-ed769d68c2ad)
- Contains the search input field and search icon.
  - `<input type="text" value="Search for products, brands and more" />`: Search input field.
  - `<div class="search">`: Search icon.
    - `<svg>...</svg>`: SVG search icon.

### Buttons and Text
![image](https://github.com/Karan9927/CSS/assets/115612744/8f4e7700-b4da-4326-a13f-b477b56ccc5c)
![image](https://github.com/Karan9927/CSS/assets/115612744/c3d0175a-446d-44e6-ba8e-c0cc2dc43817)
![image](https://github.com/Karan9927/CSS/assets/115612744/2035951c-5485-4671-97d5-6c3daf203184)

- Login button: `<button>Login</button>`
- "Become a Seller" text: `<p id="seller">Become a Seller</p>`
- Dropdown select: `<div class="dropd">`
  - `<select value="More" id="More">`: Select input.
    - `<option name="" id="">More</option>`: Select option.
- Cart icon and text: `<div class="cart">`
  - `<img width="24" height="24" src="cart.svg" alt="shopping-cart" />`: Cart icon.
  - `<p>Cart</p>`: Text.

### Product Cards (`<div class="products">`)
![image](https://github.com/Karan9927/CSS/assets/115612744/bc7bbe29-b27e-4383-bc1c-4de7c0f22bb4)
![image](https://github.com/Karan9927/CSS/assets/115612744/c45bc56b-9b2c-4e61-b342-d5e340dd70ec)

- Contains a series of product cards.
  - Each product card (`.card`) includes an image, text, and an arrow icon.

  #### Product Card Example
![image](https://github.com/Karan9927/CSS/assets/115612744/2d4cf8d3-8f25-4a7f-8ce1-3fc0eedab633)
![image](https://github.com/Karan9927/CSS/assets/115612744/f352a222-9590-4bd7-afb4-d3d2a812308f)
![image](https://github.com/Karan9927/CSS/assets/115612744/4756a106-4e02-4dfe-b972-c8634c9102a3)
![image](https://github.com/Karan9927/CSS/assets/115612744/1a13be33-d693-448e-9e7d-12b72362a5ff)
![image](https://github.com/Karan9927/CSS/assets/115612744/39c131c9-9057-4c7e-ae83-5c53a83042e3)

  - Product image: `<img src="..." />`
  - Product text: `<p>...</p>`
  - Arrow icon with text: `<div class="arrow">`
    - Text: `<p>...</p>`
    - Arrow icon: `<svg>...</svg>`
