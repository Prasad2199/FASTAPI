

create a virtual environment

virtualenv env

source env/bin/activate

installation

Install FastAPI. make sure your environment is activated

pip install fastapi

Also, install uvicorn to work as the server

pip install "uvicorn[standard]"

Install package for database support

pip install sqlalchemy

To run the FastAPI app type the following command and hit enter

uvicorn main:app --reload