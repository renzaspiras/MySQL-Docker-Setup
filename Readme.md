# MySQL Docker Guide

## Step 1: Pulling the Mysql Image

```bash
docker pull mysql:latest
```

## Step 2: Creating a container and running it

```bash
docker run --name mysql-container -e MYSQL_ROOT_PASSWORD=1234567890 -p 6969:3306 -d mysql:latest
```

## Step 3: Test Run

```bash
mysql -h 127.0.0.1 -P 6969 -u root -p
```
