# FastAPI Backend

This is the Python backend for the application, built with FastAPI. It is configured to accept CORS requests from a Vite React frontend running on port 5173.

## Prerequisites

* Python 3.8+
* pip

## Setup & Installation

1.  **Create a virtual environment** (recommended to keep dependencies isolated):
    ```bash
    # Windows
    python -m venv venv
    .\venv\Scripts\activate

    # macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

2.  **Install dependencies**:
    ```bash
    pip install fastapi uvicorn
    ```
    *(If you have a `requirements.txt` file, run `pip install -r requirements.txt` instead)*

## Running the Server

Start the development server with live reloading:

```bash
uvicorn main:app --reload