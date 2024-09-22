# container-invocation
Infraestruturas em forma de contêineres prontas para uso em desenvolvimento


## Comandos Úteis do Docker

```sh
$ docker system prune -a # Tenta excluir tudo
$ docker volume rm $(docker volume ls -q --filter dangling=true) # Exclui todos os Volumes


```

### Imagens Disponíveis

- **posgres**
```
Postgres usando a localização _pt_BR_ usando o PgAdmin para Apoiar no desenvolvimento
   - Postgres na porta 5432
   - PgAdmin na Porta 8888
```
   
- **posgres-populated**
```
Postgres usando a localização _pt_BR_ usando o PgAdmin para Apoiar no desenvolvimento e criação de estruturas iniciais.
   - Postgres na porta 5432
   - PgAdmin na Porta 8888
```