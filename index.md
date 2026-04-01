---
layout: default
title: Kitchen-Coordinator 
---
![ci-badge](https://github.com/kitchen-coordinator/kitchen-coordinator/workflows/kitchen-coordinator/badge.svg)

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
     - [Milestone 3 Progress](#milestone-3-progress)
     - [Milestone 4 Progress](#milestone-4-progress)
     - [Milestone 5 Progress](#milestone-5-progress)

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
  * [Milestone 2 Progress](#milestone-2-progress)

### Milestone 1 Progress

Milestone 1 was all about setting up a solid foundation for **Kitchen-Coordinator**, both technically and from a user experience standpoint.

Here’s what we accomplished:

- **Mobile-friendly design mockups**  
  We created three new mobile mockup pages that rethink some of the core views (pantry, dashboard, and landing page) using card-based layouts and mobile-first interactions to make the app easier to use on smaller screens.

  ### Pantry Mobile Mockup
  <img src="assets/m1/PantryMockup.png" alt="Pantry Mobile Mockup" width="250"/>

  ### Dashboard Mobile Mockup
    <img src="assets/m1/DashboardMockup.png" width="250"/>

  ### Landing Page Mockup
    <img src="assets/m1/LandingPageMobileMockup.png" width="250"/>

- **Rebranding the project**  
  We rebranded the application from Pantry Pals to **Kitchen-Coordinator**, updating the name and documentation to reflect that this is now our own project and direction.

- **Updated user stories**  
  We refined and clarified our user stories, which helped us better understand core features and streamline our development process.

- **Database setup and deployment**  
  We connected the app to a database and deployed it using Vercel, giving us persistent data storage and a live version of the app to work with.

- **Improved developer documentation**  
  We cleaned up and expanded the README to make the Developer Guide clearer and easier to follow for anyone setting up the project.

### Milestone 1 Progress
- [Milestone 1 Project Board](https://github.com/orgs/kitchen-coordinator/projects/3)

Overall, Milestone 1 gave us a strong starting point and helped align both our technical setup and design direction.

---

### Milestone 2 Progress

# Milestone 2 Progress

Milestone 2 was all about improving functionality, usability, and overall polish. We focused on making unit handling smarter, strengthening our testing setup, and moving closer to a scalable two-tier quantity system.

---

## What We Explored

During this milestone, we:

- Explored hard-coded standard unit conversions and what that means for safety vs scalability.
- Looked into implementing a true two-tier quantity system (store in base units, display in user-friendly units).
- Evaluated tradeoffs between same-metric conversions (mass → mass, volume → volume) and cross-metric conversions (mass ↔ volume).
- Considered where conversion logic should live and how future user-defined mappings would impact performance and structure.

This helped us understand how to keep conversions clean, centralized, and safe.

---

# Unit Conversion Utility Implementation

We implemented a reusable unit conversion utility that allows consistent conversions across the project.

This utility:

- Normalizes user-entered units (kg, g, lb, fl_oz, tsp, L, etc.)
- Converts values into base units (grams for mass, milliliters for volume)
- Enables proper sorting and comparison across mixed units
- Reduces duplicate conversion logic across components

We integrated this directly into **View Pantry**, which now sorts items correctly even if they use different units.

---
## Previous – Mass Sorting

<img src="assets/m2/MassExample.png" width="600"/>

---

## Previous – Volume Sorting

<img src="assets/m2/VolumeExample.png" width="600"/>

---

## Now - Mass Sorting Example

Mixed mass units (kg, g, lb) now sort correctly.

<img src="assets/m2/MassSorting.png" width="600"/>

---

## Now - Volume Sorting Example

Mixed volume units (fl oz, L, tsp) now sort correctly.

<img src="assets/m2/VolumeSorting.png" width="600"/>

---

# Testing & CI Improvements

We also strengthened reliability during this milestone:

- Added acceptance testing with **TestCafe**
- Set up **GitHub Actions CI**
- Added a build/test status badge to the repository

Now every push automatically builds and tests the system.

---

# Where This Sets Us Up

This milestone moved the project from “basic functionality” toward something much more scalable and structured. 

Next steps include:

- Expanding the two-tier system
- Supporting user-defined unit mappings (e.g., 1 bag = 500g)
- Exploring density-based mass ↔ volume conversions
- Continuing UI improvements for mobile responsiveness

Milestone 2 helped lay the foundation for a more powerful and flexible pantry system.


📌 **Milestone 2 Project Board**  
- [Milestone 2 Project Board](https://github.com/orgs/kitchen-coordinator/projects/4/views/1)

Milestone 2 is focused on making Kitchen-Coordinator more intuitive and practical for everyday use while strengthening the overall system.

---

# Milestone 3 Goals  
*(Architecture → Advanced Functionality → Performance → UX Refinement)*

Milestone 3 focuses on fully implementing and stabilizing the two-tier unit system, expanding conversion capabilities, improving performance, and refining the mobile experience.

---

## Complete Implementation of the Common Two-Tier Unit System

Move from exploration to full implementation.

**Goals:**
- Finalize the two-tier storage model (base unit + display unit)
- Implement user-input common items for reusable mappings
- Implement two-tier display logic inside Pantry
- Ensure all conversions route through a single source-of-truth utility
- Maintain backward compatibility with existing pantry data

---

## Density-Based Mass ↔ Volume Conversions

Move from exploration into real cross-category functionality.

**Goals:**
- Persist user-input density in the database
- Implement density-based conversion utility
- Integrate density conversions into pantry and recipe flows
- Add error handling for missing or invalid density
- Add test coverage for cross-metric conversions

---

## Mobile-First UI Expansion

Extend the mobile improvements started in Milestone 2.

**Goals:**
- Implement mobile-friendly design for Pantry
- Implement mobile-friendly design for Dashboard
- Implement mobile-friendly design for Landing Page
- Improve touch targets and simplify layout for small screens
- Reduce visual clutter introduced by new two-tier features

---

## Performance & UX Optimization

Address user experience polish and technical performance.

**Goals:**
- Investigate and reduce user login delay
- Research and implement improved preloader/loading states
- Optimize conversion performance (especially DB lookups for rules)
- Improve perceived performance during sorting and conversions

---

## Feature Expansion & Input Innovation

Begin expanding beyond core pantry input.

**Goals:**
- Research implementation of recipe scanner for pantry input
- Design a “Use” button workflow for consuming pantry items
- Ensure new workflows integrate cleanly with two-tier and density systems

---

## Milestone 3 Theme

If Milestone 2 was:

> “Make conversions work and improve structure.”

Then Milestone 3 is:

> “Make the system scalable, smart, and production-ready.”

---

# Milestone 4 Progress

Milestone 4 focused on improving usability, expanding the two-tier system, and refining the overall interface of **Kitchen-Coordinator**.  
During this milestone we implemented the **Two-Tier Common Item system**, improved **mobile responsiveness**, and fixed several UI and stability issues throughout the application.

These changes make pantry management more intuitive while keeping the backend unit system clean and consistent.

---

## Two-Tier Common Item System

The major feature completed in Milestone 4 was the implementation of a **Two-Tier Common Item system**.

This system allows users to define reusable item conversions that represent real-world packaging sizes or quantities. For example, users can define values such as:

- 0.25 jars  
- 1 bottle  
- 1 bag

These reusable conversions make it easier to quickly add and edit pantry items without manually calculating quantities every time.

This feature was integrated into several core pages of the application:

- Pantry Page  
- Add Item Page  
- Edit Item Page  

When a user selects a common item conversion, the application automatically converts that value into a standardized backend unit such as:

- kilograms (kg)
- grams (g)
- cups
- liters

<img src="assets/m4/m4_Database.png" width="700"/>

This ensures that all pantry data is stored consistently in the database while still allowing users to interact with familiar measurements.

### Two-Tier System Example

<img src="assets/m4/m4_Pantry.png" width="700"/>

---

## Mobile UI Improvements

Another major focus of Milestone 4 was improving the **mobile experience** of the application.

Several pages were redesigned to better support smaller screens and mobile interaction.

Pages improved in this milestone include:

- Pantry page (Added Shopping Cart)
- Edit item page
- Landing page

We redesigned pantry cards and improved spacing to make the interface easier to navigate on phones and tablets.

### Mobile Pantry Interface

<img src="assets/m4/m4_SC.png" width="700"/>

<img src="assets/m4/m4_edit.png" width="700"/>

---

## Navigation and UI Refinements

We also implemented several UI improvements to make the interface cleaner and easier to use.

Key updates include:

- A redesigned **navigation bar icon**
- A **collapsible navigation menu** for smaller screens
- Improved spacing and readability across pages

These changes help users navigate the application more efficiently.

### Navigation Improvements

<img src="assets/m4/m4_navbar.png" width="700"/>

---

## Improved User Interaction Feedback

We improved the visual feedback users receive when interacting with the interface.

These updates include:

- Cursor style changes when hovering over icons
- Clearer visual indicators for interactive UI elements

These small improvements make the interface feel more responsive and intuitive.

### New Dashboard and Landing Example

<img src="assets/m4/m4_dashboard.png" width="700"/>

<img src="assets/m4/m4_landing.png" width="700"/>

---

## Bug Fixes and Stability Improvements

Milestone 4 also addressed several technical issues in the project.

Fixes included:

- Resolving merge conflicts across development branches
- Fixing pantry display bugs
- Improving stability when rendering pantry items

These updates helped ensure the pantry system behaves reliably and consistently.

### Conditional Padding Fix

### Before

<img src="assets/m4/m4_before.png" width="700"/>

#### After

<img src="assets/m4/m4_after.png" width="700"/>

---

# Milestone 5 Progress

Milestone 5 focused on transforming Kitchen-Coordinator from a collection of individual features into a fully connected system.
During this milestone, we introduced the shopping list system, integrated pantry and recipes, and expanded our backend to support more realistic user workflows.

These changes significantly improved how users interact with the app in real-world scenarios, especially when cooking and restocking ingredients.

## Shopping List System

The biggest feature introduced in this milestone was a complete Shopping List system.

Users can now:

Create and manage shopping lists
Add and remove items
Track which items have been completed
Restock pantry items directly from the shopping list

This system is supported by new backend API routes and frontend components, making it fully integrated into the application.

Shopping List Example

<img src="assets/m5/m5_createlist.png" width="500"/>
<img src="assets/m5/m5_list.png" width="500"/>
<img src="assets/m5/m5_shoppinglist.png" width="500"/>

## Pantry and Shopping List Integration

We expanded functionality by connecting the pantry directly to the shopping list system.

New logic allows:

Pantry items to trigger restock actions
Shopping list items to update pantry quantities
Better tracking of what needs to be replenished

This creates a smoother workflow where users can go from low inventory → shopping list → restocking without friction.

## Recipe and Pantry Integration

Recipes were upgraded to interact directly with pantry data.

Users can now:

Use ingredients from their pantry when cooking
Automatically deduct ingredient quantities
Keep their pantry up to date based on actual usage

This makes recipes more than just references — they are now part of the core system workflow.

<img src="assets/m5/m5_usebutton.png" width="500"/>

## Database and Backend Improvements

Significant updates were made to the database and backend structure.

These include:

New tables for shopping lists and related items
Updated relationships between pantry, recipes, and shopping lists
Prisma schema updates and migrations

These changes allow the system to support more complex interactions between features.

## UI and Dashboard Improvements

We continued improving the overall user experience.

Updates include:

Improved dashboard with better alerts and feedback
Cleaner layout and navigation
More consistent styling across pages

These changes make the app easier to navigate and more intuitive to use.

## Milestone 5 Impact

The application now supports a full workflow from:

Managing pantry items
Cooking with recipes
Tracking usage
Restocking through shopping lists

# Milestone 6 Goals

Milestone 6 focuses on finalizing functionality, design, and overall polish to prepare the application for a stable and complete user experience.

## Full System Integration

Ensure all core systems work seamlessly together:

Pantry ↔ Recipes ↔ Shopping Lists
Verify end-to-end workflows:
Use ingredients → update pantry → generate restock items

The goal is to eliminate any disconnected or incomplete features.

## UI/UX Refinement

Improve the overall look and usability of the application.

Goals include:

Consistent design across all pages
Improved mobile responsiveness
Cleaner layouts and better spacing
More intuitive user interactions

The app should feel cohesive and easy to use.

## Performance and Stability

Improve reliability across the application.

Goals include:

Fix remaining bugs and edge cases
Optimize data fetching and rendering
Ensure consistent behavior in both development and deployment
Testing and Reliability

## Strengthen testing coverage and CI stability.

Goals include:

Add missing Playwright tests for key pages
Use stable selectors for reliable testing
Ensure all tests pass consistently before deployment
Code Quality and Maintainability

Clean up and improve the codebase.

Goals include:

Remove unused or redundant code
Improve type safety
Refactor complex logic into reusable utilities
Maintain consistent coding patterns
Deployment and Final Readiness

## Prepare the application for final presentation and use.

Goals include:

Resolve deployment issues (e.g., Prisma, API routes)
Ensure production build runs without errors
Deliver a stable and polished final product



## Development Team
- <img src="assets/m4/githubicon.png" width="15" height="15">[Mishalyn Mei Ilmeng](https://github.com/mishalyn-mei-ilmeng)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Simon Lin](https://github.com/simonwlin)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kwanho Chun](https://github.com/kwanhoc1)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Kawika Naweli](https://github.com/KawikaN)
- <img src="assets/m4/githubicon.png" width="15" height="15">[Eli Thompson](https://github.com/EliThomp)




