
Driver Behavior Monitoring System Overview

The **Driver Behavior Monitoring System** uses AI to detect dangerous driver behaviors such as drowsiness, texting, and distractions, aiming to enhance road safety, particularly in public transport. The system monitors the driver in real-time and notifies bus managers or authorities when unsafe behavior is detected, allowing for timely intervention.

Features

- **Driver Behavior Detection**: Detects dangerous behaviors like drowsiness, texting, or distractions using AI-based algorithms.
- **Real-Time Alerts**: Sends notifications to bus managers or authorities for immediate action.
- **Vehicle and Driver Analytics**: Provides detailed analytics of vehicles and drivers, including behavior patterns and driving habits.
- **Monitoring Dashboard**: Displays real-time monitoring of driver behaviors, including reports and insights for improved safety.
  
Technologies Used

- **Backend**: Node.js, Express.js
- **Frontend**: React.js
- **Database**: PostgreSQL
- **Version Control**: Git, GitHub
- **CI/CD**: GitLab for continuous integration and deployment

 Installation

Prerequisites

- Node.js
- PostgreSQL
- Git

Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LindahPatricia/Driver-Behavior-Monitoring-Dashboard.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Driver-Behavior-Monitoring-Dashboard
   ```

3. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

4. **Install frontend dependencies:**
   ```bash
   cd frontend
   npm install
   ```

5. **Set up PostgreSQL database:**
   - Create a new PostgreSQL database.
   - Update the database configuration in the `config/database.js` file.

6. **Run the backend:**
   ```bash
   npm start
   ```

7. **Run the frontend:**
   ```bash
   cd frontend
   npm start
   ```

8. Open your browser and go to `http://localhost:3000` to view the dashboard.

 Usage

1. Log in to the system.
2. Monitor the real-time behavior of drivers.
3. View analytics on vehicle and driver performance.
4. Receive alerts for unsafe driving behaviors.

