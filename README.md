# UFOs

## Overview of Project

### Purpose
The purpose of this analysis was to create a dynamic webpage using JavaScript, that filters data results based on user input.

## Results
To use the webpage, enter a search criteria into any one of the filter boxes and press 'enter'. The rows on the right will filter accordingly.

![Single Filter](https://github.com/Nveatch/UFOs/blob/main/static/images/search1.png)

To further refine the data, multiple filters may be used.

![Multiple Filters](https://github.com/Nveatch/UFOs/blob/main/static/images/search2.png)

## Summary

### Drawbacks
One drawback of this new design is that due to the removal of the 'filter' button, it isn't obvious how to filter the data. For instance, if i typed a search criteria, i would expect the data the filter accordingly, even though it might not have filtered at all due to not pressing 'enter' or clicking away.

### Improvement Recommendations
A few things could be added to the page to make it more user friendly:

1. An adaptive duration filter, that could respond to both exact durations (ex. '6 minutes') and ranges (ex. '< 30 minutes' or '< 30 minutes & > 5 minutes')

2. A string above the table that says what the data is currently being filtered by (ex. " Table currently filtered by City = 'benton' and State = 'ar' ")

3. Next to that string, a button that clears all filters and returns the data to its unfiltered form

