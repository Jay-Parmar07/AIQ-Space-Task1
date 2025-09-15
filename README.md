# AIQ-Space-Task1
Student Commute Optimizer (Full stack)
The Student Commute Optimizer addresses a real-world challenge by combining the convenience of school buses and ride-sharing services like Uber, Ola, and Rapido. The goal is to create a smart carpooling platform specifically designed for students, optimizing routes to save time, reduce costs, and minimize environmental impact.

Core Idea :-
Students enter their home location (pickup point) and destination (school/college) into a simple map-based frontend.The system calculates and visualizes the optimal routes using Google Maps API or other mapping services.Using machine learning or heuristic algorithms, the backend identifies overlapping or nearby routes within a 1-2 km range to suggest efficient ride-sharing matches.Students are assigned unique, anonymous usernames to protect privacy while enabling communication.The app enables real-time chat through Socket.io, so students can coordinate rides safely and privately.


Frontend:-
1. Built with React.js for a responsive user interface.
2. Users log in with credentials (e.g., Gmail OAuth).
3. Unique usernames are generated and verified via the backend to avoid duplication.
4. The map displays routes, nearby students traveling in the same direction, and icons for matched users.
5. Clicking on an icon opens a real-time chat window for anonymous communication.

Additional UI features:
1. Heat maps displaying popular routes.
2. Route previews showing estimated time and cost savings.
3. Real-time location sharing during active carpooling.
4. Predefined safe pickup points to ensure security.

Backend:-
1. Developed with Node.js and Express.js for API and business logic.
2. Stores user data, routes, chats, and usernames in a database (MongoDB or PostgreSQL).
3. Implements route matching algorithms:
    a. Compares routes by checking GPS coordinates for overlaps or proximity.
   b. Uses heuristics or ML-based route optimization for precise matching.
4. Ensures username uniqueness and anonymity.
5. Handles real-time chat functionality with Socket.io.
6. Supports group creation for students who want to travel together and enables ride experience ratings.

Safety Measures:-
 To ensure student safety throughout the ride-sharing process, the app incorporates multiple protective features:
2. Share Ride Status: Students can share their live ride status with trusted contacts (e.g., parents or guardians).
3. In-App Emergency Button: A panic button in the app allows students to alert authorities or contacts instantly in case of emergency.
4. Route Deviation Alerts: Automatic alerts notify students and trusted contacts if the vehicle deviates significantly from the planned route.
5. Driver-Rider Verification Codes: Both rider and driver exchange unique verification codes before starting the ride to confirm identities.

Environmental Impact
1. The app encourages sustainable commuting and helps students track their environmental contributions:
2. Carbon Footprint Reduction Points: Students earn points based on how much CO₂ emissions they save by carpooling instead of traveling individually.
3. CO₂ Emission Savings Calculator: Calculates and displays estimated emissions saved per trip.
4. Monthly Environmental Impact Reports: Users receive reports summarizing their environmental impact over time.
5. Group Achievements: Groups of students can unlock milestones for sustainable commuting, fostering community engagement and motivation.

Summary

This solution blends the efficiency of ride-hailing apps with the safety and routine of school transportation. By leveraging modern technologies like React, Google Maps API, Node.js, and Socket.io, it creates a practical and user-friendly platform that encourages students to share rides safely and sustainably while reducing travel-related challenges.
