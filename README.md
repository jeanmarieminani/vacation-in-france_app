**Project documentation, installation steps, 
usage instructions, and any other relevant information**

**1. Description**
The main purpose of this project is to build a Holiday_FastAPI. we  developed two apps: vacation-in-france and and holiday-route-app
The vacation-in-france_app: Focuses on fetching attractions and "things to do" based on user context
The holiday_route_app: handles route planning and user statistics
Our containers adopted isolation and scalability principles, if one app fails it won’t affect the other

# Holiday FastAPI Neo4j
This repository contains the Docker configuration and scripts for the Holiday FastAPI project using Neo4j. 

## Files 
- `insert_places_in_france_to_DB.py`: Script to load data into Neo4j from a CSV file. - 
`.env`: Environment variables (not included for security). 
- `neo4j_DB/Dockerfile`: Dockerfile for building the Neo4j image. 
- `docker-compose.yml`: Docker Compose file to orchestrate the services. 

## Usage 1. **Build and Run the Docker Containers**: ```bash docker-compose up --build

**2. Access Neo4j**

Open your browser and go to http://localhost:8383 to access the Neo4j browser.

**3. Docker Image **
The Docker image is available on Docker Hub: minani/neo4j_db_for_holiday_fastapi

## Clone the Repository

```bash
git clone https://github.com/your-username/holiday-fastapi-neo4j.git
cd holiday-fastapi-neo4j

**4. License**
This project is licensed under the MIT License. See the LICENSE file for more details.





