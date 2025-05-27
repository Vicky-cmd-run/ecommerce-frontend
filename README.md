project:
  name: ShopEase
  description: >
    A beautiful and modern e-commerce website built with HTML, CSS (Bootstrap), and JavaScript.
    Includes login, registration, product listing, and cart system with persistent localStorage.

  technologies:
    - HTML5
    - CSS3
    - Bootstrap 5
    - JavaScript (ES6)
    - LocalStorage (Browser)

  features:
    - Responsive homepage with hero section
    - Dynamic product listing with "Add to Cart"
    - Persistent cart system (localStorage)
    - Login and registration forms (Bootstrap styled)
    - Smooth navigation and modern UI

  pages:
    - index.html: Home page with hero section and intro
    - products.html: Product listings with Add to Cart
    - cart.html: Displays all added products
    - login.html: User login form
    - register.html: User registration form

  folders:
    css:
      - style.css: Custom styles and UI enhancements

    js:
      - main.js: Cart logic, localStorage handling

  optional_folders:  # These are currently not used
    - img/: Holds product or UI images
    - products/: Optional product detail pages
    - assets/: Fonts or icons (if added in the future)

  run_instructions:
    - Clone the repository:
      - git clone https://github.com/your-username/ecommerce-website.git
    - Open index.html with any modern browser
    - No build tools or server required

  enhancements:
    - Add product quantity & remove buttons in cart
    - Create individual product detail pages
    - Implement user auth with backend
    - Add payment gateway support
    - Add search & filters

  author:
    name: Your Name
    github: https://github.com/your-username

  license:
    type: MIT
    url: https://opensource.org/licenses/MIT

  status: MVP (Minimum Viable Product) complete

  screenshots:
    - homepage: https://picsum.photos/seed/home/800/200
    - products: https://picsum.photos/seed/products/800/200
    - cart: https://picsum.photos/seed/cart/800/200
