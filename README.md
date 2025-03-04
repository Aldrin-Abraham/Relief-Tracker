![Disaster](https://github.com/user-attachments/assets/782cbccf-544c-4c80-88b6-301f1320361f)

# ReliefTracker – Disaster Relief Management System 🎯
ReliefTracker is a web-based application designed to streamline the process of managing disaster relief requests and resources efficiently. It allows users to submit relief requests, track assistance, and enables organizations to manage aid distribution effectively.

## Project Overview
ReliefTracker is a web-based disaster relief management system designed to facilitate the distribution of aid to affected individuals and communities. The system allows users to submit requests for assistance, enables administrators to manage and track these requests, and provides a structured workflow for relief organizations.

The project is built using Python (Flask) as the backend framework, SQLite for database storage, and HTML/CSS for the user interface, ensuring a lightweight, scalable, and easy-to-use platform. ReliefTracker aims to improve response times, enhance transparency, and streamline disaster relief efforts through an efficient and user-friendly system.

## Key Features
### User Request Management:
* Users can submit relief requests for essentials such as food, shelter, and medical aid.
* Requests are stored in a centralized database for efficient tracking.
* Users can check the status of their requests in real-time.

### Administrator Dashboard:
* Tracks available resources (e.g., food supplies, medical kits, shelters).
* Ensures efficient allocation of aid to maximize coverage.
* Helps prevent overlapping or missing distributions.

### Relief Resource Management:
* Tracks available resources (e.g., food supplies, medical kits, shelters).
* Ensures efficient allocation of aid to maximize coverage.
* Helps prevent overlapping or missing distributions.

### Volunteer & Organization Coordination:
* Enables NGOs, government agencies, and volunteers to coordinate efforts.
* Assigns tasks to volunteers based on real-time needs.
* Tracks ongoing and completed relief efforts.

### Notification System:
* Sends alerts and updates to users about their request status.
* Provides real-time notifications to administrators regarding urgent requests.

### Report Generation:
* Generates detailed reports on relief efforts and resource allocation.
* Tracks total requests handled, pending cases, and response times.
* Allows administrators to review and optimize relief strategies.

## Implementation Details
### Database Setup (SQLite) :
The project uses SQLite to store all data, ensuring a simple and portable solution.
The database includes several tables:
users: Stores user details (name, contact, role).
* requests: Contains relief requests, statuses, and assigned resources.
* resources: Manages available aid supplies and allocations.
* volunteers: Stores information about volunteers and their assigned tasks.

### Web Interface (Flask + HTML/CSS):
* Homepage: Provides an overview of the system and its purpose.
* User Request Page: Allows users to submit and track their requests.
* Admin Dashboard: Enables administrators to manage and assign requests.
* Volunteer Page: Displays assigned tasks and relief efforts.

### Backend Operations (Flask Framework):
* Handles user authentication and session management.
* Processes request submissions, approvals, and updates.
* Manages database interactions for efficient data retrieval and modification.
* Sends email or SMS notifications for status updates.
