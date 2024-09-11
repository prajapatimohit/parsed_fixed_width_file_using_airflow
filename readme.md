# Airflow Project: Fixed-width File Parser

## Setup Instructions

1. **Install Docker** if it's not installed on your system: [Docker Installation Guide](https://docs.docker.com/get-docker/).
   
2. **Clone this repository** to your local machine:
   ```bash
   git clone <repository-url>

3. **Navigate to the project directory:**
    ```bash
    cd airflow_project

4. **Build and run the Docker containers:**
    ```bash
    docker-compose up -d --build

5. **Access the Airflow UI:**
    Go to http://localhost:8080 in your browser.
    Use the default credentials airflow/airflow to log in.

6. **Trigger the DAG:**
In the Airflow UI, navigate to the DAGs page and manually trigger the parse_fixed_width_to_csv DAG.

7. **Check the output:**

The output CSV file will be available inside the dags folder of the Airflow container at /opt/airflow/dags/output_file.csv.