# Movie-Flix


API Call Information -
Now playing API - 
https://api.themoviedb.org/3/movie/now_playing?api_key=a07e22bc18f5cb106bfe4cc1f83ad8ed
Documentation -
https://developers.themoviedb.org/3/movies/get-now-playing
Trailers API -
https://api.themoviedb.org/3/movie/209112/videos?api_key=a07e22bc18f5cb106bfe4cc1f83ad8ed

- The movie poster is available by appending the returned poster_path to https://image.tmdb.org/t/p/w342.Here 342 is the image width.

- The backdrop is available by appending the returned backdrop_path to https://image.tmdb.org/t/p/original

Application Requirements
- User should be able to see a list of Now Playing movies in list
- For popular movies - more than 7 votes, a full backdrop image is displayed. You don’t need to play the trailer (refer the gif above)
- For unpopular movies, a poster image, the movie title, and overview is listed. (refer the gif above)
- Use different UICollectionViewCells for popular and unpopular movies
- The images fetched from the url must be cached locally so the movies load faster the next time the app is run. Do not use any pod/library for caching.
- There should be a search bar at the top that will filter locally fetched movies
- Clicking on any movie cell should launch a details screen, the screen should just show the movie poster in full screen
- The user should be able to delete any cell (either add a delete button on the cell or use swipe to delete action). Use batch updates.
- Deployment target can be iOS 12, android 4.4 and above
