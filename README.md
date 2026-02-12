# FN-RandomShop

FN-RandomShop is a Node.js tool that creates a random Fortnite item shop for private servers.
It selects random skins from a list in `index.js` and gives each item a random price.

## Installation

1. Download and install Node.js:
   [https://nodejs.org/en/download/current](https://nodejs.org/en/download/current)

2. Install the packages:

```
npm install
```

3. Run the project:

```
node index.js
```

## Configuration

All skin IDs are inside the `index.js` file.

### Add Skins

Add more skin IDs to the list in `index.js`.
They will be included in the random shop automatically.

### Change Price Range

Prices are randomly set between 200 and 2000 V-Bucks.
You can change the minimum and maximum values in the price function inside `index.js`.

## Planned Features

* Add more skin IDs (Season 1–10)
* Make the shop change automatically every 24 hours
* Make prices closer to real Fortnite prices

## Contributing

You can open an issue or submit a pull request if you want to improve the project.

## Disclaimer

This project is for educational and private server use only.
Fortnite is owned by Epic Games.
This project is not connected to Epic Games.
