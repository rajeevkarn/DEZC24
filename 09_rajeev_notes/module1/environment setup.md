
1) Repo
 
 Create git fork of the course repo
 Create a branch of the main branch
 Open the repo in VS Code
 Add note folder
 

 2)

 check --> git config --global user.name
 check --> git config --global user.email

 git config --global user.email “mailid”

git config -–global user.name “RK"


3) dcocker 

docker run -it python:3.9
docker run -it --entrypoint=bash python:3.9



python -m ensurepip --default-pip
 
pip install --upgrade pip

python.exe -m pip install --upgrade pip

pip install "psycopg[binary,pool]"

pip install pgcli
pip install pandas
pip install pyarrow
pip install sqlalchemy
pip install psycopg2





docker run -e POSTGRES_USER="root" -e POSTGRES_PASSWORD="root" -e POSTGRES_DB="ny_taxi" -v ${pwd}/ny_taxi_postgres_data:/var/lib/postgresql/data -p 5432:5432 postgres:13

docker run -it -e POSTGRES_USER="root" -e POSTGRES_PASSWORD="root" -e POSTGRES_DB="ny_taxi" -v ${pwd}/ny_taxi_postgres_data:/var/lib/postgresql/data -p 5432:5432 postgres:13

docker run -e POSTGRES_HOST_AUTH_METHOD=trust postgres:13

pgcli -h localhost -p 5432 -u root -d ny_taxi


## list all docker images - docker ps
## kill all docker images -- docker kill $(docker ps -q)




