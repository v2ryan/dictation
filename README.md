# Dictation Buddy

A kid-friendly web application for practicing dictation. Designed for primary school children to use on an iPad.

## Features

- **Kid-Friendly UI**: Colorful interface with large buttons and easy-to-read fonts.
- **Custom Word Lists**: Parents or teachers can paste any list of words.
- **Adjustable Settings**:
  - Language: English (US) or Cantonese (HK).
  - Reading Speed: Slow to Fast.
  - Gap Duration: Control the delay between words.
- **Visual Progress**: Shows "Word X of Y" to keep track without revealing the word.

## How to Use

1. Open `index.html` in a web browser (Safari on iPad recommended).
2. Paste a list of words into the text box (separated by commas or new lines).
3. Adjust the language, speed, and gap settings if needed.
4. Press **Start** to begin the dictation.
5. The app will read each word and wait for the specified gap time before reading the next one.

## Technologies

- HTML5
- Tailwind CSS (via CDN)
- JavaScript (Web Speech API)
