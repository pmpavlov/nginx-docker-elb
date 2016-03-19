# Nginx

This repo sets up Nginx and in a Single Docker Elastic banstalk. It includes a `Dockerrun.aws.json` file which means it can be zipped and uploaded to AWS ElasticBeanstalk for turnkey operation.

## Required Environment Variables

Sensitive data has been removed from the repo, as such you need to set these environment variables from within ElasticBeanstalk:

 - `NGINX_SERVER_DOMAIN` - The FQDN of the ElasticBeanstalk instance
