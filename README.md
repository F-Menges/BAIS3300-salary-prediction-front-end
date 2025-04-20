# 3300 - Salary Prediction Model Front End

![Python badge](https://img.shields.io/static/v1?message=python&logo=python&labelColor=3776AB&color=3776AB&logoColor=white&label=%20&style=for-the-badge) ![Flask badge](https://img.shields.io/static/v1?message=Flask&logo=Flask&labelColor=000000&color=000000&logoColor=white&label=%20&style=for-the-badge) ![Bootstrap 5 badge](https://img.shields.io/static/v1?message=Bootstrap%205&logo=bootstrap&labelColor=7952B3&color=7952B3&logoColor=white&label=%20&style=for-the-badge) ![Azure badge](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

This is a homework assignment for the class BAIS:3300 Digital Product Management.

This application uses Python [Flask](https://flask.palletsprojects.com/en/3.0.x/) to provide a user interface for the salary prediciton machine learning model API.

Formatting was accomplished using [Bootstrap 5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

### To Run This Application

---

1. Clone this repository to local computer

2. Create a new virtual environment

   - Windows: `python -m venv ./venv`
   - Mac: `python3 -m venv ./venv`

3. Activate the new virtual environment

   - Windows: `.\venv\Scripts\activate`
   - Mac: `source ./venv/bin/activate`

4. Install the dependencies `pip install -r requirements.txt`

5. Run the application with `flask run`
   a. To run a specific app: `flask --app app run`  
   b. To change the port: `flask run --port 8080`  
   c. To listen on all public IP addresses: `flask run --host 0.0.0.0`
   d. To run in debug mode: `flask run --debug`

   Example: `flask --app app run --port 8080 --debug `
