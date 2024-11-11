Welcome to my Astronomer project! This was set up with astro dev init using the Astronomer CLI. Here’s a quick guide to what’s included and how to run Apache Airflow locally.

Project Structure

dags: Contains Python files for Airflow DAGs, including an example DAG that queries the Open Notify API to list astronauts currently in space.
Dockerfile: Uses an Astro Runtime Docker image for running Airflow. Add any runtime overrides here.
include: Holds additional files you might want in the project.
packages.txt: List OS packages for installation here.
requirements.txt: Specify Python packages here.
plugins: Add custom Airflow plugins here.
airflow_settings.yaml: Define Airflow connections, variables, and pools locally.
