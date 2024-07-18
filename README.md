# Pizza

## Project Title and Description
Pizza is a web application designed to manage a pizza restaurant's menu, orders, and user information. Users can browse the menu, place orders, and track their orders.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/478544d2-9be4-4121-af72-09f896c1cb7f" width="700" alt="Pizza App Demo">

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
    <th>Order Management</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/2af0a439-f8aa-4890-bf83-0407d1a0d018" width="300" height="300" alt="Homepage">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/745a3558-32dd-400a-8c65-b5e7c01a12f4" width="300" height="300" alt="Order Management">
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


