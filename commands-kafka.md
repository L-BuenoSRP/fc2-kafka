comandos usados dentro do container do kafka, apos entrar com docker exec

cria o topico e nome teste com 3 partitions no server
```
kafka-topics --create --topic=teste --bootstrap-server=localhost:9092 --partitions=3
```

Lista os topicos disponiveis no server

```
 kafka-topics --list --bootstrap-server=localhost:9092
```