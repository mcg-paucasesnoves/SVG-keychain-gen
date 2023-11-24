# SVG-keychain-gen
Simple keychain generator
Based on a previous SVG file that is the keychain base form, this python script read a UTF-8 simple text file and write the names of each keychain.
Each line on the text file must have only a name.
The script must create a new SVG file with many keycahins as names in the txt file.
Each name must be in the center the name on SVG keychain.

1. Imports txt file
2. Import base SVG file
3. Set the canvas based on the number of keychains, restriction 600x300 mm
4. Repeat the keychain and insert each name in the middle
6. Save it as a new SVG file.
