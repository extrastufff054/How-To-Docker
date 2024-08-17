# How to Docker 

### Steps to run a docker container in your terminal and accessing the CLI

* Open a terminal/ powershell/ command prompt according to your operating system and write the below commands as per your requirement. 
* Ensure <b>Docker Desktop</b> is open.

1) Enable interaction (-i).
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

* If you want to access your Docker Container using <b>VS-Code</b> you can follow the below steps : 

    * Once your container is running, you can attach VS Code to it:
    * Open the Command Palette in VS Code (F1 or Ctrl + Shift + P).
    * Type and select Dev-Containers: Attach to Running Container....
    * Choose your running container from the list.

    Note : You will require the [Dev-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) and [Docker extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) in VS-Code.

    