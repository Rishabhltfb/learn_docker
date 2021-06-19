LEARNING DOCKER

1. docker run {img_id/img_name}

2. docker ps

3. docker build .

4. docker build -t {username/project_name} .

5. docker-compose up

6. docker run -p external_port:container_port {img_id/img_name}

7. docker exec -it {img id/name} {extra command}

8. docker run {img id/name} {override initial command}

9. docker run -d {img id/name}

10. docker stop {img id/name}

11. docker-compose up --build

12. docker-compose up -d

13. docker-compose down

14. docker-compose ps

15. docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app {img id/name}

16. docker image rm -f [IMAGE...]

17. docker images