pond
========

Tracking Twitter ripples on Google Maps. Can load a file of tweets with coordinates and map as either markers or a heatmap. Can also track live collection, specifying keywords and populating map with markers from tweets in realtime.

![pond2](https://cloud.githubusercontent.com/assets/1410310/15050579/78322cee-12a9-11e6-962a-f8069d9096f2.jpg)

![pond1](https://cloud.githubusercontent.com/assets/1410310/15050580/784a0f30-12a9-11e6-85d6-9560d9ec5edc.jpg)

* On loading:
  * Open Google Maps zoomed out to world view.
  * Buttons for 'Load Pointfile', 'Search Keywords', 'Search Rectangle', 'Listen', 'Reset Map'.
    * Load Pointfile prompts user to select a file - either JSON or text containing lat/long sets. After loading the file, a heatmap is displayed showing geographical distribution of tweets. Map center is zoomed and centered based on average lat/long in set.
    * Search Keywords allows user to enter a list of terms to monitor.
    * Search Rectangle creates a draggable, stretchable rectangle map overlay. The user moves it to fit the location they want to monitor for tweets.
    * Reset Map clears all monitoring options and returns to the initial world overview.
  * Once search options are selected, user clicks a 'Listen' button.
  * Any tweets that are created that match the given search criteria are added to map, either as part of heatmap or as markers. If markers, hovering over one should give text of tweet (and additional info?).
