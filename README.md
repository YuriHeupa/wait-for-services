# Wait for services

wait-for-services is a script to wait for a single or multiple services to become available, which hold on until container responds on specified address/port pairs.

You can use it like:

```
docker run --rm -it yuriheupa/wait-for-services <service1_address> <service1_port> <service2_address> <service2_port> && <other command>
```