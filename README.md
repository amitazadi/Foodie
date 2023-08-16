<h1 >Project Title: Foodie</h1> 

## Table of Content

- [About the Project](#about-the-project)

- [Project Overview](#project-overview)

- [Folder structure](#folder-structure)

- [Technologies Used](#technologies-used)

- [Setup and Installation](#setup-and-installation)

- [Status](#status)


## About the Project
Welcome to the Your Food Delight project – your one-stop destination for exploring local restaurants, discovering delicious menus, and placing food orders seamlessly. Our web application is designed to bring the culinary world closer to you, making it convenient to satisfy your cravings from the comfort of your home.

## Project Overview

- **Search Restaurants:** Our intuitive search feature allows users to explore restaurants in a specific city by entering the city's name. This feature connects food enthusiasts with a variety of dining options available near them.

- **Browse Menus:** Once a restaurant is selected, users can easily access the restaurant's menu. Whether you're in the mood for a hearty breakfast, a quick lunch, or an indulgent dinner, our platform provides an interactive menu browsing experience.

- **Create Orders:** Users can curate their ideal meal by adding items from the menu to their cart. Our seamless cart functionality lets users review their selections, make modifications, and proceed to the checkout stage.

There are some images through which we can idea of our UI.

![ss-5](https://github.com/amitazadi/Foodie/assets/56012894/a18de84c-676c-409d-b052-0b8545009002)

![ss-2](https://github.com/amitazadi/Foodie/assets/56012894/85b07478-ee9b-42fc-b270-6aba2d9a3da7)

![ss-3](https://github.com/amitazadi/Foodie/assets/56012894/bffea443-5a9f-4d8c-8f16-46888ee9462d)

![ss-4](https://github.com/amitazadi/Foodie/assets/56012894/4a0d6a40-dfdc-42a4-88e8-921de6f4bfe9)

### Key Features

- **Restaurant Search:** Effortlessly find restaurants in your city of choice. Discover culinary gems and well-loved eateries, all in one place.

- **Menu Exploration:** View detailed menus with vivid descriptions and mouthwatering images. Dive into the diverse range of dishes offered by each restaurant.

- **Customized Orders:** Create personalized orders by adding items to your cart. Make adjustments, view the subtotal, and ensure your meal suits your cravings.

- **Convenient Checkout:** Our streamlined checkout process ensures a hassle-free experience. Provide delivery details, review your order, and finalize your food journey.

- **User-Friendly Interface:** Enjoy a responsive and user-centric design that adapts to various devices. Whether you're on a laptop, tablet, or smartphone, the experience remains consistent and delightful.


## Folder structure

The project follows a structured organization to keep the codebase clean and maintainable. Here's an overview of the key folders and their purposes:

```bash
Root Folder
+---public
|       favicon.ico
|       index.html
|       
\---src
    |   App.css
    |   App.js
    |   index.css
    |   index.js
    |   
    +---component
    |   |   About.js
    |   |   Body.js
    |   |   Cart.js
    |   |   Contact.js
    |   |   Home.js
    |   |   Menu.js
    |   |   MenuCard.js
    |   |   MenuShimmer.js
    |   |   ModalPopup.js
    |   |   Navbar.js
    |   |   PageNotFound.js
    |   |   RestaurantCard.js
    |   |   Restaurants.js
    |   |   RestaurantsShimmer.js
    |   |   Search.js
    |   |   
    |   \---Redux
    |       |   store.js
    |       |   
    |       \---features
    |               cartSlice.js
    |               coordsSlice.js
    |               
    +---img
    |       bg.png
    |       cart-img.webp
    |       
    \---utils
            constants.js
            useGetRestaurantMenu.js
            useGetRestaurants.js

```

### Description

- **`./src/components/`**: Dashboard reusable UI components. Each component should ideally be self-contained and not directly connected to the app's state.

- **`./src/component/Redux/store.js`**: Manages state management using Redux. `actions/` contains action creators, `reducers/` holds reducer functions, and `store.js` sets up the Redux store.

- **`./src/img/`**: This directory contains static assets such as images and global styles that are used throughout the project.

- **`./src/utils/`**: Stores utility functions, helper classes, or modules that are used across different parts of the application.

- **`./App.js`**: The root component of the application where routing and main layout components are often defined.

- **`./index.js`**: The entry point of the application where React is initialized and the root component is rendered.

This structure ensures a separation of concerns and makes it easier to locate and update different parts of the application. It also allows for better code organization, easier collaboration, and smoother debugging.


## Technologies Used

**ReactJs:** The project is built using React, a popular JavaScript library for building user interfaces. It utilizes state management with Redux for efficient data handling and updates.

**Redux:** To manage and organize the application's state in a predictable and centralized manner, making it easier to develop and maintain complex applications.

**Bootstrap:** Styling is done with CSS, and Bootstrap. Leveraging modern design principles to create a visually appealing and responsive dashboard.


## Setup and Installation

Here are the installation steps for setting up a project:

<ul>

<li>Download and install Node.js from the official website(https://nodejs.org/).</li>
</br>

<li> Verify Node.js and npm Installation. 

```
node -v
npm -v
```
</li>

<li>Clone the Repository using this command.

```
git clone <repository-url>
```
</li>

<li>Navigate to the project directory.

```
cd project-name
```
</li>

<li>Install al the required dependencies.

```
npm install
```
</li>

<li>Start the development server.

```
npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
</li>

</ul>



## Status 
**Status of the project:** Completed
