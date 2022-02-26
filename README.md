# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED
- [x] User can tap a cell to see more details about a particular movie
- [x] User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView

### App Walkthough GIF

<img src="http://g.recordit.co/mI2FbPCDSp.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app:

- When creating the collection view grid, the poster view images weren't displaying correctly, this was fixed with collectionViewLayout. 

---

## Flix Part 1

### User Stories

#### REQUIRED 
- [x] User sees an app icon on the home screen and a styled launch screen
- [x] User can view and scroll through a list of movies now playing in theaters
- [x] User can view the movie poster image for each movie

#### BONUS
- [x] Run your app on a real device.

### Notes
Describe any challenges encountered while building the app:

- When copying the base URL from configuration, I copied the "base_url" instead of the "secure_base_url", this prevented me from viewing the poster image for each movie.
