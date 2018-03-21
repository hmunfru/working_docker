FROM node:6-slim
# Working directory for application
WORKDIR /usr/src/app
# Binds to port 7777
COPY wait_for_postgres.sh .
EXPOSE 7777
# Creates a mount point
VOLUME [ "/usr/src/app" ]
