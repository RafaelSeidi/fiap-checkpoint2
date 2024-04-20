# fiap-checkpoint2
### Docker

* Execução em DES

```
docker run -d -p 8080:8080 -e PROFILE=dev rafaelseidi/fiap-checkpoint2
```

* Execução em STG

```
docker run -d -p 8080:8080 -e PROFILE=stg rafaelseidi/fiap-checkpoint2
```

* Execução em PRD

```
docker run -d -p 8080:8080 -e PROFILE=prd rafaelseidi/fiap-checkpoint2
```