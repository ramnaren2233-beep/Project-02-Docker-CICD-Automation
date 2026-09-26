
## Task 5 – AWS Infrastructure

| No. | What I Did | Implementation | Status |
|---:|---|---|---|
| 1 | Launched an EC2 instance using Amazon Linux 2023 | Created and configured the AWS EC2 server | ✅ Done |
| 2 | Installed Docker on the EC2 instance | Installed Docker and verified the Docker service | ✅ Done |
| 3 | Installed Jenkins on the EC2 instance | Installed Jenkins and configured the Jenkins service | ✅ Done |
| 4 | Configured the Security Group with required ports – 22, 8080 and 80 | Allowed SSH, Jenkins and application traffic | ✅ Done |
| 5 | Started and verified Jenkins service as Active (running) | Verified Jenkins using `systemctl status jenkins` | ✅ Done |
| 6 | Verified Jenkins UI through port 8080 | Accessed Jenkins using the EC2 Public IP and port 8080 | ✅ Done |
| 7 | Started and verified the Docker application container | Started the application container and verified using `docker ps` | ✅ Done |
| 8 | Verified the Kanban Task Manager application through port 80 | Accessed the application using the EC2 Public IP on port 80 | ✅ Done |
| 9 | Verified Jenkins and the running Docker application container on the same EC2 instance | Confirmed Jenkins and the Docker container are running on the same EC2 server | ✅ Done |

### Screenshots

| Screenshot | Evidence | Status |
|---:|---|---|
| 1 | EC2 Instance – Amazon Linux 2023 | ✅ |
| 2 | Security Group – Required Ports | ✅ |
| 3 | Docker Installation | ✅ |
| 4 | Jenkins Installation / Status | ✅ |
| 5 | Jenkins UI – Port 8080 | ✅ |
| 6 | `docker ps` – Running Container | ✅ |
| 7 | Docker Port Mapping `0.0.0.0:80->80/tcp` | ✅ |
| 8 | Kanban Task Manager via EC2 Public IP | ✅ |

### Task Status

**✅ Task 5 – AWS Infrastructure: COMPLETED**
