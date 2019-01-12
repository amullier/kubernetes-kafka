## Initialisation des storages classes

```sh
kubectl apply -f ./storage-classes/
```

## Initialisation du namespace

```sh
kubectl apply -f namespace.yml
```

## Initialisation de Apache ZooKepper

```sh
kubectl apply -f zookeeper
```

## Initialisation de Apache Kafka

```sh
kubectl apply -f kafka
```
