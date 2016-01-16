# minio-docker-backend
Minio S3 Backend for Docker Registry 

## Purpose

To be able to deploy Docker Registry privately with a S3 style backend.

## Ingredients 

1. Minio Server and CLI 
  
  - Minio server is currently using "us-east-1" as the default region. This is modified to allow for parameterized Minio server that cann accept custom "region" through CLI

2. Docker Registry with generic S3 Backend
  
  - Currently using the https://github.com/lorieri/distribution which has experimental support for generic S3 Backend
  - Uses "generic" as the Region name

