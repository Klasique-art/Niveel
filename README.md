# Niveel
e Are A Registered Limited Liability Company In The State Of Delaware With A Global Reach. We Pride Ourselves On The Premises Of Saving Our Clients Time And Money.
# Niveel Website Readme

Welcome to Niveel - where we prioritize saving our clients' time and money! This website is developed using Django, HTML, CSS, and JavaScript, offering a seamless experience to our users.

## Local Installation

To run Niveel locally on your computer, follow these simple steps:

1. **Prerequisites**: Ensure you have Python and Django installed on your machine.

2. **Clone the Repository**: Clone this repository to your local directory using Git or download the ZIP file and extract it.

3. **Setup Virtual Environment (Optional)**: Create a virtual environment to keep dependencies isolated:
   ```
   python -m venv myenv
   source myenv/bin/activate  # On Windows: myenv\Scripts\activate
   ```

4. **Install Dependencies**: Navigate to the project's root directory and install the required packages:
   ```
   pip install -r requirements.txt
   ```

5. **Run Migrations**: Apply the database migrations to set up the database:
   ```
   python manage.py migrate
   ```

6. **Create Superuser (Optional)**: To access the admin panel, create a superuser:
   ```
   python manage.py createsuperuser
   ```

7. **Run the Server**: Start the development server:
   ```
   python manage.py runserver
   ```

8. **Access the Website**: Open your web browser and visit `http://localhost:8000` to explore Niveel. If you created a superuser, access the admin panel at `http://localhost:8000/admin` to manage content.

9. **Stop the Server**: To stop the server, press `Ctrl + C` in the terminal where the server is running.

Now you can enjoy Niveel locally and experience the ease of navigating our services. For any feedback or issues, feel free to reach out to our team. Happy browsing!

**Note**: For production deployment, make sure to configure appropriate settings, such as setting `DEBUG=False`, updating `ALLOWED_HOSTS`, and serving static files using a proper web server or CDN.
