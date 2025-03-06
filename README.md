# Samadhan

Samadhan is a service marketplace mobile application that connects users with service professionals to address various issues. The app supports user registration, issue posting, location-based service discovery, real-time chat, service scheduling, and a rating system.

## Tech Stack
- **Frontend:** React Native, Expo
- **Backend:** Nest.js, TypeScript
- **Database:** PostgreSQL, TypeORM
- **Real-Time Communication:** Socket.io
- **State Management:** Context Provider

## Architecture
Samadhan follows a **4-Tier Layered Architecture:**

1. **Presentation Layer**: React Native-based UI handling user interactions and rendering views.
2. **Business Layer**: Contains business logic and application rules.
3. **Persistence Layer**: Manages data storage and retrieval via TypeORM.
4. **Database Layer**: PostgreSQL stores structured data such as user profiles, service requests, and chat messages.

## Features
### User Registration & Profiles
- Users create accounts with personal details and location.
- Service professionals list their expertise and service categories.

### Issue Posting
- Users post service requests with images, videos, and descriptions.

### Location-Based Service Discovery
- Users view nearby service professionals based on location.

### Chat & Negotiation
- Users and service professionals discuss details, negotiate prices, and schedule services via chat.

### Service Scheduling & Management
- Both parties agree on service time within the chat.
- Service requests become invisible to other professionals after confirmation.

### Penalty System
- Professionals are penalized for missing scheduled service times.

### Ratings & Reviews
- Users and professionals can rate each other to build trust.

### Notifications
- Real-time notifications for chat messages, service confirmations, and completions.

### Service History
- Users and professionals can track past service requests and completed jobs.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone (https://github.com/abuMomin/Samadhan_App.git
   git checkout feature/fullstack
   cd backend
   ```
2. Install dependencies:
   ```sh
   yarn install
   ```
3. Run the application:
   ```sh
   yarn run start
   ```

## License
This project is licensed under the MIT License.

## Contributors
We welcome contributions! Please submit a pull request or open an issue.
