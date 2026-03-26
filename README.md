#  Django REST API: AWS Cloud Deployment
**Task:** Day 13 - Infrastructure & Cloud Setup

##  Live Deployment
The application is successfully hosted on an AWS EC2 instance.
- **Live URL:** [http://13.62.224.243:8000](http://13.62.224.243:8000)
- **Status:** Active (Production Test Environment)

##  Infrastructure Details
- **Cloud Provider:** Amazon Web Services (AWS)
- **Instance:** t3.micro (Ubuntu 24.04 LTS)
- **Networking:** Security Groups configured for SSH (22) and Web (8000)

##  Project Contents
- **`backend_api/`**: Main Django configuration.
- **`api/`**: Student model, serializers, and REST views.

##  Setup Instructions
1. SSH into the EC2 instance using your `.pem` key.
2. Activate the virtual environment: `source venv/bin/activate`.
3. Run the server: `python3 manage.py runserver 0.0.0.0:8000`.

