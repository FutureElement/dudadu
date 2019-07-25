### Deploy Mongo DB
```bash
docker stack deploy ddd --with-registry-auth --compose-file docker-compose-mongodb.yml
```
Visit ```http://localhost:8081```or```http://host-ip:8081``` (as appropriate).

### Deploy Consul
```bash
docker stack deploy ddd --with-registry-auth --compose-file docker-compose-consul.yml
```