# Assignment 1c part 1 for COMP 3940

## Setup

1. Download [tomcat 10](https://tomcat.apache.org/download-10.cgi).

2. Unzip tomcat to a known location.

3. For ease of use, rename the unzipped tomcat to **tomcat**.

4. In the `~/tomcat/webapps` directory clone this repository.

5. Install Docker desktop https://www.docker.com/products/docker-desktop/

## Note: the following steps below assume a windows installation.

6. Install cygwin https://www.cygwin.com/

7. In cygwin type: `cd /cygdrive/path/to/tomcat/webapps/dockerhits`

8. Next, type `docker build -t hits .`

9. Then, type `docker run -p 8081:8080 hits`

10. Finally, go to your browser and type http://localhost:8081/hits/dockerhits to access the page.

## Contributors

- Jimmy Tsang
