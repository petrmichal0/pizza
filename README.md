# Pizza

## Project Title and Description
Pizza is a web application designed to manage a pizza restaurant's menu, orders, and user information. Users can browse the menu, place orders, and track their orders.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/89d73842-7bc6-4149-88ce-006fe39e309d" width="700" alt="Pizza App Demo">

## Table of Content
- [Project Title and Description](#project-title-and-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Demo (link)](#demo-link)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Third-Party Libraries](#third-party-libraries)
- [License](#license)

## Features
- Browse menu items
- Place and manage orders
- User management
- Search orders
- Update order information
- User-friendly interface

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm (v6 or higher)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/petrmichal0/pizza.git
    ```

2. Navigate to the project directory:
    ```bash
    cd pizza
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the application, run the following command:
```bash
npm run dev
```

After starting, go to [http://localhost:3000](http://localhost:3000) in your web browser.

## Screenshots

<table>
  <tr>
    <th>Homepage</th>
    <th>Ordering Pizza</th>
    <th>Order Cart</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/4eed151e-d458-4092-a0b8-29898399ca0f" width="300" height="300" alt="Homepage">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/915db2d5-0241-42a5-92ce-705d64b269a0" width="300" height="300" alt="Ordering Pizza">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/a2f46a3e-2778-4dd1-9d86-b9c9a07240a6" width="300" height="300" alt="Order Cart">
    </td>
  </tr>
  <tr>
    <th>Add Information / Order Confirmation</th>
    <th>Order finish list</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/255e0018-21ae-4182-891d-c548050bbb8e" width="300" height="300" alt="Add Information / Order Confirmation">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/8dc33712-0f58-4288-8838-322325a71520" width="300" height="300" alt="Order finish list">
    </td>
  </tr>
</table>

## Demo (link)

Check out the live demo of the application [here](https://pizza-2023.netlify.app/).

## Project Structure

```css
Pizza/
├── public/
│   ├── vite.svg
├── src/
│   ├── features/
│   │   ├── cart/
│   │   │   ├── Cart.jsx
│   │   │   ├── CartItem.jsx
│   │   │   ├── CartOverview.jsx
│   │   │   ├── DeleteItem.jsx
│   │   │   ├── EmptyCart.jsx
│   │   │   ├── UpdateItemQuantity.jsx
│   │   │   ├── cartSlice.js
│   │   ├── menu/
│   │   │   ├── Menu.jsx
│   │   │   ├── MenuItem.jsx
│   │   ├── order/
│   │   │   ├── CreateOrder.jsx
│   │   │   ├── Order.jsx
│   │   │   ├── OrderItem.jsx
│   │   │   ├── SearchOrder.jsx
│   │   │   ├── UpdateOrder.jsx
│   │   ├── user/
│   │   │   ├── CreateUser.jsx
│   │   │   ├── Username.jsx
│   │   │   ├── userSlice.js
│   ├── services/
│   │   ├── apiGeocoding.js
│   │   ├── apiRestaurant.js
│   ├── ui/
│   │   ├── AppLayout.jsx
│   │   ├── Button.jsx
│   │   ├── Error.jsx
│   │   ├── Header.jsx
│   │   ├── Home.jsx
│   │   ├── LinkButton.jsx
│   │   ├── Loader.jsx
│   ├── utils/
│   │   ├── helpers.js
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── store.js
├── .prettierrc
├── .gitignore
├── README.md
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.js
└── vite.config.js
```

## Technologies Used

[![React Badge](https://img.shields.io/badge/-React-61DBFB?style=for-the-badge&labelColor=black&logo=react&logoColor=61DBFB)](#)
[![Vite Badge](https://img.shields.io/badge/-Vite-646CFF?style=for-the-badge&labelColor=black&logo=vite&logoColor=646CFF)](#)
[![Redux Badge](https://img.shields.io/badge/-Redux-764ABC?style=for-the-badge&labelColor=black&logo=redux&logoColor=764ABC)](#)
[![TailwindCSS Badge](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=for-the-badge&labelColor=black&logo=tailwindcss&logoColor=38B2AC)](#)

## Third-Party Libraries

* React Router
* @reduxjs/toolkit
* react-redux
* tailwindcss
* react-router-dom
* eslint
* prettier
* postcss
* autoprefixer

## License

This project is licensed under the MIT License - see the LICENSE file for details.

