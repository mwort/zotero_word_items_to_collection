# Zotero Word items to collection

A Python utility to create a Zotero collection from items added to a Word (.docx) document via the Zotero Word integration.

## Setup
- Open a commandline and install `pyzotero`: `pip install pyzotero`
- Create a Zotero API key with write permissions here (login first, copy the string shown and keep safe): https://www.zotero.org/settings/keys/new

## Usage
Run the script e.g. from this repo or add to a directory on your `PATH`:
  ```
  ./zotero_word_items_to_collection.py <path/to/docx/file> "New collection name" <your api key>
  ```
(add `-h` for help or `-n` to do a dryrun first)

## Credit
Michel Wortmann < wortmann@pik-potsdam.de >
MIT Licence