# Pokédex App
### Pokedex

This is a single-page web application that fetches and displays information about Pokemon from the PokeAPI. It allows users to browse and filter through a list of Pokemon based on their types. The project has been bundled using WebPack.
<br>
##### Hosted (**[Link](https://pokebodex.netlify.app)**)
##### Video (**[Link](https://youtu.be/sbvp--K2mAM)**)

<br>

	 Author: Ebod Shojaei
	 Version: 1.0

<br>

## Features
- **Fetching Pokemon**: 
    > - The app fetches a list of Pokemon objects from the PokeAPI, containing the names and URLs of the Pokemon.
- **Fetching Pokemon Types**: 
    > - The app fetches a list of Pokemon types from the PokeAPI, containing the names and URLs of the types.
- **Caching Pokemon Data**: 
    > - The app caches the response data for each Pokemon to reduce the number of API requests.
- **Pagination**: 
    > - The app displays the Pokemon cards in a paginated manner, with a fixed number of cards per page (default is 10). 
	> - Users can navigate between pages to view different sets of Pokemon.
- **Filtering by Type**: 
    > - The app provides checkboxes for each Pokemon type. 
	> - Users can select one or multiple types to filter the displayed Pokemon. 
	> - The app dynamically updates the displayed Pokemon based on the selected types.
- **Pokemon Details Modal**: 
    > - The app shows a modal with detailed information about each Pokemon. 
	> - Clicking the "Details" button on a Pokemon card opens the modal, displaying the Pokemon's ID, image, abilities, stats, and types.
- **Responsive Design**: 
    > - The app is designed to be responsive and work well on different devices and screen sizes.

<br>

## Requirements
- The app requires the following dependencies:
    > - **axios**: A promise-based HTTP client for making API requests.
    > - **jquery**: A JavaScript library for DOM manipulation and event handling.
    > - **bootstrap**: A popular CSS framework for styling the app.
    > - **popper.js**: A library required by Bootstrap for handling dropdowns, tooltips, and popovers.

- The app also uses custom CSS and HTML files for styling and structure.

<br>

## Usage
To use the app on your local machine, follow these steps:
- **Clone** the repository to your local machine.
- **Open** the index.html file with a live server.
	> - The app will automatically fetch the Pokemon data from the PokeAPI and display the Pokemon cards.
- **Use** the checkboxes to filter the Pokemon by type.
- **Use** the pagination buttons to navigate between different pages of Pokemon.
- **Click** the "Details" button on a Pokemon card to view its detailed information in a modal.

**Note**: Internet access is required to fetch data from the PokeAPI.

<br>

Enjoy exploring the world of Pokemon!

<br>

## Resources
- **[COMP2530-s23-A3-Sample-Code](https://github.com/nabil828/COMP2530-s23-A3-Sample-Code)** by nabil828
	- Used for setup
<br>

- **[ChatGPT-4](https://chat.openai.com/)** by OpenAI
	- Used for debugging

<br>
