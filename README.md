💸 Expense Management System
A full-stack Python application that empowers users to track, manage, and analyze their expenses seamlessly. Leveraging FastAPI for a high-performance backend and Streamlit for an intuitive frontend, this system offers real-time insights into your spending habits.
LinkedIn

🚀 Features
Expense Recording: Add, update, or delete expenses with details like amount, category, and notes.

Analytics Dashboard: Visualize spending patterns through interactive charts and summaries.

Data Export: Download expense reports in CSV or Excel formats.

User Authentication: Secure login and user management system.

Responsive UI: Streamlit-powered interface for real-time interaction.

## Project Structure

- **frontend/**: Contains the Streamlit application code.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
