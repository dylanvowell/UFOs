# OVERVIEW
There are a ton of UFO sightings all over the United States each year. This project is a way to aggregate many of those sightings in one place and allow users to easily filter by a few different data points to narrow down specific sightings. 
# RESULTS
A user can visit the site to see all of the listed UFO sightings. If needed, a user can also filter sightings by a number of criteria: 
![no filter](https://github.com/dylanvowell/UFOs/blob/main/static/images/no_filter.png?raw=true)

Now, adding some filters: 
![yes filter](https://github.com/dylanvowell/UFOs/blob/main/static/images/yes_filter.png?raw=true)

The results are immediately filtered upon entering search criteria. 

# SUMMARY
One drawback to this design is the lack of a button to finalize your search filters. The current method is a bit clunky and can often return 0 results before you've had a chance to correct any typos. I would add a button that initializes the filters, as well as replace the strict matching (===) with a looser matching (==) in case city names are misspelled. 
