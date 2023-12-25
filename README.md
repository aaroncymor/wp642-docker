# Wordpress 6.4.2 running on Docker

## Installing and Setting Up
### 1. Create an .env file
```bash
vi .env
```

### 2. Add the following
```
MYSQL_ROOT_PASSWORD=<your_root_password>
MYSQL_DATABASE=<your_db_name>
MYSQL_USER=<your_db_user>
MYSQL_PASSWORD=<your_db_pass>
```

### 3. Run docker-compose
```bash
docker-compose up -d
```

### 4. Go to your themes folder
```bash
cd wordpress/wp-content/themes
```

### 5. Install tailpress for custom theme
Follow steps here: https://tailpress.io/

### 6. Run npm-watch
```bash
npm run watch
```

### 7. Activate custom theme in wordpress admin
