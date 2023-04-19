# Steinitz;Reader

## Overview

This project is a webapp for viewing annotated chess games in PGN format. The main focus is on viewing well-annotated master games. Key features:

* You can navigate entirely with the keyboard by using left and right arrow, and enterring variations with numeric keys. 0 enters the main line (as does right arrow), and 1 for the first variation.

* Big and friendly buttons for mouse users. A generous spacing means you won't misclick.

* Comments are given a prime spot in the interface for easy reading.

* The "variation stack" helps you remember whether you are looking at the mainline, a variation or sub-variation, and lets you easily go back to mainline or a parent variation.

* Overlaid arrows helps you compare the main move (green), variations (grey) and stockfish's pick (blue).

[Try it now](https://sr.rinor.se)

## Technologies used

 * chess.js
 * chessboard.js
 * @mliebelt/pgn-parser
 * Wikipedia chess pieces
 * Lichess cloud eval

## Installation

To run this project locally, you'll need to have npm installed on your machine. Then, follow these steps:

 * Clone this repository to your local machine.

 * Open a terminal in the project directory.

 * Install the project dependencies by running `npm ci`

## Running locally

* Open a terminal in the project directory and run `python -m http.server`

* Open your web browser and navigate to http://localhost:8000 to view the app.

## Contributing

If you'd like to contribute to this project, feel free to open an issue or pull request on GitHub.

## Known Issues

This app is not currently responsive or mobile-friendly.

## License

This project is licensed under the AGPL-3.0 license.