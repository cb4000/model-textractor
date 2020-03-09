# model-textractor

So far all that exists is a local RDS to serve as a datastore. 

The current plan is to make a hexogonal architecture that stores content, extracts text, and displays it for users.

Currently using Environment Variables for storing secrets:
POSTGRES_DB
POSTGRES_USER
POSTGRES_PASSWORD


## Local Admin
navigate to local infrastructure folder, then run: docker-compose up
DB admin example :http://localhost:8086/?pgsql=db&username=postgres&db=postgres&ns=public

|Function   | Cloud Functionality | Local Implementation  | AWS Implementation   |  CI / CD      |    Tests       |
|-----------|---------------------|-----------------------|----------------------|---------------|----------------|
|Main DB    | Not Implemented     | Postgres              | Not Implemented      |Not Implemented|Not Implemented |
|TBD        |