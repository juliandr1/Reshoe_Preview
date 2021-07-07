Original App Design Project - README Template
===

# Reshoe

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
A social media app specifically designed to help people connect and interact with local barbers. Users can rate barbers and provide feedback to others who are looking for select styles. Both barbers and users can post images of their haircuts, in order to give others an idea of the type of styles they want. Through the search process, users can filter by location, style, and price.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:**
- **Mobile:**
- **Story:**
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Users can view and post images about shoes (Sellers post and buyers view).
* Buyers can post ratings about shops.
* Users can login, choosing between a seller or buyer account. Sellers must say whether they do drop-off or have an actual storefront.
* Buyers and sellers must be able to communicate with one another.

**Optional Nice-to-have Stories**

* Buyers can get directions to the shoe store (if it exists) via Google Maps.
* Sellers can connect their other social media pages to the app.
* Clean and accessible UI design.
* Notifications remind users of new releases from a favorited shop.
* Users can create an account through linking external accounts: Google, Facebook, Snapchat, etc.

### 2. Screen Archetypes

* Login screen
   * Users can login
* Account registration screen
   * New users can create an account, choosing a buyer or a seller account.
* Search screen
   * Users can view local shops.
   * Sellers' ratings and location shown on the map screen.
* Seller Detailed Screen
   * Buyers can view the gallery of shoe images and reviews.
* Direct Message Screen
   * Users communicate with one another to discuss prices or potential drop-off location.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home (Account information)
* Search sellers
* Post image (Review)

**Flow Navigation** (Screen to Screen)

* Login
   => Registration (if not account created)
   => Home Timeline
* Registration
   => Login (if account already created)
* Home Timeline
   => Detailed Shoe Screen
   => Detailed Seller Screen
* Map screen
   => Seller Detailed Screen 
* Detailed Seller Screen
   => Directions Screen 
   => Message Shop Screen
   => Detailed Shoe Screen
   => Home Timeline
* Directions Screen
   => Detailed Seller Screen
* Message Shop Screen
   => Detailed Seller Screen
* Detailed Shoe Screen
   => Home Timeline
   => Detailed Seller Screen   
* Profile Screen
   => Edit Account Info/Profile Picture
   => Edit Payment Options
   => Edit Settings

## Wireframes
<img src="Wireframe.png" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
