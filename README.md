## Getting Started

<div align="center">
   <a href="https://heliohdd-fast-react-pizza.vercel.app" alt="The Wild Oasis">
   <img src="./src/assets/to_readme/FastReactPizzaCo.gif" width="500px" alt="Home Page" />
   <a>
</div>

Run each of the lines above in a git bash terminal:

1. Clone the repository

```sh
git clone https://github.com/heliohdd/fast-react-pizza.git
```

2. Change to the project folder

```sh
cd fast-react-pizza
```

3. Install NPM packages dependencies

```sh
npm install
```

4. Now run the application

```sh
npm run dev
```

And then open [http://localhost:5173](http://localhost:5173) with your browser to see the result.

## Introduction

<b>"Fast React Pizza Co."</b> is a site that allow customers to <b>order pizzas and get them delivered</b> to their home.

## Project Requirements From the Business

1. Very simple application, where users can order <b>one or more pizzas from a menu</b>
1. Requires <b>no user accounts</b> and no login: users just input their names before using the app
1. The pizza menu can change, so it should be <b>loaded from an API</b>
1. Users can add multiple pizzas to a <b>cart</b> before ordering
1. Ordering requires just the <b>user's name, phone number</b>, and <b>address</b>
1. <b>GPS location</b> is also provided, so to make delivery easier
1. User's can <b>mark their order as "priority"</b> for an additional 20% of the cart price
1. Orders are made by <b>sending a POST request</b> with the order data (user data + selected pizzas) to the API
1. Payments are made on delivery, so <b>no payment processing</b> is necessary in the app at this moment
1. Each order will get a <b>unique ID</b> that should be displayed, so the <b>user can later look up their order</b> based on the ID
1. Users should be able to mark their order as "priority" order <b>even after it has been placed</b>

<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->

## Technology & Tools

- React Router for routing
- Tailwindcss for styling
- React Router for remote state management
- Redux for UI state management

## Structure of the application

<!-- This application is used internally as tool inside a company, that are entirely hidden behind a login it was used to build a Single-Page-Application and this application is composed of 8 pages that represents 7 features categories as listed below: -->

1. Homepage
1. Pizza menu
1. Cart
1. Placing a new order
1. Looking up an order
