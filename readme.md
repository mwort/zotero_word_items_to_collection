# Zotero Word items to collection

A Python utility to create a Zotero collection from items added to a Word (.docx) document via the Zotero Word integration.

## Setup
- Open a commandline and install using pip: `pip install zotero-word-items-to-collection`
- Login to Zotero online and create a Zotero API key with write permissions here: https://www.zotero.org/settings/keys/new
- Copy the API string displayed after you saved it and save it to an empty file in your home directory called: `~/.zotero_api_key` (you can also parse it via the `--api-key` argument)

## Usage
On a commandline run:
```
zotero_word_items_to_collection <path/to/docx/file> "New collection name"
```
(add `-h` for help or `-n` to do a dryrun first)

## Credit
Michel Wortmann < wortmann@pik-potsdam.de >

MIT Licence