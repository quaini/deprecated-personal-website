---
layout: project
title: "Farmer's Market"
date: 2019-12-6
categories: projects school
permalink: /:categories/:title
description: Final project for Database Design. Simulated farmer’s market with MySQL database and Java Swing UI.
stack: MySQL, Java, Java JDBC, Java Swing
source: farmers-market
sourceurl: "https://github.com/GuilledelAguila/farmersmarket"
picture: /assets/quaini/img/farmers-market-uml.jpeg
---

As a final group project for Northeastern's CS3200: Database Design, my team and I created a simulated farmer's market where buyers, sellers, and farmers conduct their business. The goal of this project was to flesh out our understanding of database structure, design, and connectivity. Above is the Unified Modeling Language (UML) design of our project. I've also attached the Enhanced Entity Relationship (EER) model below for reference.

We built this project using a MySQL database and Java Swing UI. To connect our UI and database, we used the Java API, [Java Database Connectivity (JDBC)](https://docs.oracle.com/javase/tutorial/jdbc/overview/index.html).

The design of the project is centered around the needs of the farmer's market's users. In our simulation, there are three types of users: Buyers, who consume the produce, Sellers, who trade the goods, and Farmers, who provide the produce. In our market: 

Buyers can 
1. View Shopping History
2. View Available Goods
3. Buy Goods
3. Filter Goods by Category
4. Read Reviews
6. Write Reviews.

Sellers can
1. View Catalog of Produce
2. Partner with Farms
3. Make Postings
4. View their Selling History

Farmers can
1. Add Produce
2. View Posted Produce
3. See Reviews
	

Instructions on how to install and run the project can be found in the source code linked above.

EER Model:

<img src="/assets/quaini/img/farmers-market-eer.png" class="img-thumbnail"/>
