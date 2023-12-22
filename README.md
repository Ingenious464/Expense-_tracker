# Expense Tracker Project

## Overview
This Expense Tracker project is a web application developed using Python and Flask. It provides users with a simple yet efficient way to track their expenses, categorize spending, and gain insights into their financial habits.

## Features
- **User Authentication:** Secure user registration and login functionality.
- **Expense Logging:** Intuitive interface to log expenses with details like amount, category, and date.
- **Expense Categories:** Pre-defined and customizable categories for better organization.
- **Data Visualization:** Graphical representation of expenses to facilitate quick analysis.
- **Search and Filtering:** Robust search and filtering options for easy data retrieval.
- **Responsive Design:** Mobile-friendly interface for on-the-go expense tracking.

## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Ingenious464/expense-tracker.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd expense-tracker
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables:**
   - Create a `.env` file based on the provided `.env.example`.
   - Set your environment variables, including database connection details.

5. **Initialize the Database:**
   ```bash
   flask db init
   flask db migrate -m "Initial migration"
   flask db upgrade
   ```

6. **Run the Application:**
   ```bash
   flask run
   ```

7. **Access the Application:**
   Open your browser and go to [http://localhost:5000](http://localhost:5000)

## Project Structure
- `app/`: Contains the main application logic.
- `migrations/`: Manages database migrations.
- `templates/`: HTML templates for rendering pages.
- `static/`: Static files (CSS, JS, images, etc.).
- `tests/`: Unit tests for the application.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Thanks to the Flask community for providing a powerful and flexible web framework.
- Special thanks to [Chart.js](https://www.chartjs.org/) for the awesome charting library.

## Contact
For any inquiries or feedback, please contact us at [adetunjifataib@gmail.com](mailto: adetunjifataib@gmail.com).

Happy expense tracking! 📊💰
