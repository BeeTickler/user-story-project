# Unit 2 - Data for Social Good Project

## Introduction

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need.

## Requirements

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program:
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors.
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about.
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs.
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset).
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions.

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

“As a terraria enthusiast, I want to observe the data its game weapons to find the best in certain categories in order to gain a better advantage over its difficulty.”

## Dataset 

Include a hyperlink to the source of your dataset used for this project. Additionally, provide a short description of each column used from the dataset, and the data type. 

Example: 
weaponNames	Stores the name of each weapon (e.g., Sword, Bow, Staff).	String
damageStrings	Stores the damage value of each weapon as a string (e.g., "25").	String
damageTypes	Stores the type of damage for each weapon (Melee, Ranged, Magic, Summon).	String
useTimeStrings	Stores the time it takes to use or attack with the weapon, as a string (e.g., "1").	String

Dataset: reorganized Terraria wiki page - https://terraria.fandom.com/wiki/List_of_weapons

## UML Diagram 

Put an image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get displayed on this README. 

<img width="1536" height="1024" alt="UML User Story" src="https://github.com/user-attachments/assets/374e1868-4aa6-41b9-8f7e-0f7a182e3a2f" />


## Description 

For this project, I created a UserStory application that analyzes a dataset of weapons and allows users to interactively identify the most effective weapon for a specific damage type. The dataset is organized into arrays storing weapon names, damage values, damage types, and use times, which were loaded from four text files using the FileReader helper class. By using the Scanner class, the program provides a user interface where the user can input a preferred damage type—such as Melee, Ranged, Magic, or Summon—and the program will calculate the best weapon by iterating through the arrays and comparing numerical values of damage.

The UserStory class encapsulates all weapon data and provides methods like bestWeaponIndex to determine the weapon with the highest damage for a given type, demonstrating concepts such as loops, conditional statements, and string manipulation. The program also uses a toString method to summarize the dataset, giving the user a quick overview of the available weapons. By combining data storage, user input, and algorithmic decision-making, this project addresses the user’s goal of efficiently selecting the optimal weapon from a structured dataset.
