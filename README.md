# UFOs

## Project Overview:
The core of this project was to build a dynamic webpage that filters a large table of data based on user input. The purpose of the site is to aggregate and display data regarding sightings of UFOs.

## Resources:
Source Data:[data.js](https://github.com/Jflux05/UFOs/blob/07439a271a592583cd5fb76aa52fedfdfefd2579/static/js/data.js)
Software: JavaScript, Visual Studio Code v1.63.2, BootStrap 4, HTML, CSS

## Results: 
The webpage (Needs link)UFO Sightings - The Truth is Out There has been created. Upon entering, visitors embarking on their "first encounter" will see:
![UFO's landing page.png](https://github.com/Jflux05/UFOs/blob/2d6405ccfa08f37daece2963fbb7904ea40359f8/Resources/UFO's%20landing%20page.png)



You will notice that a "Filter Search" section has been added.

![UFOs landing page search filter.png](https://github.com/Jflux05/UFOs/blob/2d6405ccfa08f37daece2963fbb7904ea40359f8/Resources/UFOs%20landing%20page%20search%20filter.png)


You can filter by one or all of the search criteria shown. For example, if you search by "City", you will see that the table updated to show the reported sightings that was recorded for that specific city.
![UFOs search by city.png](https://github.com/Jflux05/UFOs/blob/2d6405ccfa08f37daece2963fbb7904ea40359f8/Resources/UFOs%20search%20by%20city.png)


If you add a shape, the table will update filtering further to only display the information containing that shape.
![UFOs search by city and shape.png](https://github.com/Jflux05/UFOs/blob/2d6405ccfa08f37daece2963fbb7904ea40359f8/Resources/UFOs%20search%20by%20city%20and%20shape.png)


## Summary

Unfortunately, the webpage has a few drawbacks which include:

- There is no button to click, wording or action that tells the user that the table will update after you hit "enter".

- The data is limited and outdated since it is not linked to a "live" source.

- The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown.



### Recommendations for further development:

- Add functionality to pull the data from a live source that includes current and archived data not limited to only the United States, but globally.

- Add additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help "guide" the user and make the page more interactive.

- Add a "Latest News" section that will highlight an article showing the most recent reported sighting.
