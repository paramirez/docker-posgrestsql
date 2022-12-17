Execute dump or script in db

```
docker exec -it --user postgres <container-id> /bin/bash
su - postgres
cd /scripts
psql -d <dbname> -a -f <file>.sql
```
