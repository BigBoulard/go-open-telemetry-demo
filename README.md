This code comes from www.komu.engineer: [The complete guide to OpenTelemetry in Golang](https://www.komu.engineer/blogs/11/opentelemetry-and-go.html)

The Golang code can be found in the `code` folder.  
To run the code;

```sh
./confs/certs.sh
docker-compose up --build
go run ./...

curl -vkL http://127.0.0.1:8081/serviceA
```
