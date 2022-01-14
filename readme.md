# Kubernetes
![Okteto](https://cloud.okteto.com/#/login)
## Preparation
- Install kubectl
- Register di [Okteto](https://cloud.okteto.com/#/login)
- Download [Lens](https://k8slens.dev/) (optional)

## List syntax yang digunakan

- Untuk melakukan create
```sh
    kubectl apply -f <nama-file>
```

- Untuk melakukan delete
```sh
    kubectl delete -f <nama-file>
```

- Untuk mendapatkan detail informasi pada object tertentu
```sh
    kubectl describe <jenis> <nama-object>
```

- Untuk melihat daftar object
```sh
    kubectl get <jenis>
```