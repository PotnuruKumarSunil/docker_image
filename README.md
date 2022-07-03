# Docker Image

This repository contains docker image used with configured apache server for blogs and websites hosting.
This image is configured especially for hosting webservers in any oragnization, which basically comes with apache server so that pods in case of k8's or containers in case of docker can be used to relaunch the server if any faulty happens in real world.


### To Use the Image
Prerequisites: Docker service should be installed in your OS.

Run the following COMMANDS:\
To check whether you have docker service enabled
   ```sh
   systemctl status docker
   ```
To download the image
   ```sh
   docker pull sunilpotnuru/centos:7
   ```
To check whether the image is downloaded:
   ```sh
   docker images | grep sunilpotnuru/centos:7   
   ```
