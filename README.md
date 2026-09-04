# Android Book Search

A simple Android application for searching and finding books, built with Kotlin and Jetpack Compose.

## Project Overview

This is an Android application that allows users to search for books by title or author, and filter results by genre and condition. The app is built using modern Android development practices, including Kotlin and Jetpack Compose for the UI.

## Key Features

*   **Search:** Find books by title or author.
*   **Filtering:** Filter book results by genre (Fiction, Non-Fiction, Mystery, Science Fiction) and condition (New, Good, Fair, Old).
*   **Book Details:** View details for specific books.
*   **Local Database:** Uses a local database (Room) for storing and retrieving book information.

## Tech Stack

*   **Language:** Kotlin
*   **UI Framework:** Jetpack Compose
*   **Local Storage:** Room Database
*   **Concurrency:** Kotlin Coroutines
*   **Navigation:** Jetpack Navigation Compose

## Project Structure

*   `AndroidStudioProjects/mybookswap/`: Contains the main Android Studio project.
    *   `app/src/main/java/com/example/mybookswap/ui/Search/`: Contains the UI components for the search screen (`BookSearchScreen.kt`).

## Development

This is an Android Studio project. To run the project locally:

1.  Clone the repository.
2.  Open the `AndroidStudioProjects/mybookswap/` directory as a project in Android Studio.
3.  Sync project with Gradle files.
4.  Run the application on an emulator or a physical device.
