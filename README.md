**Project documentation, installation steps, 
usage instructions, and any other relevant information**

**1. Description**
The main purpose of this project is to build a Holiday_FastAPI. we  developed two apps: vacation-in-f>
The vacation-in-france_app: Focuses on fetching attractions and "things to do" based on user context
The holiday_route_app: handles route planning and user statistics
Our containers adopted isolation and scalability principles, if one app fails it won’t affect the oth>
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

### Pushing the Docker Image to GitHub

Sharing the Docker image itself on GitHub directly is not necessary since Docker images are typically stored on Docker Hub. However, you can include the link to your Docker Hub image in your `README.md` file as shown above.

By following these steps, you'll be able to share your project and Docker image information on GitHub effectively. If you have any more questions or need further assistance, feel free to ask! 😊🚀

Is there anything else you'd like to review or adjust? 🚀

