---
layout: default
title: Kitchen-Coordinator 
---

# Kitchen-Coordinator 

## Table of Contents
1. [Overview](#overview)
2. [Deployment](#deployment)
3. [Team Contract](#team-contract)
4. [User Guide](#user-guide)
5. [Developer Guide](#developer-guide)
6. [Development Team](#development-team)
7. [Milestones](#milestones)
     - [Milestone 1 Progress](#milestone-1-progress)


<!--
comment out add in later as we progress through project
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Walkthrough videos](#walkthrough-videos)
* [Example enhancements](#example-enhancements)
* [Team](#team)
-->

---

## Overview

### Problem
_What's the point of a pantry app?_
- People often forget what they have in their pantry, fridge, or spice rack
- Expired food leads to waste and wasted money 
- Grocery shopping is inefficient without knowing what's already at home

### Approach
- Create a digital inventory system for pantry, fridge, freezer, and spices
- Allow users to easily add, remove, and update items
- Automatically generate shopping lists when items are low or missing
- Simple and clean interface so it's quick to use every day

### Use Case Ideas
- Before going to the store, check what items are low or expired
- While cooking, search the app to see if you have a specific ingredient
- Share the pantry list with family or roomates so everyone is synced
- Use expiration reminders to finish food before it spoils

### Beyond the Basics
- Barcode scanner for quick item entry
- Recipe suggestions based on available ingredients 
- Reports that show spending trends and reduce food waste
- Possible integration with smart home assistance like Alexa or Google Assistant

## Deployment

---

## Team Contract
[Link to Team Contract](https://docs.google.com/document/d/1VzBkSbz36BjpE7QcRbgKxxXCnpzzko8UlDvcngXWB2k/edit?tab=t.)


---
## Credits and Attribution 
This project is forked off of the [Pantry Pals appliction](https://github.com/pantry-pals/pantry-pal). This project builds upon the code with additional features.

---
## User Guide
An intro to using pantry pals  

### Sign in page
Sign up for pantry pals and verify your email to sign in
![Pantry App Sign Up_Screenshot](assets/m4/m4_signup.png)
![Pantry App Sign In_Screenshot](assets/m4/m4_signin.png)

### Dashboard
Users have easy access to all pages through Pantry Pal's dashboard
![Pantry App Dashboard_Screenshot](assets/m5/m5_dashboard.png)

### View your pantry
Pantry pals allows you to easily keep track of what ingredients you have in your household, where they are, and how much of them you have left
![Pantry App InventoryList_Screenshot](assets/m5/m5_pantry_table.png)
![Pantry App InventoryCards_Screenshot](assets/m5/m5_pantry_cards.png)

### Add and Edit your pantry
Keep track of your spices and food by adding them to your pantry  
![Pantry App Add Item_Screenshot](assets/m5/m5_addProduceModal.png)
![Pantry App Edit Item_Screenshot](assets/m5/m5_editProduceModal.png)
![Pantry App Delete Item_Screenshot](assets/m4/m4_deleteitem.png)

### Create Shopping Lists
Easily create and manage your shopping list based on what’s running low in your pantry. Check off items as you shop to keep your inventory up to date.
![Pantry App CreateShoppingList_ScreenShot](assets/m6/m6_create_shoppinglist.png)
![Pantry App ShoppingList_Screenshot](assets/m4/m4_shoppinglists.png)
![Pantry App ViewShoppingList_Screenshot](assets/m4/m4_shoppinglist_view.png)

### Find Recipes
Discover recipes you can make with the ingredients you already have. Pantry Pals helps you reduce waste and find meal ideas tailored to your pantry.
![Pantry App Recipes Screenshot](assets/m5/m5_recipes.png)
![Pantry App Recipes I Can Make](assets/m5/m5_recipes_make.png)
![Pantry App Recipes Instructions](assets/m5/m5_recipes_instructions.png)

---

## Developer Guide
This section provides information of interest to developers wishing to use this code base as a basis for their own development tasks.

### Installation
First, install [Node.js](https://nodejs.org/en/download/)

Second, visit the [Kitchen-Coordinator application github page](https://github.com/kitchen-coordinator/kitchen-coordinator), and click the “Use this template” button to create your own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the pantry-pal directory and install libraries with:
```
$ npm install
```

Fourth, run the system with:
```
$ npm run dev
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

### Application Design
Kitchen-Coordinator is based upon the ICS Software Engineering [Next.js Application Template](https://github.com/ics-software-engineering/nextjs-application-template).

---

## Milestones
  * [Milestone 1 Progress](#milestone-1-progress)

### Milestone 1 Progress
[Milestone 1 Project Board](https://github.com/orgs/kitchen-coordinator/projects/3)

---

## Development Team
- <img src="assets/m4/githubicon.png" width="15" height="15">[Mishalyn Mei Ilmeng](https://github.com/mishalyn-mei-ilmeng)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Simon Lin](https://github.com/simonwlin)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kwanho Chun](https://github.com/kwanhoc1)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kawika Naweli](https://github.com/KawikaN)




