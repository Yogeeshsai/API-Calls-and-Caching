# API-Calls-and-Caching
It is a internship assignament
Creating a mobile image gallery app that fetches recent images from Flickr, caches them, and retains the last view when offline involves several steps. Below is a simplified example using React Native and AsyncStorage for caching. This example covers fetching data, displaying images, caching, and setting up a basic navigation structure.

Step-by-Step Guide
Set up your React Native environment.
Install necessary packages:
React Navigation for navigation.
Axios for API calls.
AsyncStorage for caching.
React Native Elements for UI components.
Explanation:
Fetching Data: The HomeScreen component fetches the recent photos from Flickr API using axios.
Caching: It checks for cached photos in AsyncStorage. If found, it sets the photos state to cached data and then updates with new data if available.
Displaying Data: The FlatList displays the images. It falls back to cached data if the network request fails or if the app is offline.
Styling: Basic styles are applied to position the images.
