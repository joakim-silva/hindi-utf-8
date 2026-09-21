# Hindi UTF-8 Reference

A lightweight educational website exploring how Hindi characters in the Devanagari script are represented using Unicode and UTF-8.

Built with HTML and CSS, the site works offline and requires no installation or external dependencies.

## Features

Reference tables covering:

* Vowels and consonants
* Consonants with nukta
* Vowel marks (matras)
* Other marks, including halant and chandrabindu
* Common combined letters

Each entry includes its Devanagari character, Latin transliteration or meaning, Unicode code point, and UTF-8 bytes in hexadecimal.

The layout adapts to smaller screens, with horizontally scrollable tables.

## Understanding the Encoding

For example, the letter **क** is represented as:

| Representation     | Value                        |
| ------------------ | ---------------------------- |
| Transliteration    | ka                           |
| Unicode code point | `U+0915`                     |
| UTF-8 bytes        | `E0 A4 95`                   |
| Binary             | `11100000 10100100 10010101` |

UTF-8 is an **encoding, not encryption**. It defines how text is stored as bytes.

Each individual code point listed on the site uses three UTF-8 bytes. Combined letters can contain multiple code points and therefore require more bytes.

## Running Locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

No server, build tools, or internet connection is required.

## Project Files

* `index.html` — Page content and character tables.
* `style.css` — Colours, typography, layout, and responsive styling.

## Notes

* Transliteration helps represent Hindi characters using Latin letters; it is not a complete pronunciation guide.
* Dotted circles illustrate combining marks and are excluded from the listed encodings.
* Nukta consonants may have equivalent representations with different byte sequences.
* The tables focus on Hindi rather than the entire Devanagari Unicode repertoire.

## Author

Joakim Silva

