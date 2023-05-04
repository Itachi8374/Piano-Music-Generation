# Piano Music Generation Using RNN

This app generates a piano music, given a sequence of seed notes. 

## Getting Started

To get started with this app, follow the instructions below.

### Prerequisites

Before you can run this app, you'll need to have the following installed:

* Python 3.x
* Flask

### Installing

1. Clone the repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Install the required packages using `pip install -r requirements.txt`.

### Running the App

1. Once you have installed the required packages, start the Flask development server by running the command `python app.py`.
2. Open a web browser and navigate to `http://localhost:5000` to view the app.

## Usage

To use the app, follow the instructions below.

1. By clicking generate button, a request goes to endpoint `\predict`.
2. For now, a randome sequence of 50 notes is selected as seed and a song is generated as downloadable MIDI file.
2. Select and upload the MIDI file to play it with visualisation.

## To Do's

1. Form to change hyperparameters like seed_len, length of generated music.
2. Use custom seed notes
3. Comparison with random generation and generation with seed.
