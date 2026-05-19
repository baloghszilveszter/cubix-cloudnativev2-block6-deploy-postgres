# Cubix Cloud-Native Application Development Training: cloud-native requirements (PostgreSQL deployment)
Fork this repository for the practice session.

## How to start the Chart

Replace password setting.

```shell
helm upgrade postgresql bitnami/postgresql --version 14.2.3 -n cubix --create-namespace --set auth.password=<ENTER-PASSWORD> -f values.yaml --install
```
