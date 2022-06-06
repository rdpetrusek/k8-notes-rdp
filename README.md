## Docker Run
### Start a container, and make it run indefinitely
`docker run -d -t -i --name='cantstop-wontstop' kong:latest sh -c "while true; do sleep 2000; done"`
### Environment variables
`docker run -e KONG_DATABASE='postgres' -e KONG_PG_HOST='taco-db' -e KONG_PG_USER='taco' -e KONG_PG_PASSWORD='taco' -e KONG_PG_DATABASE='taco-db' --network='taco-net' kong:latest`
