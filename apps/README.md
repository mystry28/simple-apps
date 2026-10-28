# Create env variable

```
vim .env
```

```
DB_NAME=training
DB_HOST=ipaddress
DB_USER=peserta
DB_PASS=password
APP_PORT=3000
```
sonar-scanner \
  -Dsonar.host.url=http://172.23.13.91:9000 \
  -Dsonar.token=sqp_8a521704f66532ad87e8933d7e161431aea096fc \
  -Dsonar.projectKey=simple-apps