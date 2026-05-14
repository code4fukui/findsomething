# findsomething

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)


![findsomething demo](findsomething.jpg)


A web application that uses Japan's Open Data Platform (ODP) to search for and map nearby points of interest, such as emergency shelters, AEDs, and public facilities.

## Demo

**https://taisukef.github.io/findsomething/**

## Features

-   Automatically detects the user's location to display nearby points of interest.
-   Supports multiple languages: Japanese, English, Chinese, Korean, German, Catalan, Portuguese, Tagalog, and Persian.
-   Displays various types of points of interest with unique icons:
    -   Civic Facilities
    -   Emergency Shelters
    -   Farmers Markets
    -   AED Locations
    -   Public Toilets
    -   Fire Hydrants
    -   Medical Institutions
-   Calculates and displays the nearest points of interest first.

## Setup

To run this project locally, you will need a Google Maps API key.

1.  Clone this repository to your local machine.
2.  Obtain a Google Maps API key from the [Google Cloud Console](https://console.developers.google.com/projectselector/apis/credentials).
3.  Open the `lib/gmap.js` file and replace the placeholder value of `API_KEY` with your own key.
4.  Open `index.html` in a modern web browser.

## Data Sources

-   **Data:** [Open Data Platform (ODP) SPARQL API](https://sparql.odp.jig.jp/data/sparql)
-   **Mapping:** Google Maps JavaScript API

## Credits

This project was created by [Taisuke Fukuno](http://fukuno.jig.jp/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.