Docker:
    $ docker build -t container-name .
    $ docker run -v "$(pwd)":/app container-name
    $ docker ps -q -a | xargs docker rm


Reference:
