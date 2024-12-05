
# Cyber Security Encryption Playground

**Cyber Security Encryption Playground** is a web-based application designed to help users explore and experiment with various encryption techniques. The platform provides an interactive way to learn how different ciphers work and to practice encryption and decryption.

## Features

- **Caesar Cipher**: Shift each letter by a fixed number of places.
- **Multiplicative Cipher**: Multiply the position of each letter with a key value.
- **Affine Cipher**: Combines multiplication and addition for encryption.
- **Additive Cipher**: Add a constant value to each letter's position.

## Technologies Used

- **HTML, CSS, JavaScript**: For building the front-end interface and cipher functionalities.
- **Bootstrap**: Provides a responsive design and prebuilt components for enhanced usability.

## File Overview

### `index.html`
- The landing page for the application.
- Lists all available ciphers with descriptions and links to their respective tools.
- Styled with gradient animations and interactive hover effects.

### `cipher.html`
- The encryption and decryption tool for the selected cipher.
- Dynamically adapts based on the selected cipher type (passed via query parameters).
- Includes:
  - Text fields for the message and encryption keys.
  - Buttons for encrypting and decrypting text.
  - Live results display for immediate feedback.

## How to Use

1. Open `index.html` in any modern web browser.
2. Choose a cipher to explore from the homepage.
3. On the cipher tool page:
   - Enter your message and required keys.
   - Click **Encrypt** or **Decrypt** to see the result.

## Cipher Implementations

- **Caesar Cipher**: Simple substitution cipher that shifts characters.
- **Multiplicative Cipher**: Uses modular arithmetic for encryption.
- **Affine Cipher**: Combines a multiplicative step and an additive step.
- **Additive Cipher**: A simpler variation of Caesar Cipher.

## Project Structure

```plaintext
project-directory/
│
├── index.html      # Home page with cipher selection
├── cipher.html     # Cipher tool page
├── README.md       # Documentation
```

## Future Enhancements

- Implement a fully functional AES cipher.
- Add support for additional encryption methods.
- Improve accessibility for a wider audience.

## License

This project is open-source and available under the [MIT License](LICENSE).
