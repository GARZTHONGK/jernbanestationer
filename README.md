# Jernbanestationer

This project is a Python application that fetches data from Wikidata about train and metro stations in Denmark. It uses the SPARQLWrapper library to query Wikidata and SQLAlchemy for database operations. The application also provides a GUI using tkinter and tkintermapview for displaying the station data on a map.

## Installation

1. Clone the repository
```bash
git clone https://github.com/GARZTHONGK/jernbanestationer.git
```
2. Install the required packages using pip:

```bash
pip install -r requirements.txt
```
## Usage

Run the `main.py` script to start the application.

If there are no markers present on first initial run, press the "Update database" button.

You can search for stations by name, type, line, network and opening date. The search terms should be separated by commas. For example, to search for all s-trains and all regional trains you can enter "S-train,Regional rail" in the type field.
