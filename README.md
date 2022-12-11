# Exam-2022
Javascript Exam 2022

*Google Translate*

Task 1: 
Countries in America (25%)
In the attached HTML file for this assignment, there is an array of objects in the script for all the countries in the continent of America. Each object in the array is one country.
You will create a program that shows the following functionality:
1. Show all countries with full information. It is only necessary to show the "common name" of the countries and show only 1 of the flags of the country, the png or svg version.
2. Show all countries by "subregion"; see property "subregion" in the objects in the array. The user must write the name of "subregion" in the text field. It must be possible to write small and capital letters and also incomplete text. For example, it should be possible to write "Car" and you should get all countries that have "subregion" with the value "Caribbean". If the user does not enter anything, a message must be given that something must be entered.
3. Show how many inhabitants there are in total in America.
4. Show the country with the most inhabitants in America: must use for loop and if condition to find this.
5. Show the country with the fewest inhabitants in America: must use for-loop and if-condition to find this.
The screenshot below shows an example of what it might look like.

Task 2. Miaow Miaow meets the fish (25%)
In this task, you will create a small game/program where the user can move a cat (the cat's name is Miaow Miaow) by clicking on buttons, and create a dialogue by clicking on pictures.
Functionality:
1. Move the cat with the buttons: using element.style.left and element.style.top you can move the image of Miaow Miaow in all 4 directions (up, down, left, right). The cat must be moved 50 pixels per click.
2. If Miaow Miaow is in the fish's room, marked by the vertical line, the user can click on the fish and print a dialogue between Miaow Miaow and the fish. The vertical line marking the room is 600px from the left. The dialogue should be solved in the following way: you should have 1 array for the cat's question and 1 array for the fish's answer. Enter at least 5 questions and 5 answers. Every time the fish is clicked on, a random question from Miaow Miaow and a random answer from the fish must be selected and printed to the website.
3. If Miaow Miaow is not inside the room of the fish, i.e. has not reached 600px or more from the left, and clicks on the fish, it should be printed that the fish does not hear what Miaow Miaow is trying to say.
4. The fish don't like Miaow Miaow getting too close. If Miaow Miaow goes further than 700px then Miaow Miaow is teleported back to the starting position and a comment from the fish is printed about this.
5. Miaow Miaow cannot move further to the left than the left edge of the white space.

Task 3. Art Maker (25%)
In this assignment, there is some completed code that has been attached, but there are also some functions that have not been completed that you must finalize. You should only code in the empty functions!
A user enters width, height, background color and a word. When the user clicks on Add figure in array, the figure is not displayed on the website, but only in an array; see the function addFigureToArray which accepts 4 parameters.
It is only when the user clicks on the Show all artworks button that the figures are displayed.
Helper code (1 of several ways to solve it): This is a way to create a <div> that has width, height and background color. It can be added to the page with JavaScript. The values, for example 100px, must be dynamic in the task.
<div style="width: 100px; height: 100px; background-color: red;"></div>

Task4. Online banking: You must code 3 of the following 4 points:
a. Creating accounts (for example current account, savings account and salary account)
b. Move money between accounts
c. Change the account afterwards (change name, color?)
d. Pay bill. You must enter a password to be allowed to pay.

**All code must be your/their own. Copying and copying other people's codes, for example from the internet or from fellow students, is illegal, i.e. considered plagiarism. The entire group is responsible for following this rule.**
