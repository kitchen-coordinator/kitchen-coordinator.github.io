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
     - [Milestone 2 Progress](#milestone-2-progress)


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

## Milestones

### Milestone 1 Progress

Milestone 1 was all about setting up a solid foundation for **Kitchen-Coordinator**, both technically and from a user experience standpoint.

Here’s what we accomplished:

- **Mobile-friendly design mockups**  
  We created three new mobile mockup pages that rethink some of the core views (pantry, dashboard, and landing page) using card-based layouts and mobile-first interactions to make the app easier to use on smaller screens.

  ### Pantry Mobile Mockup
  ![Pantry Mobile Mockup](assets/m1/PantryMockup.png)

  ### Dashboard Mobile Mockup
  ![Dashboard Mobile Mockup](assets/m1/DashboardMockup.png)

  ### Landing Page Mockup
  ![Landing Page Mockup](assets/m1/LandingPage.png)

- **Rebranding the project**  
  We rebranded the application from Pantry Pals to **Kitchen-Coordinator**, updating the name and documentation to reflect that this is now our own project and direction.

- **Updated user stories**  
  We refined and clarified our user stories, which helped us better understand core features and streamline our development process.

- **Database setup and deployment**  
  We connected the app to a database and deployed it using Vercel, giving us persistent data storage and a live version of the app to work with.

- **Improved developer documentation**  
  We cleaned up and expanded the README to make the Developer Guide clearer and easier to follow for anyone setting up the project.

**Milestone 1 Project Board**  
https://github.com/orgs/kitchen-coordinator/projects/3/views/1

Overall, Milestone 1 gave us a strong starting point and helped align both our technical setup and design direction.

---

### Milestone 2 Goals

Milestone 2 builds directly on what we accomplished in Milestone 1, with a bigger focus on functionality, usability, and polish.

Our goals for Milestone 2 include:

- **Two-tier quantity and conversion system**  
  We want to build user-friendly conversion tools that let pantry items stored in package-based units (like bags or boxes) be converted into recipe-friendly units. For example, setting up mappings like *1 bag = 500 g* so ingredients can be accurately used in recipes.

- **Unit conversion with error handling**  
  Add support for common cooking conversions such as cups to tablespoons and teaspoons, along with proper validation and error handling when conversions don’t make sense.

- **Mobile-friendly UI implementation**  
  Turn our approved mobile mockups into real, working layouts inside the app to improve the experience on phones and tablets.

- **More mobile-focused UI development**  
  Design and prototype additional mobile-friendly UI components that prioritize usability on smaller screens, including card-based layouts, simplified navigation, and touch-friendly interactions to support new features and workflows       introduced in this milestone.


- **Continued testing and refinement**  
  Add more acceptance tests and continue polishing the UI and performance across both desktop and mobile views.

📌 **Milestone 2 Project Board**  
https://github.com/orgs/kitchen-coordinator/projects/4/views/1

Milestone 2 is focused on making Kitchen-Coordinator more intuitive and practical for everyday use while strengthening the overall system.


---

## Development Team
- <img src="assets/m4/githubicon.png" width="15" height="15">[Mishalyn Mei Ilmeng](https://github.com/mishalyn-mei-ilmeng)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Simon Lin](https://github.com/simonwlin)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kwanho Chun](https://github.com/kwanhoc1)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kawika Naweli](https://github.com/KawikaN)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Eli Thompson](https://github.com/EliThomp)




