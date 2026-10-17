# CineMagicHub

A static movie-channel landing page I built in 2023 while learning HTML, CSS and Bootstrap. It's a front-end only project: no backend, no JavaScript of my own, just layout and styling.

## What's on the page

- **Navbar** with the CineMagicHub logo, a Movies dropdown (2023 / 2022 / 2021), About Us, a search box and a Guest menu (Log In / Sign Up)
- **Featured movie** section for *Avengers: Endgame* with a poster, *Watch Now* and *Download* buttons, and a grid of the heroes (Captain America, Iron Man, Thor, Hulk, Black Widow, Hawkeye)
- **Popular Movies** row of posters that lift on hover
- Responsive layout: the heroes grid is hidden on screens 768px and narrower

All links and buttons are placeholders (`href="#"`); search, login and playback aren't implemented.

## Built with

- HTML5 and CSS3
- [Bootstrap 4.0](https://getbootstrap.com/docs/4.0/) (loaded from CDN, with jQuery and Popper for the dropdowns)
- [Font Awesome](https://fontawesome.com/) icons
- [Protest Riot](https://fonts.google.com/specimen/Protest+Riot) from Google Fonts

## Project structure

```
css/style.css            custom styles
html/movie channel.html  the page
image/                   logo, background and movie/hero posters
```

## Running it

No build step. Clone the repo and open `html/movie channel.html` in a browser. An internet connection is needed for the CDN-hosted Bootstrap, Font Awesome and Google Fonts.

## Note

Movie posters and character images belong to their respective studios and are used here for learning purposes only.
