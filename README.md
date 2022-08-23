# UFOs

### Overview of Project
The webpage at first included a table of UFO sightings with the ability for the user to initially filter by date. The challenge was to use Javascript and HTML to modify the code to make it possible for users to filter the table by four additional options (city, state, country, and shape).

#### Results
The new webpage now looks like this:

![image](https://user-images.githubusercontent.com/107162310/186045474-7580e4cb-5eba-45fa-8268-b74a9121da4f.png)

Users are able to filter by any or multiple of the options shown. Simply type into the input box (in the same style as the placeholder) whatever filters you'd like to apply, then press Enter. And the table will quickly display on the results that match your chosen filters.

For instance, here's a screenshot of a search for a certain date, prior to hitting Enter:

![image](https://user-images.githubusercontent.com/107162310/186045701-c0ad7396-efb3-4f4e-b837-e18e64a93830.png)

You can see that other results not from that date are visible. Once I hit enter, however:

![image](https://user-images.githubusercontent.com/107162310/186045749-8c345c0d-68df-4673-a163-8da5ec94e41c.png)

Now the table is only displaying sightings from the date chosen.

And while that initial filter is already entered and operating, I've added another filter in this screenshot and hit Enter:

![image](https://user-images.githubusercontent.com/107162310/186045853-41bfd108-4f27-4564-aaac-615d81bd8470.png)

To clear a filter, the user must delete the input box(es) and then either press enter or click the cursor anywhere on the webpage that is not within an input box. The table will then reset.

#### Summary
The website works as requested however there is room for improvement. One notable drawback is that the filtering feature is not friendly towards those with a more casual interest in UFOs. If someone doesn't know an exact date to search for that already has a sighting in the database, the table will display no results even if they're only off by as little as one day. Likewise, if they have a typo in a city, state, or country, or if their input doesn't exactly match the style of the placeholder (and that includes any extra spaces they may accidentally include).

So, here are two recommendations to improve the user experience/interface:

1. Update the date filter to allow for a range of dates rather than a single date, or the ability to search only by a year and/or a month and a year.

2. Loosen the input requirements so that they're not case-sensitive and to allow for extra whitespace from the user.
