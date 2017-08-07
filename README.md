# KanaAdder
An Anki plugin that will generate a kana-only translation of an expression. This can be done in bulk or during the creation of new cards. Requires the [Japanese Support](https://ankiweb.net/shared/info/3918629684) plugin to function.

Adapted from [Predator2610's plugin](https://github.com/Predator2610/KanaAdder).

# Instructions

KanaAdder will generate the kana reading from the "Reading" field, and write it to the "Kana" field. This is done after you click "Add" when creating a new note.

Bulk-adding kana can be done through the "Edit"->"Bulk-add Kana" menu item after selecting a batch of cards in the Anki browser. It will not overwrite fields that are already populated.

# Setup
Open the `KanaAdder.py` file and change the values of `READING_FIELD` and `KANA_FIELD` to match your own cards. Just the Japanese Support plugin, KanaAdder will only work for notes that include "Japanese" in their names. (This can be customized with the `NOTE_TYPE` line in the above file.)

Copy `KanaAdder.py` to your Anki plugins directory. 
