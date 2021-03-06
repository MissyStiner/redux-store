# Redux Store

## Description
This is an e-commerce site that's been refactored to use Redux.

## GitHub URL
https://github.com/MissyStiner/redux-store

## Application URL
https://damp-beach-51339.herokuapp.com/

## User Story
AS a senior engineer working on an e-commerce platform<br>
I WANT my platform to use Redux to manage global state instead of the Context API<br>
SO THAT my website's state management is taken out of the React ecosystem

## Acceptance Criteria
GIVEN an e-commerce platform that uses Redux to manage global state<br>
WHEN I review the app’s store<br>
THEN I find that the app uses a Redux store instead of the Context API<br>
WHEN I review the way the React front end accesses the store<br>
THEN I find that the app uses a Redux provider<br>
WHEN I review the way the app determines changes to its global state<br>
THEN I find that the app passes reducers to a Redux store instead of using the Context API<br>
WHEN I review the way the app extracts state data from the store<br>
THEN I find that the app uses Redux instead of the Context API<br>
WHEN I review the way the app dispatches actions<br>
THEN I find that the app uses Redux instead of the Context API

## Mock-Up
- A user can register using the Signup page and then navigate to the Products page:<br>
![https://github.com/MissyStiner/redux-store/blob/main/assets/22-state-homework-demo-01.gif]

- The user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:<br>
![https://github.com/MissyStiner/redux-store/blob/main/assets/22-state-homework-demo-02.gif]

- The user can checkout by going to their shopping cart, as shown in the following animation:<br>
![https://github.com/MissyStiner/redux-store/blob/main/assets/22-state-homework-demo-03.gif]

