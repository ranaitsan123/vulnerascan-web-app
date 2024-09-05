# VulneraScan Web App

## Description
VulneraScan is a web application designed to help users perform vulnerability scans on websites. It provides authentication, scanning, and reporting functionalities.

## Features
- User authentication
- Initiate vulnerability scans
- View scan results
- Download scan reports in PDF format
- View scan history

## Installation

### Backend
1. Clone the repository: `git clone https://github.com/yourusername/vulnerascan-web-app.git`
2. Navigate to the backend directory: `cd vulnerascan-web-app/backend`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment: `source venv/bin/activate` (Linux/macOS) or `venv\Scripts\activate` (Windows)
5. Install dependencies: `pip install -r requirements.txt`
6. Run the server: `python run.py`

### Frontend
1. Navigate to the frontend directory: `cd vulnerascan-web-app/frontend`
2. Install dependencies: `npm install`
3. Start the app: `npm start`

## API Documentation

### Authentication
- **Endpoint:** `/api/authenticate`
- **Method:** POST
- **Description:** Authenticates users and returns a session token.

### Scan
- **Endpoint:** `/api/scan`
- **Method:** POST
- **Description:** Initiates a scan.

### Report
- **Endpoint:** `/api/report`
- **Method:** GET
- **Description:** Fetches the latest scan report.

## Contributing
Please submit issues and pull requests through GitHub.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
