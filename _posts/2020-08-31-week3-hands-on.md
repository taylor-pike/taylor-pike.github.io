---
title: Week 3 Hands-on
author:
  name: Taylor Pike
  url: https://taylor-pike.github.io/2020/08/31/week3-reflection.html
categories:
- hands on
---

For the Card Picker, I think a list of dictionaries is used.
The list contains 4 items (James Stuart - Training Manager, Isaac Pullman - Creative Director, Sarah Oscar - Sales Rep, Srinivas Tamada - Tech Lead).
Within each item in this list is a dictionary of four keys (phone number, home town, main role, photo).
The phone number is a number scalar.
The home town is a text scalar.
The main role is a longer text scalar.
The photo is a blob.
I think this is an effective visualization. It makes it easy to see the information of each employee without getting mixed up with the others.
To do less clicking, you could simply have a table or page where all the information is shown without having to press each person.
But I think this way allows you to have interaction with each member.

For The Demographics of Others, interactive square pie charts are used.
The user can interact with them by choosing the different demographics that are being analyzed.
As a dictionary, these demographics include three keys (sex, age group, race or origin).
All of these keys are text scalars.
Depending on which of these demographics are chosen, the list of square pie charts change how full they are.
This list includes 11 items (married, own children in household, has healtcare coverage, bachelor's degree or more, employed, self-employed, primarily pub. transit to work, personal income above nat. med., below poverty line, veteran, born outside US, cog. or phys. difficulty, hearing or vis. difficulty, widowed).
The combinations of the keys in the dictionary determine how full each of the square pie charts in the list will be.
For example, if the keys are selected like this (female, 18 to 24, white), the item in the list (employed) is filled with 63/100 squares, meaning approximately 63% of people in these categories are employed.
Once this visualization is understood, it is a good way to represent this data.
But since I wasn't sure what a square pie chart was before seeing this, I was a little confused at first.
It might have made more sense if it was just normal pie charts with their percentages written on it or to the side.
But once the parameters are understood, this becomes a good visualization for the data.

The final visualization is very interesting. 
It is the "Based on a True Story" visualization.
It contains a list of movies (items).
Once you click a movie, another list is found, an ordered list of each scene of the movie.
Within each scene, you find a dictionary with three keys: movie description, reality description and color.
These first two keys are text scalars.
The color key I assume is a blob which is determined by a boolean of sorts with, instead of just a true or false, has true, trueish, falseish, false and unknown.
I believe this is a fantastic visualization.
By using so many descriptions and colors for each scene, the in depth research used to create the visualization is made clear.
More than enough information is given and it allows a user to look for the specific information they desire to find easier (by clicking into the section that interests them).


Post
