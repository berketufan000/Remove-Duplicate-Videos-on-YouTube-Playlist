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

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/Remove-Duplicate-Videos-on-YouTube-Playlist.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Remove-Duplicate-Videos-on-YouTube-Playlist
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Place your `client_secret.json` file in the project directory.
2. Run the script:
   ```bash
   python script.py
   ```
3. Follow the on-screen instructions to authenticate with your Google account.
4. Provide the **playlist ID** when prompted.  
   - You can find the playlist ID in the URL of your playlist.  
     Example URL:  
     ```
     https://www.youtube.com/playlist?list=PLabcd1234Efgh5678
     ```
     The playlist ID is the part after `list=`:  
     ```
     PLabcd1234Efgh5678
     ```

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
