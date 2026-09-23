Task 03 — Docker Security

No.	Requirement	How It Was Completed	Screenshot	Status
1	.dockerignore	Created .dockerignore to exclude unnecessary files such as node_modules, .git, and environment files.	01-dockerignore.png	✅ Completed
2	Secure Dockerfile	Used Alpine-based Node.js and Nginx images with a multi-stage Docker build.	02-secure-dockerfile-final.png	✅ Completed
3	Secure Image Build	Successfully built the secure Docker image using docker build.	03-secure-image-build.png	✅ Completed
4	Docker Image Verification	Verified the naren-kanban-secure:1.0 image using Docker image listing.	04-docker-image.png	✅ Completed
5	Container Deployment	Started the secure container and exposed the application on port 8080.	05-container-running.png	✅ Completed
6	Non-Root User	Configured the container to run as appuser instead of the root user.	06-non-root-user.png	✅ Completed
7	Application Verification	Verified that the Kanban application runs successfully in the browser.	07-browser-app.png	✅ Completed
8	Security Scan	Scanned the Docker image using Trivy. The scan reported 0 vulnerabilities and 0 secrets.	08-security-scan.png	✅ Completed

# Screenshots

01-dockerignore.png

02-secure-dockerfile-final.png

03-secure-image-build.png

04-docker-image.png

05-container-running.png

06-non-root-user.png

07-browser-app.png

08-security-scan.png

Task 03 Status

✅ TASK 03 COMPLETED
