# Jenkins JNLP Java Build agent

Dockerfile for a simple JNLP Java build agent for Jenkins. Based in part on https://github.com/cloudbees/java-build-tools-dockerfile but with less tools and JDK 11. \
Contains the following build tools:
* Java 11
* Maven 3.6.3
* Kubectl v1.18.0
* Jmeter 5.3

### Usage
Build the image with: \
```docker build . -f jenkins-build-slave-dockerfile --tag jenkins-build-slave``` \
Or pull the image from Dockerhub: \
```docker pull woutervanderlinde/jenkins-build-slave:jdk-11```
