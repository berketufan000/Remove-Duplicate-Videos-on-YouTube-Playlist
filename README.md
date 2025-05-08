# Remove Duplicate Videos on YouTube Playlist

This Python script identifies and removes duplicate videos from a specified YouTube playlist using the YouTube Data API. It ensures that the playlist remains clean and organized by eliminating redundant entries.

---

## Features

- **Duplicate Detection**: Automatically detects duplicate videos in a YouTube playlist.
- **YouTube Data API Integration**: Seamless interaction with YouTube's API for playlist management.
- **Efficiency**: Removes redundant videos with minimal user intervention.

---

## Prerequisites

Before using this script, ensure you have the following:

1. A valid Google Cloud project with YouTube Data API v3 enabled.
2. A set of OAuth 2.0 credentials downloaded as a `client_secret.json` file.
3. Python 3.x installed on your system.

---

## Running the Script

### Windows:

1. Ensure Python is installed on your system.
2. Place your `client_secret.json` file in the project directory.
3. Double-click `run.bat` to start the script.

### Linux/MacOS:

1. Ensure Python is installed on your system.
2. Place your `client_secret.json` file in the project directory.
3. Run `run.sh` in your terminal to start the script.

---

## Notes:

- The `client_secret.json` file must be in the same directory as the script for authentication.
- Follow the prompts to authenticate via your browser.
- Provide the **playlist ID** when prompted.

---

## Limitations

- Only works with playlists owned by the authenticated account.
- Requires manual authentication via OAuth 2.0 the first time the script is run.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to suggest improvements or new features.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
