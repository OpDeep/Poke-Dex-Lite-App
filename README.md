
# Pokedex Lite

A simple web application that allows users to explore a list of Pokémon, search for specific Pokémon by name, filter by type, paginate the list, and mark favorites. Built with **React**, **TypeScript**, and **PokéAPI**.

## Features

- **List Pokémon**: Fetch Pokémon from the [PokéAPI](https://pokeapi.co/) and display them in a grid.
- **Search by Name**: Search for Pokémon by their name as you type.
- **Filter by Type**: Filter the displayed Pokémon by their type (e.g., Fire, Water, Grass).
- **Pagination**: Paginate the list of Pokémon with a mechanism to load more results.
- **Favorites**: Mark Pokémon as favorites and persist them in local storage.
- **Detailed View**: View detailed stats for each Pokémon (e.g., HP, attack, abilities).
- **Fully Responsive**: The UI is responsive and works across mobile, tablet, and desktop screens.

## Technologies Used

- **React** - Frontend framework
- **TypeScript** - Static typing for JavaScript
- **PokéAPI** - API to fetch Pokémon data
- **CSS** - Styles for UI components
- **web-vitals** - For reporting performance metrics

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/pokedex-lite.git
cd pokedex-lite
```

### 2. Install Dependencies

Make sure you have **Node.js** and **npm** installed. Then, run the following command to install dependencies:

```bash
npm install
```

### 3. Run the Development Server

After the dependencies are installed, start the development server:

```bash
npm start
```

This will start the application at [http://localhost:3000](http://localhost:3000).

## Usage

### Searching Pokémon
Type a Pokémon's name into the search bar, and the list will filter in real-time to show only the Pokémon that match the name.

### Filtering by Type
Select a type (e.g., Fire, Water, etc.) from the available type buttons, and the list will update to show only Pokémon of that type.

### Pagination
Use the **Next** and **Previous** buttons at the bottom to navigate through pages of Pokémon. You can also load more results using the "Load More" button.

### Favorites
Click the **heart icon** on a Pokémon card to mark it as a favorite. Your favorite Pokémon are saved in **localStorage**, so they persist even after a page refresh.

### Detailed View
Click on a Pokémon card to open a modal that displays detailed information about the selected Pokémon, including stats like **HP**, **Attack**, **Abilities**, and more.

## Acknowledgments

- **PokéAPI** for providing the Pokémon data.
- **React** and **TypeScript** for building the app.
- **web-vitals** for performance tracking.
