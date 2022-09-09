
## Dockerfile

Pull ubuntu image from docker hub.

```sh
 FROM ubuntu
```

Update and install apt-get 

```sh
RUN apt-get update && apt-get install -y
```
Install python latest version

```sh
RUN apt install python3 -y
```

Install wget

```sh
RUN apt install wget -y
```

install unzip 

```sh
RUN apt install unzip -y
```

Print python version

```sh
ENTRYPOINT [ "python3", "--version" ]
```
