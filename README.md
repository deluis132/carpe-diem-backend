# Carpe Diem Backend

Carpe Diem Backend is the server-side application that handles the business logic, database interactions, and API endpoints for the Carpe Diem project. This backend service supports both the mobile and admin applications.

## Features

- User Authentication
- Membership Management
- Order Management
- Quotes of the Day
- Notifications (Push and Email)
- Database Management

## Technologies Used

- Python
- Flask 
- PostgreSQL

## Getting Started

### Prerequisites

- Python 3.x
- PostgreSQL
- Virtual Environment (venv)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/carpe-diem-backend.git
   cd carpe-diem-backend
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv\Scripts\actuvate
3. Install dependencies:
   ```sh
   py -m pip install -r requirements.txt
4. Set up the database:
   ```sh
   flask db init
   flask db migrate
   flask db upgrade
5. Start the development server:
   ```sh
   flask run
   
## Usage

Access the API endpoints at http://localhost:5000.

## License 

Proprietary License

© 2024 Carpe Diem LLC. All rights reserved.

