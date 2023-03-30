# Anki Importer

This Python script is designed to extract data from an HTML file that was export from Notion and generate a file that can be imported into Anki, a popular flashcard software.

## Prerequisites

Before running this script, make sure you have the following installed:

- Python 3.x
- BeautifulSoup (You can install it using `pip install beautifulsoup4` command)
- Put all your media into Anki media stored directory.(It's usually be something like this C:\Users\your_username_here\AppData\Roaming\Anki2\Anki_user_here\collection.media)
## How to Use

1. Save the HTML file to be parsed in the same directory as the script.
2. Run the script using the command `python anki_importer.py`.
3. Enter the name of the HTML file when prompted.
4. Enter the name of the product when prompted.
5. Enter the tags to be associated with this deck when prompted.
6. The script will generate an output file named `<product_name>_anki_importer.txt` which can be imported into Anki.
## Information in Anki card

1. Using Toggle list head as a Front of the card
2. Using Paragraph in that Toggle list as that card Back
## Note

This script assumes that the HTML file contains information about a product and the flashcards will be generated based on the information present in the HTML file. Also, it assumes that the HTML file contains a section with the heading "Anki" which signifies the start of the flashcard data.
