# Campground Explorer Pt. 3

Submitted by: Isaac Livingston

Campground Explorer Pt. 3 is an Android app that combines the Parks app and Campground Explorer app into one application. Users can switch between a list of National Parks and a list of campgrounds using Bottom Navigation.

Time spent: about 5.5 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] Added Bottom Navigation to the application
- [x] Added a Parks navigation item
- [x] Added a Campgrounds navigation item
- [x] Created and used a ParksFragment
- [x] Used the existing CampgroundFragment
- [x] Dynamically displays fragments inside MainActivity
- [x] User can switch between Parks and Campgrounds using the bottom navigation
- [x] Parks data is displayed in a RecyclerView
- [x] Campground data is displayed in a RecyclerView
- [x] Added custom icons for Parks and Campgrounds
- [x] Set Parks as the default tab when the app opens

## Optional Features

The following **optional/stretch** features are implemented:

- [ ] Settings screen
- [ ] Custom Home screen
- [ ] Orientation changes without resetting the application

## Additional Features

The following **additional** features are implemented:

- [x] Uses the National Park Service API
- [x] Uses fragments to organize separate screens
- [x] Uses a FrameLayout as the fragment container
- [x] Uses a custom park icon for the Parks tab
- [x] Uses a custom camping icon for the Campgrounds tab
- [x] Uses Kotlin Serialization for API data
- [x] API key is stored in `apikey.properties`
- [x] API key is kept out of the GitHub repository

## Video Walkthrough

Here's a walkthrough of the implemented features:

[ (https://drive.google.com/file/d/1yIFyxkQfcu9WAkDqYNRLipqD-XBbORvz/view?usp=sharing) ]

## Notes

One challenge was setting up the API key and getting the project to sync correctly.

Another challenge was moving the Parks code from MainActivity into ParksFragment and making sure the RecyclerView continued to work.

The Bottom Navigation was then connected to MainActivity so that selecting Parks or Campgrounds swaps between the correct fragments.

Custom vector icons were also added for both navigation items.

## License

Copyright 2026 Isaac Livingston

Licensed under the Apache License, Version 2.0.
