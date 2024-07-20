## simple_java_application_for_docker
A simple java application integrated with docker.

The Dockerfile simply compiles the Main.java file placed in src, and then will execute the Main function when the container will start.
To utilize this project, follow below steps:

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
