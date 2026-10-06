# Pokémon Full Art Trainer Checklist

A web-based checklist for tracking a Pokémon TCG Full Art Trainer card collection.

The application provides a visual catalog of Full Art Trainer cards and allows collectors to quickly keep track of which cards they own and which cards are still missing.

## Features

- Search cards by character/trainer name
- Filter cards by owned or missing status
- Filter by Pokémon TCG set
- Filter by rarity/type
- Sort cards alphabetically or by set/card number
- View card artwork alongside card information
- Track collection progress
- Automatically save owned cards locally in the browser
- Export collection progress to a JSON file
- Import previously saved collection data
- Works offline once the files are downloaded

## Technologies

- HTML
- CSS
- JavaScript
- JSON
- Browser Local Storage

## How to Use

1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Browse or search for cards in the collection.
4. Mark cards as owned as you collect them.
5. Use the filters to view owned or missing cards.
6. Use **Export** to create a backup of your collection progress.
7. Use **Import** to restore a previously exported collection.

## Purpose

This project was created to provide a simple and visual way to manage a Pokémon TCG Full Art Trainer collection without requiring an account, database, or internet connection.

Collection data is stored locally in the user's browser, making the checklist lightweight and easy to use.

## Repository Structure

- `index.html` — Main application and user interface
- `images/` — Card images used by the checklist
- `image_overrides.json` — Image mapping/override data

## Future Improvements

Potential future additions include improved mobile responsiveness, additional card collections, expanded sorting/filtering options, and easier updating as new Pokémon TCG sets are released.
