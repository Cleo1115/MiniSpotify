# MiniSpotify

MiniSpotify is a mobile music streaming application based on Kotlin, designed to provide an efficient user experience through a separated frontend and backend architecture. The frontend utilizes Android Jetpack and Jetpack Compose for a modern user interface, while the backend leverages the Ktor framework to manage all server-side logic.

## Architecture

### Frontend
- **Jetpack Compose**: Handles UI logic and rendering, ensuring a dynamic and responsive user experience.
- **Jetpack Navigation**: Used to design a smooth and visually appealing in-app navigation system with a BottomBar.

### Backend (using Ktor Framework)
- **Ktor**: Serves as the server application framework, handling HTTP requests, routing, and data interactions with the frontend.
- **Retrofit**: Integrated in the frontend to handle network requests, closely integrated with the Ktor backend to simulate real-world data interactions.
- **Room Database**: Utilized in the frontend for local data storage and caching to optimize data retrieval and offline access.

## Features

- **Kotlin-Based Application**: Developed using Kotlin, incorporating Android Jetpack Libraries to facilitate a modular and efficient app architecture.
- **Dependency Injection with Hilt**: Utilized Hilt for advanced dependency injection, resulting in clean and maintainable code.
- **Jetpack Compose UI**: Created a compelling user interface using Jetpack Compose, aligning closely with Spotify's design and functionality standards.
- **In-App Navigation**: Streamlined navigation with a BottomBar component via Jetpack Navigation, making user interactions smoother and more intuitive.
- **Mock RESTful API**: Established a mock backend using Ktor to simulate real-world data interactions, integrated with Retrofit for network request handling.
- **Local Data Caching**: Enabled local caching of user favorites using Room Database, which ensures optimized data retrieval and offline accessibility.
- **Music Playback**: Implemented Google ExoPlayer to provide seamless music playback, offering a smooth and high-quality audio experience.

## Technologies Used

### Frontend
- **Jetpack Compose**: Handles the UI logic and rendering, providing a dynamic and responsive user experience.
- **Jetpack Navigation**: Used for designing a responsive and visually appealing in-app navigation structure with BottomBar.

### Backend
- **Ktor**: Primary framework used for application logic on the server-side.
- **Retrofit**: Used for handling network requests to communicate with the Ktor backend.
- **Room Database**: Utilized for storing and caching user data locally to provide a seamless experience even without internet connectivity.

## Additional Libraries
- **Hilt**: Used for dependency injection to improve the maintainability and modularity of the application.
- **Google ExoPlayer**: Integrated for music playback, providing users with high-quality streaming of audio content.

## Demo

Below are screenshots showcasing the key features of MiniSpotify:

### Home Screen

The home screen displays personalized recommendations, including "Top mixes," "Made for you," and "This Is: K-Music" sections, ensuring users have easy access to their favorite tracks.

### Album Detail Screen

Users can view detailed information about albums, including the list of songs and descriptions, offering a visually appealing and informative experience.
