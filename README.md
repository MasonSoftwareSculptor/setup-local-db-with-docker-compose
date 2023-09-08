# setup-local-db-with-docker-compose

Setup:

1. MySQL Server
2. Redis Server
3. PostgreSQL Server
4. RabbitMQ Server
5. SonarQube
6. Jenkins

START COMMAND:
docker-compose up -d

SonarQube Info:

1. username: admin
2. password: admin

Jenkins Info:

1. password: You must exec Jenkins container or use Docker Desktop to access Jenkins conainer, then run this command: "cat /var/jenkins_home/secrets/initialAdminPassword" to get admin password
