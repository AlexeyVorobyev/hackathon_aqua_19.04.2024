## Команды для работы с GIT

```shell
# git submodules clone
git submodule update --init --recursive
```

```shell
# git submodules update
git submodule update --recursive --remote
```
## Команды для запуска Docker Compose
### Main
```shell
# custom network creation
# you should write subnet for your custom network
docker network create --subnet=10.14.0.0/16 dev-network-hackathon-aqua-19-04-2024
```

### Auth
```shell
# custom network creation
# you should write subnet for your custom network
docker network create --subnet=10.5.0.0/16 dev-network
```