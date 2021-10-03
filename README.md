# docker-composer-oracle-database-enterprise

## How to run locally

- clone repo
- change CWD to root of repo

### Settings
`
./docker/ora.conf`

- DB_SID=ORCLCDB
- DB_PDB=orclpdb1


### Start you container

```bash
docker-compose up -d --build
```

### Check if it is running

```bash
docker ps
```

- Your container should provide “health: starting” as status. After a few minutes it should go live and the status
  changes to “healthy”.

And that's it!! You should have a running Oracle Database in your system! To start creating schemas you should connect
to your PDB and use system as your user. Default password is **Oradoc_db1**.