
# E-commerce Application 🛍️

### Refer to the video below:

<br/>
<div style="text-align: center;">
  <video style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12);outline:none;" loop="true" autoplay="autoplay" controls="controls" muted>
    <source src="https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-output.mp4" type="video/mp4">
  </video>
</div>
<br/>


A complete **E-commerce Application** that offers users a smooth shopping experience with product browsing, search, detailed product views, cart management, and protected routes.

## 🚀 Live Demo

👉 [Click here to view the live site](https://bhumiecomapp.ccbp.tech)  
🔗 URL: https://bhumiecomapp.ccbp.tech

## ✨ Features

- 🔐 **Login Functionality**  
  Users must log in with valid credentials to access the store features. The application uses JWT tokens for secure session handling.

- 🛒 **Product Listing Page**  
  Displays a wide selection of products with name, image, rating, and price. Users can scroll through and pick items of interest.

- 🔍 **Search Products**  
  Users can search for specific products using the search input. The results update in real-time based on the search term.

- 📦 **Product Details Page**  
  Clicking on a product shows a detailed page with:
  - Product image  
  - Title & description  
  - Price & availability  
  - Brand and total reviews  
  - Star rating  
  - Quantity selector  
  - Add to Cart functionality

- 🛍️ **Cart Page**  
  - View all added items  
  - Increase or decrease quantity  
  - Remove individual items  
  - View total order amount  
  - Clear entire cart  
  - Empty cart message if no products are added

- 🚫 **Protected Routes**  
  Users cannot access product or cart pages without logging in. Unauthorized access redirects to the login page.

- 📴 **Failure Page**  
  If the user navigates to an invalid route, a custom "Not Found" page is shown.

- 🔁 **Persistent Cart**  
  Cart items remain stored until removed manually, even after refreshing the page (if session is still valid).

- 📱 **Responsive Design**  
  Works smoothly on all screen sizes including mobile, tablet, and desktop.

- 🔄 **Loading Indicators**  
  Loading spinners are shown while fetching products or product details to enhance UX.

## 🛠️ Tech Stack

- React JS  
- JSX  
- CSS  
- React Router  
- REST API  
- JWT Authentication

