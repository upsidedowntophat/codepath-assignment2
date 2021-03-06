## Yelp

This is a Yelp search app using the [Yelp API](http://developer.rottentomatoes.com/docs/read/JSON).

Time spent: `15hrs`

### Features

#### Required

- [x] Search results page
   - [x] Table rows should be dynamic height according to the content height
   - [ ] Custom cells should have the proper Auto Layout constraints (turned it off because it was breaking my infinite scroll)
   - [x] Search bar should be in the navigation bar (doesn't have to expand to show location like the real Yelp app does).
- [x] Filter page. Unfortunately, not all the filters are supported in the Yelp API.
   - [x] The filters you should actually have are: category, sort (best match, distance, highest rated), radius (meters), deals (on/off).
   - [x] The filters table should be organized into sections as in the mock.
   - [x] You can use the default UISwitch for on/off states. Optional: implement a custom switch
   - [x] Clicking on the "Search" button should dismiss the filters page and trigger the search w/ the new filter settings.
   - [ ] Display some of the available Yelp categories (choose any 3-4 that you want).  (Assignment wasn't clear about what was required with categories.  Choosing 3-4 would be the same setup as the other sections.  I thought I'd learn more from doing infinite scroll and the map view)

#### Optional

- [x] Search results page
   - [x] Infinite scroll for restaurant results
   - [x] Implement map view of restaurant results
- [ ] Filter page
   - [ ] Radius filter should expand as in the real Yelp app
   - [ ] Categories should show a subset of the full list with a "See All" row to expand. Category list is here: http://www.yelp.com/developers/documentation/category_list (Links to an external site.)
- [ ] Implement the restaurant detail page.

### Walkthrough

![Video Walkthrough](codepath-assignment2.gif)
