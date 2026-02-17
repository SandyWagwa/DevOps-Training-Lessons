(By Joseph-njogu - 0799551696)
Install LINUX- About 60GB needed

Virtues of a programmer
1. Laziness- The quality that makes you go to great effort to reduce overall energy expenditure. It makes you write labor-saving programs that other people will find useful and document what you wrote so you don't have to answer so many questions about it.
2. Impatience- The anger you feel when the computer is being lazy. This makes you write programs that don't just react to your needs, but actually anticipate them. Or at least pretend to.
3. Hubris- The quality that makes you write (and maintain) programs that other people won't want to say bad things about.

*Learn about the Secure Shell (ssh)
PAT -For a service and service .For example, Jetkins and Github

How to create ssh keys- (https://www.google.com/search?q=how+to+create+ssh+keys&rlz=1C1MMCH_enKE1182KE1183&oq=how+to+create+ssh+keys&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIKCAEQABixAxiABDIHCAIQABiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCTU3NjBqMGoxNagCCLACAfEFuEgoaFzsD5A&sourceid=chrome&ie=UTF-8).

.git-To store the history of what is being stored in the directory.(This directory contains all the necessary metadata, objects, references (branches and tags), and configuration files for the repository's history.
)

JWT Tokens most start with ey

Advanced Commands- Git Rebase
-Git Ref log
-Git grep
-Git Config list
-Git Config ls
-Git Config --list

History on LINUX (To get the history of what you were doing.)
Command to write when looking for a specific thing in history- history | grep "docker"

GitHub/GitLab- GitHub and GitLab are both web-based platforms used for version control and collaborative software development using Git. 

Scrum happens in sprint while Kanban no sprints. Scrum is most efficient is Kanban since it is doen continuously... 
Timeframes is to know when the sprints should happen. Research about Odoo.
Explore more on GitLab
Look at issues in Gitlab

In LINUX what does ps -aux do...

TLS and SSL - SSL (Secure Sockets Layer) and TLS (Transport Layer Security) are security protocols used to encrypt data sent over the internet so that hackers or third parties cannot read it.

Ingress

Ingress = Incoming traffic

It refers to data entering a network, server, or system.

Examples

A user opening your website

Receiving an email

Download requests coming into a server

API requests from outside users

Think of Ingress as “IN-coming.”

Egress

Egress = Outgoing traffic

It refers to data leaving a network, server, or system.

Examplese ingress traffic


Sending an email

Uploading files to the internet

Streaming a video to users

Server responses going out

Think of Egress as “EXIT / OUT-going.”


Docker Compose and Kubernetes
- Docker Compose is a tool for defining and running multi-container Docker applications on a single host. It uses a YAML file (docker-compose.yml) to describe services, networks, and volumes.

Example: 
version: '3'
services:
  web:
    image: nginx:latest
    ports:
      - "8080:80"
  db:
    image: mysql:5.7
    environment:
      MYSQL_ROOT_PASSWORD: example


- Kubernetes is a container orchestration platform designed for running and managing containerized applications at scale across multiple hosts (clusters).

Example: apiVersion: apps/v1
kind: Deployment
metadata:
  name: nginx-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: nginx
  template:
    metadata:
      labels:
        app: nginx
    spec:
      containers:
        - name: nginx
          image: nginx:latest
          ports:
            - containerPort: 80

Cloud server can be accessed using HTTP and HTTPS..

Git Bisect- Read on it

MTTR (Mean Time to Recover)

CI/CD (Continuous Integration/Continuous Deployment)
How to achieve- Testing (Unit Testing)


GitlabCI
Code coverage =100% ->Write more unit tests
Implement CI on Github (CircleCI)

Commit message=Subject and the body

Write more tests nad implement CI (Min of 4 commits and not to the main branch).. Have branches for collaboration


