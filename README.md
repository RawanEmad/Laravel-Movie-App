## Laravel Movie App

A simple Laravel Movie App uses [the movie database API](https://www.themoviedb.org/) that helps user to discover movies. 
<br></br>

## Screenshots

![movies](https://user-images.githubusercontent.com/49768271/135720723-9ca848e1-27b5-4de6-8950-cdeef644285d.PNG)
![tvshows](https://user-images.githubusercontent.com/49768271/135720740-144d5adc-b28b-4331-b63c-8afff5d7400f.PNG)
![actors](https://user-images.githubusercontent.com/49768271/135720675-d06a2614-9cf9-4edb-8874-450119f6c75f.PNG)
![movie](https://user-images.githubusercontent.com/49768271/135720690-d32e7c0c-b8f5-4686-bf47-b8cc579589b2.PNG)
![movie2](https://user-images.githubusercontent.com/49768271/135720696-af336af8-04bc-4f65-86bb-f8c7a11efcd7.PNG)
![actor](https://user-images.githubusercontent.com/49768271/135720670-eaf564e4-50be-4f28-8c3e-5b2a5a85c14b.PNG)

---

## Features

- Discover the most popular and now playing movies
- Discover the most popular and the top rated tv shows
- Watch movie and tv show trailers, cast and images
- Read movie and tv show description
- Discover the most popular actors
- See actor biography and known for 
- Search for movies, tv shows and actors
- UI optimized for pc and phone
---

## Installation
1. Clone the repo and `cd` into it
2. `composer install`
3. Rename or copy `.env.example` file to `.env`
4. Set your `TMDB_TOKEN` in your `.env` file. You can get an API key [here](https://www.themoviedb.org/documentation/api). Make sure to use the "API Read Access Token (v4 auth)" from the TMDb dashboard.
5. `php artisan key:generate`
6. `php artisan serve` 
7. Visit `localhost:8000` in your browser
