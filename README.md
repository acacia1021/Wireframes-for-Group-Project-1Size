# Wireframes-for-Group-Project-1Size

Group Project - README Template
===

1SIZE

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
1Size - It’s an app that allows the user to input the age, height, weight, clothing size, shoes size, etc. and it show all types of clothes and shoes that you might like to wear. It also give the location of stores near you with the clothes that you may like and if they have it in stock or not. You can buy the clothes in store or you can buy it online. It allows you to try it on before you purchase it so you’re just not stuck with clothes that do not fit.


### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Shopping
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer, such as tinder or other similar apps. Functionality wouldn’t be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Keeps track of clothing we have liked and suggests further clothing we may like from other places.
- **Market:** Anyone that is interested in clothing or sharing clothing favorites with their friends
- **Habit:** This app could be used as often or unoften as the user wanted depending on how deep their social life is, and what exactly they’re looking for.
- **Scope:** First we want to make it possible to view clothing on different store sites and be able to add them to our favorites list or preferences, and later be able to seach for items specifically depedning on these preferences.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User Log in
* User Register
* User can like/thumbs up clothing items that they like
* User can update their profile page with age, height, weight, gender, etc.
* Can browse clothing items from stores (just add links to stores for now)
* User can create lists of clothing- shoes, shirts etc. or style- summer, spring, etc.


**Optional Nice-to-have Stories**

* User Log off feature
* User can view other people profiles
* User can like others' clothing/favorite it or add it to their lists
* User can friend other profiles to have access to their likes/dislikes
* Users can post their outfits on the feed for everyone to see
* Users would apply for a spot to showcase their own clothing line.
* Users can also showcase their own clothing line on the app
* Users can receive directions to the store in which the item is stocked/available
* Settings page to edit what you can see on your stream
* Link to purchase page/shipping progress
* Advanced Search options

### 2. Screen Archetypes

* Login/Register Page
   * User can register via- email
   * User can login via- email or username
   * User can request a new password
* Stream
   * Photos of suggested clothing
   * List of stores you like that have recently added items
   * Clothing you have recently purchased
* Creation
    * User can post a new photo to their feed
    * User can share what they recently bought with others
    * Earn achievements 
* Detail
    * When you tap on a clothing item, more detailed information appears such as the price, the available sizes, the store that it is available at, etc.
    * When you like/favorite clothes more clothes will be suggested to you in your size. (maybe can change type that is suggested in settings)
* Profile
    * Users can view all of the clothes that they've liked.
    * Users can change height, age, etc.
    * Users can add a profile picture.
* Search
    * Users can search for other Users
    * Users can search for certain stores
    * Users can search for clothing by color
    * Users can search for clothing by type (shoes, tshirts, dresses, jewelry, etc.)
* Settings
    * Users can logout
    * Can change your location
    

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Log-in/Register screen
* Stream page 
* Profile page
* Settings

**Flow Navigation** (Screen to Screen)

* Login/Register Screen
    * => Home/Stream Page
* Stream Page
   * => None for now, but will later show listing information such as prices, sizes, etc.
   * ...
* 

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="https://github.com/acacia1021/Wireframes-for-Group-Project-1Size/blob/master/IMG_1462.jpg" width=600>


## Schema 
[This section will be completed in Unit 9]



### Models

Can also be found here: https://github.com/acacia1021/Wireframes-for-Group-Project-1Size/blob/master/Data%20Models%20File%20-%20Sheet1.pdf
[Add table of models]

	Property	Model	Description
Log in/Register Screen	loginTitle	String	Opening title welcoming user
	userName	String	user ID for logging in
	password	String	password for logging in
	logInButton	String	button for logging in
Home Screen/Search Page	searchBar	Relation to stores/images	Search button to look up stores
	suggestion	String	"You may also like…" part of suggestion in feed
	suggestionImage	File	Image shown in suggestion feed
	youLiked	String	Tells user they liked clothing from certain stores
Profile Page	profileImage	Pointer to User/File	image of user
	name	String	Profile name
	description	String	Description of user
	location	String	location of the user
	yourLikes	Pointer to likes/Relation to likes	shows list of your liked items
	height	String	height of user
	age	Number	age of user
	friends	Pointer to users/Relation to users	List of friends

### Networking
Can also be found here: https://github.com/acacia1021/Wireframes-for-Group-Project-1Size/blob/master/Outline%20Parse%20Network%20Requests%20File.docx
- [Add list of network requests by screen ]

- (READ/GET) username
- (READ/GET) password
[ ] (READ/GET) 
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
