🚀 MoodFlix – Mood-Based Entertainment Recommendation System

MoodFlix is a full-featured desktop application built using Java 21, JavaFX 17, and PostgreSQL that delivers personalized entertainment recommendations based on a user's emotional state. The application is designed using the Model-View-Controller (MVC) architecture to ensure clean separation of concerns, modular design, and maintainability.

The system allows users to select their current mood (such as Happy, Sad, Thriller, Romantic, Feel Good, or Comedy) and receive curated recommendations for movies, series, and trailers. It integrates the OMDb REST API to fetch real-time movie metadata including posters, ratings, and descriptions, enhancing the richness of content displayed inside the application.

MoodFlix implements secure authentication using BCrypt password hashing and supports role-based access control with separate dashboards for Admin and User roles. Users can manage personal watchlists, track viewing activity, and explore recommendations dynamically. Admin users can manage content, update entries, and oversee user activity through a dedicated management interface.

The application uses PostgreSQL as the relational database with proper normalization and structured schema design. HikariCP connection pooling ensures efficient and optimized database performance during concurrent access.

On the frontend, JavaFX is used to create a modern dark-themed UI with centralized CSS styling and smooth transitions. The application emphasizes usability, performance, and clean architecture principles while demonstrating strong backend integration and database handling.

MoodFlix showcases full-stack Java development skills, REST API integration, secure authentication practices, and real-world application architecture.
