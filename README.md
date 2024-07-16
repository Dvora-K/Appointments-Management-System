# **Appointments Management Website**
The Appointments Management Website is an end-to-end platform designed for efficient management of queues and meetings between customers and service providers.
It is a robust solution for managing appointments, ensuring streamlined communication and scheduling between customers and service providers. 
The system is designed with user-friendly screens and functionalities tailored to different user roles. The server-side application employs a 3-layer architecture, ensuring efficient data access using Entity Framework.
This README file provides comprehensive instructions on the setup, usage, and contribution guidelines for the project.

## Features
- **Queue Management:** Efficient handling of customer queues.
- **Appointment Scheduling:** Easy scheduling and management of meetings.
- **User Roles:** Functionality adapted to different user roles (customers and service providers).
- **Data Access:** Seamless data management using Entity Framework.
- **Responsive Design:** User-friendly interface optimized for various devices.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dvora-K/Appointments-Management-System.git
   cd Appointments-Management-System
   ```
2. **Backend Setup**:

   Navigate to the backend directory and restore the required packages:

   ```bash
   cd server
   dotnet restore
   ```

   Update the connection string in `appsettings.json` to match your SQL Server configuration.

   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=your_server;Database=your_database;User Id=your_user;Password=your_password;"
   }
   ```

3. **Frontend Setup**:

   Navigate to the frontend directory and install the required packages:

   ```bash
   cd ../client
   npm install
   ```

## Running the Application

1. **Run the Backend**:

   Navigate to the backend directory and start the server:

   ```bash
   cd server
   dotnet run
   ```

2. **Run the Frontend**:

   Navigate to the frontend directory and start the development server:

   ```bash
   cd ../client
   npm start
   ```

3. Open your web browser and navigate to `http://localhost:3000/`.

## Usage

1. **User Registration**: Users can register and log in to the system.
2. **Appointment Booking**: Customers can book, view, and cancel appointments.
3. **Queue Management**: Service providers can manage customer queues.
4. **User Roles**: The system provides distinct functionalities for customers and service providers.
   
## Technologies Used

- **Backend**: C# .NET CORE, Entity Framework Core
- **Database**: SQL-SERVER
- **Frontend**: React, TypeScript, SCSS
