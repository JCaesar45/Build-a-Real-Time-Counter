```
 # Real Time Character Counter

This project is a simple web application that provides a live character count of text input in a textarea. It enforces a maximum character limit of 50 characters using JavaScript (without the `maxlength` attribute) and updates the count in real-time as the user types.

## Features

- Textarea input with a maximum limit of 50 characters enforced via JavaScript.
- Live character count display below the textarea.
- When the user reaches exactly 50 characters, the character count text turns red.
- Prevents the user from typing beyond the 50-character limit.
- Clean and minimal UI styling.

## Demo

Open `index.html` in your browser to see the app in action.

## Usage

1. Start typing in the textarea.
2. The character count updates live in the format: `Character Count: X/50`.
3. When exactly 50 characters are typed, the count text turns red.
4. You cannot enter more than 50 characters.

## Files

- `index.html`: The main HTML structure including the textarea and character count elements.
- `styles.css`: CSS styles for layout and color changes.
- `script.js`: JavaScript logic to enforce character limits and update the UI.

## Technical Details

- The textarea has the id `text-input`.
- The character count display is a paragraph with the id `char-count`.
- JavaScript listens to the `input` event on the textarea to update the count and enforce the character limit.
- The red color style is applied inline to the character count text when the character count reaches exactly 50.

## How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Start typing in the textarea to see the live character count in action.

## License

This project is open source and available under the MIT License.

---

Feel free to customize or ask if you want a more detailed or simplified version!
