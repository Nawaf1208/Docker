# Task: Run NGINX Container using Docker

## Summary

- Installed Docker on Windows
- Ran official NGINX container
- Exposed container on port 8080

## Command Used

```bash
docker run -d --name mynginx -p 8080:80 nginx
