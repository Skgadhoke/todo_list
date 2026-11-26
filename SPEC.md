What it is

This is a simple Todo List app that will allow a person to create a list of Todos compiled however they see fit. I can have a exercise Todo which will be a list of exercises for my planned workout today or it can be something like todo for a grocery list

Data
Todo1: [item1, item2]
Todo2: [item1, item2]

I should be able to add, delete, edit any item within the Todo. And I should be able to add, delete, and edit the Todo itself.

For example Todo1 could be renamed to Todo3 or Todo1 can only contain item1 or item1 can get renamed to item4

The Todo’s themselves have to be unique, so I cannot have Todo1 and Todo1, and the items in each Todo must be unique however I can have the same item cross Todos.

For example Todo1 and Todo2 both can include item1, however Todo1 cannot have item1 and item1


Must do

V1 scope: the user can add their respective Todos in a browser on their own machine. The app runs locally (npm run dev), and each browser keeps its own list. Seeing the same Todos across desktop, iPhone and iPad is planned for V2.

How to check if it works
I should be able to create, delete, or edit as many Todos
I should be able to create, delete, or edit as many items in the Todos 
I should be able to view my todos again after reloading the page in the same browser

Not Building (out of scope)
Todos are not shared to anyone
Todos are not exported to pdf
Todos cannot be modified by anyone
V1 only: no login or accounts, no sync across devices, no hosting or deployment (planned for V2)

Tech constraints: 
V1: Vite + React + TypeScript frontend, data saved in browser localStorage, no backend or database. V2 may add Supabase for login and sync across devices.