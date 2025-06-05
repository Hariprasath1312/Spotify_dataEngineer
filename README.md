# Spotify_dataEngineer
the spotify project helps to insert the data into database and get the data fromthe spotify using API 

And This Python script connects to the Spotify Web API using the Spotipy library to fetch detailed metadata about a specific Spotify track given its URL. The script performs the following key tasks:

Authentication: It authenticates with Spotify’s API using client credentials (Client ID and Client Secret) through the SpotifyClientCredentials manager.

Track ID Extraction: The script extracts the unique track ID from a full Spotify track URL by using a regular expression to parse the URL string.

Fetching Track Data: Using the extracted track ID, the script requests detailed information about the track, including:

Track Name

Primary Artist Name

Album Name

Popularity Score (a value from 0 to 100 representing the track’s popularity)

Duration (in minutes)

Data Display and Storage:

It prints the fetched metadata to the console for quick review.

Converts the metadata into a Pandas DataFrame for structured data manipulation.

Saves the track metadata as a CSV file (spotify_track_data.csv) for persistent storage and later use.

Visualization:

The script creates a simple bar chart visualization showing the track’s popularity and duration using Matplotlib.

This helps provide a quick visual understanding of these two key attributes.
