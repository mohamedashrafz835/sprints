# Docker & Compose Recap Quiz

## Multiple Choice Questions

1. What does the `-d` flag do when running a Docker container?

   - A) Deletes the container after execution
   - B) Runs the container in detached mode
   - C) Downloads the image only
   - D) Disables network
   - **Answer:** B

2. What is the purpose of `docker-compose.yml`?

   - A) To build custom Docker images
   - B) To manage multi-container Docker applications
   - C) To remove all containers
   - D) To update Docker
   - **Answer:** B

3. Which network mode does Compose use by default?

   - A) Host
   - B) None
   - C) Bridge
   - D) Overlay
   - **Answer:** C

4. What does a health check in Docker do?

   - A) Monitors disk usage
   - B) Verifies container functionality over time
   - C) Performs virus scanning
   - D) Clears cache
   - **Answer:** B

5. What is the function of the `COPY` command in a Dockerfile?

   - A) Installs packages
   - B) Runs shell commands
   - C) Copies files from host to container image
   - D) Creates directories
   - **Answer:** C

6. What is layer caching in Docker builds?

   - A) Caching data from the internet
   - B) Speeding up container run time
   - C) Reusing unchanged build steps to speed up builds
   - D) Compressing image files
   - **Answer:** C

7. In a multi-stage build, what is the main benefit?

   - A) Smaller final images by copying only necessary artifacts
   - B) Simpler logs
   - C) Avoiding port conflicts
   - D) Combining all containers into one
   - **Answer:** A

8. How can you map port 8080 of a container to port 3000 on your host?

   - A) `-p 3000:8080`
   - B) `-p 8080:3000`
   - C) `-m 8080:3000`
   - D) `--expose 3000:8080`
   - **Answer:** A

9. What does the `volumes:` section do in a Compose file?

   - A) Manages logs
   - B) Allocates memory
   - C) Persists data between container restarts
   - D) Sets port mappings
   - **Answer:** C

10. What is the correct way to name a container using Docker CLI?
    - A) `--container-name myapp`
    - B) `--name=myapp`
    - C) `--name myapp`
    - D) Both B and C
    - **Answer:** D
