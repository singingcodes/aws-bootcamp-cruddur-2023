# Week 1 — App Containerization
 - This week, I continued working on the Github repository from last week.  I learned abot Docker. Docker is a platfprm for building, runnung, and shipping applications in a consistent manner
 
 - I configured the Gitpod.yml configuration file to install some Visual Studio Code extensions that I find useful for my development workflow. I added the extensions [openai, postgresql] to the configuration file.

- After configuring the workspace,  I  explored the codebases of both frontend and backend to get a better understanding of the application's architecture and functionality.

- To ensure that I could run the apps locally, I followed the instructions in the README files for each repository. I had to install all the dependencies in the package.json file of the react application, before I could run the applications.

- Once I had both apps running locally, I decided to create a Dockerfile for each app. I followed best practices and included only the necessary files and dependencies in each image.

- After creating the Dockerfiles, I ensured that I could get the apps running via individual containers. I used the command "docker run" to start each container and verified that the apps were still working as expected.

- Next, I created a docker-compose file to orchestrate multiple containers to run side by side. I specified the configuration for each service, such as the image name, port mapping, and environment variables.

- I was able to add notifications endpoint on the backend and notifications page on the frontend

- I wanted to be able to make changes to the code while I was coding. I mounted the directories containing the code into each container so that changes would be reflected immediately.

- I was also able to install docker locally on my machine and got some containers running

- I learned the 10 Docker Security best practices listed below
  - Keep host and Docker updated to latest security patches.
  - Docker daemon and containers should run in non-root user mode.
  - Image vulnerability scanning.
  - Trusting a private vs public image registry
  - No sensitive data in Dockerfiles or images.
  - Use secret management services to share secrets.
  - Read only file system and volume for Docker
  - Separate databases for longterm storage
  - Use DevSecOps practices while building application security
  - Ensure all code is tested for vulnerabilities before production use






