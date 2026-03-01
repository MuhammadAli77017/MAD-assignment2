# 🍽️ Ali Restaurant API

This project is a **simple restaurant backend server** built using **Node.js and Express**.
It provides a basic API that allows users to view the restaurant menu, search for food items, and place orders.

The server contains a **hardcoded menu catalog** with food items such as pizza, burgers, biryani, pasta, and drinks.
It is designed for learning purposes and can be connected with a **React Native (Expo) frontend application**.

## 📌 Features

* View full restaurant menu
* Get a single menu item by ID
* Search menu items by name
* Place a food order
* Simple REST API endpoints

## 📂 Project Structure

```
restaurant-app
│
├── server.js        # Backend server file
├── package.json     # Project dependencies
└── README.md        # Project documentation
```

## ⚙️ Requirements

Before running the project, make sure you have installed:

* Node.js
* npm (Node Package Manager)

## 📦 Install Dependencies

Open the project folder in terminal and run:

```
npm install
```

This will install all required packages such as **Express**.

## ▶️ Run the Server

Start the backend server using:

```
node server.js
```

If everything runs correctly, you will see messages like:

```
🚀 FoodHub Server Running
Home: http://localhost:3000
Menu: http://localhost:3000/menu
```

## 🌐 API Endpoints

| Endpoint            | Method | Description            |
| ------------------- | ------ | ---------------------- |
| `/`                 | GET    | Show API information   |
| `/menu`             | GET    | Get all menu items     |
| `/menu/:id`         | GET    | Get a single food item |
| `/search?name=item` | GET    | Search food in menu    |
| `/order`            | POST   | Place a new order      |

## 📱 Frontend Connection

This API can be connected with a **React Native (Expo) mobile app** to display the menu and place orders directly from the phone.

## 👨‍💻 Author

Ali Restaurant App Backend
Created for learning **Node.js, Express, and API development**.
