# UFOs

## Overview of the analysis :

In this module, we focused on building a dynamic webpage by inserting JavaScript into an HTML page and also we used CSS and Bootstrap to style the entire page.
We started by building a table to store and neatly display the data we want to work with. Then we added filters for multiple criteria (date, city, state, country, and shape ) to let users search on more than one level.

### UFO Sightings webpage : https://tjavaheripour.github.io/UFOs/

## Results
The webpage has a banner on the top, an article summary in the middle, and a table summarizing UFO Sightings to grab attention. The user can re-initialize the page by clicking on UFO Sightings on the top-left corner in the navigation bar.

### Deafult page
![Default.PNG](https://github.com/tjavaheripour/UFOs/blob/main/screenshots/Default.PNG)

As you can see, there are a table with information about the UFO Sightings and a Filter Search with 5 criteria (date, city, state, country, and shape) which enable you to filter the table. You can filter by one option or multiple and the table will return any results matching those values.
Note that the text boxes show sample inputs on how to fill them.
For example, the image below shows how the table summary would look like once the following filters have been applied :
- Date: 1/1/2010
- State: ca
- Shape: light 

### Filtered table
![filtered.png](https://github.com/tjavaheripour/UFOs/blob/main/screenshots/filtered.png)

## Summary
- One drawback of this design is that you have to follow just the format that shown in the search box so it could cause errors due to misspelling or don’t pay attention to case sensitivity so I recommend drop-down menu including all filter values, instead of input fields so user can select the data instead of typing

- Another recommendation is to add “Filter” button below search boxes that user click on this button after filling search boxes instead of push Enter.

- Here we have to clear search boxes manually to start new search, so I would highly recommend add “Clear” button that automatically clean inputs of search boxes.
