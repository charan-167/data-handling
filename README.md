# Hospital Resource Optimization & Patient Flow Management System

This is a full-stack analytical web platform tailored for hospitals, helping them manage resources effectively, prevent emergency department overload, cluster departments by demand, and forecast future admission trends.

## Features
- **Patient Data Upload:** Structure data effectively using pandas.
- **Emergency Overload Analysis:** Recognize peak waiting times.
- **Resource Clustering:** Classify overall hospital demand.
- **Demand Forecasting:** Forecast patient inflow seamlessly.
- **Dynamic Analytical Dashboard:** Visual representation using tailored chart components.

## Application Architecture

The project contains two separate directories:

1. `frontend/` - Built with **React** and **Vite**, using Vite's fast local development server.
2. `backend/` - Built with **FastAPI** (Python), executing data management operations via Pandas, Scikit-Learn, and statsmodels.

---

## How to Run locally

### 1. Start the Frontend
The frontend requires Node.js installed on your machine.
Navigate to the frontend folder and run the developer server using npm:

```bash
cd frontend
npm install
npm run dev
```

This will deploy the React application locally, which usually defaults to `http://localhost:5173`.

### 2. Start the Backend API
The backend requires Python available on your machine.
Navigate to the backend folder and start the API with Uvicorn:

```bash
cd backend
# Activate the virtual environment if applicable:
# .\venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

The FastAPI application will start on `http://localhost:8000`. You can test API endpoints from its interactive documentation page at `http://localhost:8000/docs`.



# data-handling
