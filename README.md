# KanaAdder
An Anki plugin that will generate a kana-only translation of an expression. This can be done during the creation of new cards, or in bulk for existing cards. Requires the [Japanese Support](https://ankiweb.net/shared/info/3918629684) plugin.

Adapted from the previous [KanaAdder plugin](https://github.com/Predator2610/KanaAdder).

# Instructions

KanaAdder will generate the kana reading from the `Reading` field, and write it to the `Kana` field. This is done **after** you click "Add" when creating a new note.

Alternatively, you can select a batch of cards in the Anki browser, and click the "Edit"->"Bulk-add Kana" menu item to generate readings. This will not overwrite a card's `Kana` field if it is already populated.

# Setup
Open the `KanaAdder.py` file and change the values of `READING_FIELD` and `KANA_FIELD` to match your own cards. Like the Japanese Support plugin, KanaAdder will only work for notes that include "Japanese" in their names. (This can be customized in the `NOTE_TYPE` line in the above file.)

Copy `KanaAdder.py` to your Anki plugins directory. 
