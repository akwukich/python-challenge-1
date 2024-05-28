# Interactive Ordering System for a Food Truck


## Introduction


This interactive ordering system is designed to allow customers to place an order at a food truck. Using the code, a user can place an order and receive a printed, itemized, and totaled receipt.


## Instructions


1. The user is welcomed and prompted to place an order, which begins a continuous loop.


2. The user is prompted to select a menu category by typing in the corresponding menu category number and then an item from the specified menu. An example of a user choosing a single cookie from the snack menu would result in an output like this:


(![alt text](https://drive.google.com/file/d/1_yPxR5NEiXBHr10XdfM_o7L0odyvRTjH/view?usp=drive_link))


3. After selecting an item and specifying the quantity, the user is prompted to either continue ordering or complete their order. Continuing the order results in the continuation of the loop, and the user is brought back to the menu categories to add items to their order.


4. When the user has completed their order, the loop will end, and a printout will be generated of the items ordered, their corresponding prices and quantities, as well as an overall total:


(![alt text](https://drive.google.com/file/d/1WUzS5_S7yKI-VTkWCY5DbgvUayUYn3nC/view?usp=drive_link))


## Resources


This code was adapted from [Module 2 Challenge Files](https://static.bc-edx.com/ai/ail-v-1-0/m2/lms/starter/M2_Starter_Code.zip). I was able to reference and adapt this code to develop the “Place Order” Loop. The “Keep Ordering Loop” and Order Printing/Totaling were the most challenging and I needed to consult in-class notes, demonstrations and activities.


In developing the "Keep Ordering Loop," I referenced several in-class demonstrations and activities, including" Loops" and "Loop de Loop."


I attempted to use a match case to check the user's input for the "Keep Ordering Loop." The "match" function, as adapted from the instructor demonstration, was unavailable on my version of Python, so I used an if-elif-else statement, adapted from the “Rock, Paper, Scissors” warm-up.


The most time-consuming part for me was looping through the order and formatting the items, prices, and quantities (and their respective spacing). I consulted and adapted the "Printing a Menu" activity, the “List Comprehensions” instructor demo, and the "Guest List" activity.

