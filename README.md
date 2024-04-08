# Scaling Infrastructure as Code on Google Cloud Platform - playersearch function

The Google Cloud Platform facing cloud infrastructure demo code for the Google Next '24 talk "Scaling Infrastructure as Code: Proven Strategies and Productive Workflows".  

This is the repo is for the playersearch function.  By default it uses a Node.js function that has the permissions and roles to connect to the Game services' datastore on a read level.

To enable automatic releases on Github for this app:

1. Go to this Repository Settings
2. Go to Actions -> General
3. Under Workflow Permissions enable "Read and Write Permissions" for github actions