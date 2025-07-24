# Docker Lifecycle Report

This report demonstrates the lifecycle of a Docker container: from creation to removal, and how disk space changes before and after using `docker image prune`.

---

## Step 1: Pull a Docker Image

```bash
docker pull alpine:latest
```

## Step 2: Create the Container

```bash
docker create --name temp-alpine alpine:latest
```

## Step 3: Start the Container

```bash
docker start temp-alpine
```

## Step 4: Stop the Container

```bash
docker stop temp-alpine
```

## Step 5: Remove the Container

```bash
docker rm temp-alpine
```

---

## Step 6: Check Disk Usage Before Pruning

```bash
docker system df
```

_Output sample before pruning:_

```
TYPE            TOTAL     ACTIVE    SIZE      RECLAIMABLE
Images          3         1         200MB     150MB (75%)
Containers      1         0         1MB       1MB (100%)
Local Volumes   1         1         30MB      0B (0%)
Build Cache     0         0         0B        0B
```

---

## Step 7: Prune Unused Docker Images

```bash
docker image prune -f
```

## Step 8: Check Disk Usage After Pruning

```bash
docker system df
```

_Output sample after pruning:_

```
TYPE            TOTAL     ACTIVE    SIZE      RECLAIMABLE
Images          1         1         50MB      0B (0%)
Containers      0         0         0B        0B
Local Volumes   1         1         30MB      0B (0%)
Build Cache     0         0         0B        0B
```

---

## Conclusion

This report showed how to create, start, stop, and remove a Docker container. It also demonstrated how unused Docker images take up space, and how `docker image prune` can help reclaim that space.
