# GeoEstate Backend

GeoEstate’s backend is built using Node.js, Express, and PostgreSQL, deployed on Google Cloud Platform (GCP). This API serves as the core of GeoEstate, providing the necessary functionality to manage real estate data, user authentication, and neighborhood insights.

## Setup Environment

1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/geoestate-backend.git
   cd geoestate-backend
2. Install dependencies:

   ```bash
    npm install
3. Set up environment variables:

 - Create a .env file in the root directory with the following variables:
   ```bash
   DB_HOST=your-database-host
   DB_USER=your-database-user
   DB_PASSWORD=your-database-password
   DB_NAME=your-database-name
   JWT_SECRET=your-jwt-secret
   GCP_PROJECT_ID=your-gcp-project-id
  - Initialize PostgreSQL Database on GCP (if not already set up).

4. Get Started
Run the development server:

   ```bash
    npm start
Access the backend API on http://localhost:3000.

5. Features
- User Authentication: Using JWT for secure user login and session management.
- Property Data: Manage property listings, including creating, updating, and retrieving property details.
- Neighborhood Insights: Provide dynamic layers and data regarding neighborhoods.
- Real-Time Updates: API endpoints to handle updates related to properties and neighborhoods.

6. License
This project is licensed under the MIT License - see the LICENSE file for details.








