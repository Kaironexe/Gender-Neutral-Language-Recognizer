# Gender-Neutral Language Recognizer

A single-page web application that scans a `.txt` file for gender-specific words and phrases and suggests gender-neutral alternatives. Terms are recognized with **regular expressions** (JavaScript `RegExp`).

## How to run

1. Download or clone this folder.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox). No installation, server, or internet connection is needed.
3. Click **Choose .txt file** (or drag a file onto the box) and select `sample.txt`.
4. Review the results table and the highlighted text.

## Files

- `index.html` - the complete application (HTML, CSS, JavaScript)
- `sample.txt` - sample input for testing
- `README.md` - these instructions

## Behavior

- Matching is case-insensitive and whole-word only (`he` is not found in `the`).
- Shows each detected term, its number of occurrences, and suggested alternatives.
- Displays "No predefined gender-specific terms were detected." when nothing is found.
- Displays clear messages for empty files and unsupported formats (anything other than `.txt`).
- Suggestions are for review only; the text is never changed automatically.
