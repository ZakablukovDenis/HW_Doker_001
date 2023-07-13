### Сборка образа

```
sudo docker build . --tag=homework_docker_img
```

### Запуск контейнера

```
sudo docker run --name=homework_docker_cont -d -p 5555:80 homework_docker_img
```
