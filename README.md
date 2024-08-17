# How to Docker 

### Steps to run a docker container in your terminal and accessing the CLI

1) <b>Enable interaction (-i).
    ```
    docker run -i ubuntu:latest
    ```

2) Enable tty (-t).
    ```
    docker run -it ubuntu:latest
    ```

3) Custom container name (--name XynetContainer).
    ```
    docker run -it --name XynetContainer ubuntu:latest
    ```

4) Allow admin access to container (--cap-add=NET_ADMIN)
    ```
    docker run -it --name XynetContainer --cap-add=NET_ADMIN ubuntu:latest
    ```