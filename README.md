pond
========

Tracking Twitter ripples on Google Maps.

Here's what I want this to do:

* On loading:
  * Open Google Maps zoomed out to world view.
  * Buttons for 'Load Pointfile', 'Search Keywords', 'Search Rectangle', 'Listen', 'Reset Map'.
    * Load Pointfile prompts user to select a file - either JSON or text containing lat/long sets. After loading the file, a heatmap is displayed showing geographical distribution of tweets. Map center is zoomed and centered based on average lat/long in set.
    * Search Keywords allows user to enter a list of terms to monitor.
    * Search Rectangle creates a draggable, stretchable rectangle map overlay. The user moves it to fit the location they want to monitor for tweets.
    * Reset Map clears all monitoring options and returns to the initial world overview.
  * Once search options are selected, user clicks a 'Listen' button.
  * Any tweets that are created that match the given search criteria are added to map, either as part of heatmap or as markers. If markers, hovering over one should give text of tweet (and additional info?).
