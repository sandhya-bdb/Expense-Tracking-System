# Expense Management System

An expense tracking system is a tool or software designed to help individuals or organizations monitor, record, categorize, and analyze their spending. This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server. FastAPI is a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints, whereas Streamlit is a tool that transforms Python scripts into interactive web apps in minutes, instead of weeks. Build dashboards, generate reports, or create chat apps.




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
