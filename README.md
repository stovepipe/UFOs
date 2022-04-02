# UFOs
Using JavaScript to build a table to display data using multiple filters. Final table will be embedded in an organized web page using html.

## Project Overview
The purpose of this project was to build a dynamic webpage that can format and display data with user inputs resulting in a filtered table of UFO Sightings. The table defaults to display all of the UFO Sightings data. A user can then filter the UFO Sightings data by date, city, state, country and shape. The filters may be combined to further narrow down the results.\

The table can be reset by clicking the "UFO Sightings" button in the upper left corner of the page.

## Results
This is the landing screen. Notice the full table of UFO Sightings data. The "UFO Sightings" button in the upper left of the screen will bring the user back to this landing screen when clicked.
![ufo_1.png](https://github.com/stovepipe/UFOs/blob/main/static/images/ufo_1.png)

When a user enters a date, the change is detected automatically and the table is filtered accordingly.
![ufo_2.png](https://github.com/stovepipe/UFOs/blob/main/static/images/ufo_2.png)

The user can then enter a city and state to further filter the data.
![ufo_3.png](https://github.com/stovepipe/UFOs/blob/main/static/images/ufo_3.png)

There is even an option to filter the UFO Sightings by country and shape of the UFO.
![ufo_4.png](https://github.com/stovepipe/UFOs/blob/main/static/images/ufo_4.png)

## Summary

### Limitations
One limitation with this filter is that there is not a way to remove a single filter without needing to reset the entire table. During the analysis, this could be a challenging barrier to exploring the entire dataset in an efficient way.

### Future Recommendations
- Each filter could include a button to remove the filter, allowing more flexibility to data manipulation.
- Rather than having text boxes with user input, each filter could include a dropdown list of available filter criteria. This would minimize errors and further increase the efficiency of analysis performed using this interface.