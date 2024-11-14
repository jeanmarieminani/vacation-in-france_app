# Use the official Neo4j image as the base
FROM neo4j:latest

# Install Python and required packages
RUN apt-get update && apt-get install -y python3 python3-pip
RUN pip3 install neo4j python-dotenv

# Copy the Python script and .env file
COPY insert_places_in_france_to_DB.py /scripts/insert_places_in_france_to_DB.py
COPY .env /scripts/.env

# Set the working directory
WORKDIR /scripts

# Expose Neo4j ports
EXPOSE 7474 7687

# Start Neo4j and run the data loader script
CMD ["sh", "-c", "neo4j start && sleep 30 && python3 /scripts/insert_places_in_france_to_DB.py && tail -f /dev/null"]
