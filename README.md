## Restaurant Chatbot

## Demo link

You can view the live project [here](https://the-restaurant-chatbot.onrender.com/)

## About The App

This is basically a restaurant chatbot that assists customers in placing orders for their preferred meals. Customers are able to send options and the backend has a chat app that would respond to the options. 

## Technologies used

Node, Express, Socket.io

## Project setup

Download or clone the repository

run `npm install` to install all packages used.

Run `npm run dev` to start the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Approach

- The customer sends a message to the chatbot

- The chatbot responds with options for the user to select from:

- Select 1 to Place an order
- Select 99 to checkout order
- Select 98 to see order history
- Select 97 to see current order
- Select 0 to cancel order

- When the customer selects 1, the chatbot returns the list of the items the customer can order

- When the customer selects 99, the chatbot places the order for the customer according to his or her choice.

- When the customer selects 98, the chatbot responds with the history of orders created by the customer.

- When the customer selects 97, the chatbot displays the current order the customer made.

- When the customer selects 0, the chatbot cancels the order made by the customer.

## Status

Completed.

## Contributor

Michael Abaniwo
