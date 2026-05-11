---
layout: post
author: Jake Nurkin
title: Lab 6 -  Data Modeling
---
## User Stories

1. As a store owner, I can view and edit the item inventory, where each item has a name, price, description, quantity available, and a manufacturer
2. As a store owner, I can view a list of finalized orders made by customers, and for each order I can see the items ordered, the date and  time when the order was placed, the method of reaching the customer (delivery or pickup), and relevant account information of the customer. 
3. As a customer, I can visit the site and register an account, entering my name, address, and phone number.
4. As a customer, I can start orders for pickup or delivery and be able to select items for sale from the store to add to the order, including quantity, special instructions, and possible substitutes.
5. As a customer, I can checkout my order, putting in payment details, location, and time and date for the order to be fulfilled. 

## Entity Relationship Diagram

![Entity Relationship Diagram]({{ '/assets/erd.png' | relative_url }})

## SQL Schema

![SQL Schema]({{ '/assets/sql.png' | relative_url }})

## Reflection

The user stories were the easiest part to design, since the information was given pretty clearly through the assignment page. I had some minor experience with Lucidchart, so it was not too difficult and even enjoyable to create an entity diagram. It did take me a bit to get the hang of entity relations. The most difficult part was creating the schema in Redgate. The UI for Redgate is very busy and hard to understand for someone new to the program. I sitll have not gotten the hang of how relations work, as the implementation in Redgate is quite strange leading me to re-evaluate how I thought relations worked. By the time I had completed it, I felt satisfied with the model I created. I will implement the experience I gained from this assignment towards the schema in the final project.