# JCOMPANY
Urban Company Full-Stack Clone built using Flask, Jinja2, Python, ASGI

![image](https://github.com/user-attachments/assets/fda3cf61-0a96-4acd-8c43-be2ad4305658)

![image](https://github.com/user-attachments/assets/bef72ffd-40b8-4497-bdfc-2d355bebb5f8)


## Project Overview
This is a full-stack clone of Urban Company, built using Python, Flask, SQLite, and SQLAlchemy. It is a multi-user platform designed to manage services, with distinct panels for admin, employees, and customers.

## Features
- **Admin Panel:**
  - Manage users (add, update, delete).
  - Manage services and categories.
  - View detailed analytics and reports.

- **Employee Panel:**
  - View assigned service requests.
  - Update service status (e.g., completed, in-progress).
  - Upload CV and personal details.

- **Customer Panel:**
  - Browse services by category.
  - Book services and select preferred dates.
  - Manage personal information and saved addresses.
  - View booking history and service status.

- **Additional Features:**
  - Search functionality for services.
  - Address selection from saved profiles or Google Maps.
  - Flash messages for user feedback.
  - Responsive design using Bootstrap 5.3.0.

## Technology Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript, Bootstrap 5.3.0
- **Database:** SQLite with SQLAlchemy ORM

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/urban-company-clone.git
   cd urban-company-clone
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Initialize the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

5. Run the development server:
   ```bash
   flask run
   ```

6. Open the application in your browser:
   ```
   http://127.0.0.1:5000/
   ```

## Project Structure
```
jcompany/
├── app/
│   ├── static/
│   ├── templates/
│   ├── models.py
│   ├── routes.py
│   ├── forms.py
│   └── utils.py
├── migrations/
├── instance/
│   └── config.py
├── requirements.txt
├── README.md
└── run.py
```

## Key Pages and Modules
1. **Admin Panel:** Accessible at `/admin`.
2. **Employee Panel:** Accessible at `/employee`.
3. **Customer Dashboard:** Accessible at `/dashboard`.
4. **Service Booking:** Customers can book services and view details in a modal pop-up.

## Deployment
The project is deployed on Render. Access the live demo here:
[Urban Company Clone](https://jcompany.onrender.com/)

## Future Enhancements
- Add payment gateway integration.
- Improve analytics with charts and graphs.
- Implement real-time notifications.

## License
This project is licensed under the MIT License.

---
For any queries or contributions, feel free to contact the project creator.

