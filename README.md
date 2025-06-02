# surfplanner-deployment


## local startup
### (needs a mysql database)

### backend
```bash
cd backend
DATABASE_URL=mysql+pymysql://admin:admin@localhost/surfplanner uvicorn main:app --reload --host 127.0.0.1 --port 8000
```
### frontend
```bash
cd frontend
npm start
```

## docker startup
### (needs docker installed)
```bash
docker compose down
docker compose build
docker compose up
```
