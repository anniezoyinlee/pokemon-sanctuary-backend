# General Assembly - Project 3

## Project Name
PokeMon Sanctuary

## Scrum master
Trent Sanders

## Team Members
Annie Lee
Christina Whether
Safa Nasirli

## Project Description
Our team set out to make an E-commerce app for a Pokemon adoption agency. The app is intended for general populace consumption, catering to all ages.

## Models and Properties
User
```
name: {
    type: String,
    required: true
},
email: {
    type: String,
    required: true,
    unique: true
},
password: {
    type: String,
    required: true
}
```
Pokemon
```
name: {
    type: String,
    required: true
},
description: {
    type: String,
    required: true
},
price: {
    type: Number,
    required: true
},
image: {
    type: String,
    required: true
}
```

## Wireframe
Landing Page
![image](https://imgur.com/sM08Abg.png)
The Description page
![image](https://imgur.com/I1eGXF7.png)

## User Stories
As a User I want:
* The website to have the official pokemon colors
* The Landing page to have multiple card containers
* Each card has a unique pokemon
* Each card has an interactive link to the Description page

Landing Page includes:
* Multiple pokemon image ‘cards’,
* Each card is interactive
* Each card has CSS for animations
* Stretch: page navigation mark

The Description page includes :
* Reviews
* Pokemon Image
* Pokemon Bio/Desc
* Pokemon Price