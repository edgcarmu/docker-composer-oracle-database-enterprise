# docker-composer-oracle-database-enterprise


## How to run locally
- clone repo
- change CWD to root of repo

### Start you container
`docker-compose up -d --build`

### Check if it is running
 - `docker ps`

You should have a running Oracle Database in your system! To start creating schemas you should connect to your PDB and use system as your user. Default password is `Oradoc_db1`.