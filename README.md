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
- One drawback of this design is that you have to follow strictly the format that is shown in the search box for your inputs so it would throw errors if you missplled your input or didn't pay attention to case sensitivity. Thus, I recommend replacing the text boxes with drop-down menus that include all filter values to be selected.

- Another recommendation is to add a “Filter” button below the search boxes by clicking on which the search runs.

- Here we have to clear search boxes manually to start a new search, so I would highly recommend adding a “Clear” button that automatically resets value of search boxes.
