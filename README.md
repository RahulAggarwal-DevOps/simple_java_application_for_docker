# simple_java_application_for_docker
Simple java application integrated with docker

1. Build the docker image:
   ~~~
   $ docker build -t java-image:v1 .
   ~~~

2. Verify in docker images:
   ~~~
   $ docker images
   ~~~

3. Create and run a container with this image:
   ~~~
   $ docker run java-image:v1
   ~~~

4. Output should be like:
   ~~~
   "Hello, Docker! Current date: Sat Jul 20 17:59:11 GMT 2024"
   ~~~
