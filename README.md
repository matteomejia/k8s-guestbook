# k8s-guestbook

## Cosas

## Entregables

### Tarea 2.1

1. Se utilizó el siguiente comando para crear un cluster de 1 nodo

```
minikube start
```

- Una vez creado el cluster se ejecutó el comando ```kubectl cluster-info``` y se obtuvo lo siguiente:

![kubectl cluster-info](./images/command_01.png)

- Se puede apreciar más información con el comando ```minikube status```:

![minikube status](./images/minikube_status_01.png)

- Tambien se ejecutó el comando ```kubectl get nodes -owide``` y se obtuvo el siguiente resultado:

![kubectl get nodes -owide](./images/command_02.png)

### Tarea 2.2

1. Se utilizó el siguiente comando para crear un cluster multi-nodo

```
minikube start --nodes 3
```

- Una vez creado el cluster se ejecutó el comando ```kubectl cluster-info``` y se obtuvo lo siguiente:

![kubectl cluster-info](./images/command_03.png)

- Se puede apreciar más información con el comando ```minikube status```:

![minikube status](./images/minikube_status_02.png)

- Tambien se ejecutó el comando ```kubectl get nodes -owide``` y se obtuvo el siguiente resultado:

![kubectl get nodes -owide](./images/command_04.png)

### Tarea 2.3
Objetivo: Aplicación de reservas online.

Arquitectura: 

![arquitecture](./images/arquitecture.png)

Funcionalidad: Agendar una reserva (write) y leer reservas (read).

Herramientas: Go, MongoDB.

### Tarea 2.5
![flow_a](./images/flow_a.png)
