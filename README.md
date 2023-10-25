# Jammming - Spotify Playlist Creator

## Overview

Jammming is a React-based web application that allows users to search for songs using the Spotify API, add them to a custom playlist, and then save it to their Spotify account.

## Features

- Search for songs by title, artist, or album
- View search results in real-time
- Add songs to a custom playlist
- Remove songs from the custom playlist
- Save the custom playlist to a Spotify account

## Prerequisites

- Node.js and npm installed
- Spotify developer account and a registered app to get the `client_id`

## Setup

1. Clone the repository or download the ZIP file and extract it.

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Navigate to the project directory and install dependencies.

    ```bash
    cd your-repository
    npm install
    ```

3. Create a `.env` file in the root directory and add your Spotify `client_id`.

    ```
    REACT_APP_SPOTIFY_CLIENT_ID=your_actual_client_id_here
    ```

4. Start the development server.

    ```bash
    npm start
    ```

## Usage

1. Open your web browser and go to `http://localhost:3000/`.
2. Use the search bar to find songs.
3. Add songs to your custom playlist.
4. Save the playlist to your Spotify account by clicking the "Save to Spotify" button.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License

