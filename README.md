# Elastic Search BIBBOX application
can be installed as [BIBBOX APP](https://bibbox.readthedocs.io/en/latest/ "BIBBOX App Store") or standalone. 

* initial user/passwordd: **admin / admin**
* After the installation follow these [instructions](INSTALL-APP.md)

## Standalone Installation

Clone the github repsoitory. If necessary change the ports and volume mounts in `docker-compose.yml`.  

```
git clone https://github.com/bibbox/app-elasticstack
cd app-elasticstack
mkdir data
docker-compose up -d
```

The main app can be opened at 

```
http://localhost:9300
```



