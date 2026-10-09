# Random Password Generator

A simple and beginner-friendly Random Password Generator built using HTML, CSS, and JavaScript. It generates a random 14-character password containing uppercase letters, lowercase letters, numbers, and special characters.

## Features

- Generate a random 14-character password.
- Include uppercase and lowercase letters.
- Include numbers and special characters.
- Copy the generated password to the clipboard.
- Display a confirmation message after copying.
- Simple user interface with interactive buttons.

## Technologies Used

- **HTML5** — Structure of the application.
- **CSS3** — Styling and layout.
- **JavaScript** — Password generation and clipboard functionality.
- **Google Fonts (Oswald)** — Typography.
- **Font Awesome** — Copy icon.

## How It Works

1. Click the **Generate** button to create a random password.
2. JavaScript selects random characters from a predefined character set.
3. The generated password contains 14 characters.
4. Click the copy icon to copy the password.
5. A **Copied!** message appears temporarily to confirm the action.

## Project Structure

```text
random-password-generator/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run Locally

1. Clone or download the repository.
2. Keep `index.html`, `style.css`, and `script.js` in the same folder.
3. Open `index.html` in your web browser.
4. Click **Generate** to create a password.
5. Click the copy icon to copy it.

No package installation or build tools are required.

## Current Limitations

- Password length is fixed at 14 characters.
- Users cannot customize the character types.
- Passwords are generated using JavaScript's `Math.random()`, which is not suitable for generating passwords for highly sensitive accounts.
- Generated passwords are not saved.

## Future Improvements

- Add a password-length selector.
- Allow users to choose uppercase letters, lowercase letters, numbers, and symbols.
- Add a password-strength indicator.
- Add a button to show or hide the password.
- Use the Web Crypto API for stronger random password generation.

## Security Note

This project is intended for learning and practice. For important accounts, use a trusted password manager or a generator that uses cryptographically secure randomness.

## License

This project is created for learning and practice purposes. Add a formal license if you plan to distribute it publicly.