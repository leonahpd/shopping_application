
**To Deploy a three-tier shopping application using Docker**

you need a setup that includes 

1. **Frontend (Web Layer):** Handles the user interface.
2.  **Backend (API):** Manages the request  from frontend and backend.
3.  **Database** : store the data
   

Below is a step-by-step guide:

![image](https://github.com/user-attachments/assets/8ac2e8af-ba1f-4380-858e-5184feb3beec)



**Prerequisites**

1. Install Docker and Docker Compose.
2. Have the application files ready (e.g., frontend code, backend configuration, database schema).
3.  Prepare a Docker network for inter-container communication **(Optional)**.

Step 1: Write **Frontend Dockerfile**  &  **Backend Dockerfile**

Step 2: Create **Application Files**
        Frontend (index.html)
        
        Frontend (app.js)
        
        Backend (app.py)
        
        Backend (requirements.txt)
        
Step 3: Write **docker-compose.yml**

Step 4: Deploy the Application

        cd shopping-app
        
Navigate to the shopping-app directory:

       docker compose up -d

Step 5: Access the Application

Open your browser and navigate to **http://localhost:8080** to view the shopping app frontend.
The frontend fetches product data from the backend via **http://backend:5000**


