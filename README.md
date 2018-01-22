# go-udp
simple go UDP client and server

### 
docker build -t goudp:latest . 

### Start the sever
`docker run -p 10001:10001/udp -it --rm --name goudp goudp:latest`

Make sure /udp on the [port](https://docs.docker.com/engine/reference/commandline/port/) option,
    
    docker port CONTAINER [PRIVATE_PORT[/PROTO]]


### Start the client
`go run client.go`

Output on the Server should be 

    Received  0  from  172.17.0.1:44373

    Received  1  from  172.17.0.1:44373

    Received  2  from  172.17.0.1:44373

    Received  3  from  172.17.0.1:44373

    Received  4  from  172.17.0.1:44373

