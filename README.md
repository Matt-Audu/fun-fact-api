# Fun Fact API(Number Classification)

## Prerequisites

- Install python 3.8+

## Features

- **Number Classification:**  
  - Determines if the number is an Armstrong number.
  - Checks if the number is prime.
  - Checks if the number is a perfect number.
  - Calculates the digit sum.
  - Classifies the number as odd or even.
- **Fun Fact Integration:**  
  - Retrieves a fun math fact from the Numbers API.
- **CORS Enabled:**  
  - Allows cross-origin requests.
- **Static File Handling:**  
  - Serves a favicon from the static directory.

## Project Structure

- **main.py:** Contains all the API logic, endpoints, and helper functions..
- **static/favicon.ico:** A favicon file to serve for the endpoint `/favicon.ico`.
- **requirements.txt:** Lists required packages and their versions.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Matt-Audu/fun-fact-api  
    ```

2. **Create and activate a virtual environment::**
    ```
    python -m venv venv
    ```
    ```
    On macOS/Linux:
    source venv/bin/activate
    ```
    ```
    On Windows:
    venv\Scripts\activate

    ```

3. **Install dependencies:::**

    ```
    pip install -r requirements.txt      

    ```  

# Local Development
Ensure you have the static directory and a favicon.ico file in it.

Run the application using Uvicorn:
```
uvicorn main:app --reload
```

# Access the API: 

Root endpoint: http://127.0.0.1:8000/  

API endpoint: http://127.0.0.1:8000/api/classify-number?number=371