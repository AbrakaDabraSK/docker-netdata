# Using docker compose yml to run netdata
Using docker compose yml to run netdata.


## Make .env file

```shell
cp .env.example .env
```

## Edit .env file (vim, nano.. your favorite choice)

Open enviroment file

```shell
vim .env
```

Edit default enviroment file if u need

```shell
NETDATA_LOGIN_USER=<username>
NETDATA_LOGIN_PASSWORD=<password>
```

Execute quit and save changes command, then press ENTER

```shell
:wq!
```

## Run

```shell
docker-compose up -d
```

## Down

```shell
docker-compose down
```

## Check

```shell
docker-compose ps
```

## Visit 

```shell
http://host-ip:1919
```
