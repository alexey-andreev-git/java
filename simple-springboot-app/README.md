# Simple Spring Boot Application - A Quick Start Guide

It is an approach to develop spring based application with very less configuration. 
It provides defaults for code and annotation configuration to quick start new spring projects within no time.

Spring Boot automatically configures required classes depending on the libraries on its classpath.

A spring boot application can be created in three different ways

    Spring boot initialize web interface

    Spring boot CLI

    Spring boot using spring tool suite IDE

# Content of Quick Start Guide

 - @ExceptionHandler
 - @ControllerAdvice
 - @RestControllerAdvice
 - @ResponseBody
 - application.yaml
 - Interceptor
 - @Component
 - @Service
 - @Repository
 - @Configuration
 - @Bean
 - @Value
 - @ConfigurationProperties
 - How to use multiple Yaml Files
 - @Autowired
 - @Qualifier
 - @Primary
 - @Required
 - Autowire by Properties / Autowire by Name
 - Autowire by Setter / Autowire by Type
 - Autowire by Constructor

# .gitlab-ci.yaml
#
# This GitLab CI configuration file is used to automate the deployment of an application to a Kubernetes cluster.
# It defines the stages, jobs, and scripts necessary to build, test, and deploy the application.
#
# Stages:
# - build: Compiles the application and prepares it for deployment.
# - test: Runs unit tests and integration tests to ensure the application is functioning correctly.
# - deploy: Deploys the application to the Kubernetes cluster.
#
# Jobs:
# - build: Uses a Docker image to compile the application and create a Docker image for deployment.
# - test: Executes test scripts to validate the application.
# - deploy: Uses kubectl to apply Kubernetes manifests and deploy the application to the cluster.
#
# Variables:
# - KUBERNETES_NAMESPACE: The namespace in the Kubernetes cluster where the application will be deployed.
# - KUBERNETES_CLUSTER: The Kubernetes cluster to which the application will be deployed.
# - DOCKER_IMAGE: The Docker image repository and tag for the application.
#
# This configuration ensures that the application is built, tested, and deployed in a consistent and automated manner.