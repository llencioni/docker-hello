## docker-hello
Docker very simple project with a Javascript application.

# Fist steps

1) Install Docker in your computer (MacOS and Windows should use the Docker Desktop instalation)

2) Check if Docker was correctly installed:
```
   $ docker version
```
4) Check if there is any Docker container running or stopped:
```
   $ docker ps -a
```
6) Clone this repository

7) Check to guarantee there's no node previously installed (you should see an error because node is not installed):
```
   $ node app.js
```
5) Build the Docker Image (_docker-hello_)
```
   $ docker build -t docker-hello .
```
7) Check if the Docker Image is really available in the computer
```
   $ docker images
```

| REPOSITORY  | TAG    | IMAGE ID  | CREATED        | SIZE  |
| ----------  | ------ | --------- | -------------- | ----- |
|docker-hello | latest | xxxxxxxxx | 36 seconds ago | 181MB |

8) Run the Docker Image (create the **Docker Container**)
```
   $ docker run docker-hello
```
9) You should see:
```
   $ Hello Docker
```


# Some references:

https://www.youtube.com/watch?v=pTFZFxd4hOI&list=PLCD3diFGpOGz_8f_v6mRu-r5s5ufRVirJ&index=2

https://www.youtube.com/watch?v=pg19Z8LL06w

https://www.geeksforgeeks.org/execution-of-c-program-using-docker-environment/












