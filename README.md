# NavBot


Conversational Route Planning Application

Overview
This project is a mobile application designed to help users plan routes with integrated stops using a conversational chatbot interface. Users can input a natural language query, such as "I want to go from downtown Toronto to Grassy Barra in North York and stop at a grocery store on the way." The application then provides optimized routes, suggests grocery stores along the way, and integrates public transit schedules, all in a seamless and efficient manner.

This project showcases the use of Python for backend development, API integration, machine learning, and mobile app development. It is a portfolio project that demonstrates full-stack capabilities with a focus on problem-solving and user experience.

Features

Conversational Route Planning: Users can interact with the app via a chatbot, inputting natural language queries to get multi-stop route suggestions.
Google Maps Integration: Provides optimized routes, including public transit information and walking directions.
Grocery Store Suggestions: The app recommends grocery stores based on location and user preferences, including store hours.
Real-Time Transit Data: Uses public transit APIs (e.g., TTC) to provide accurate information on bus and subway schedules.
User Preferences and Data Persistence: The app allows users to save preferred stores and routes for future use.
Technologies Used

Frontend
Framework: Kivy or BeeWare (Python-based cross-platform mobile frameworks)
UI/UX: Chatbot interface for querying and displaying results
Google Maps SDK: Used for map visualization and route planning
Backend
Framework: Flask or FastAPI for building RESTful APIs
Routing & Location APIs: Google Maps API for route suggestions, Google Places API or Yelp API for store data
Public Transit API: Integrated with real-time transit information from APIs such as TTC
Chatbot: OpenAI GPT-3 API for natural language processing and conversational interactions
Database: SQLite or PostgreSQL for user data and preferences
Additional Tools
Hosting: Heroku or PythonAnywhere for backend hosting
Version Control: GitHub for code management and collaboration
Testing: Unit tests for backend and frontend functionality
