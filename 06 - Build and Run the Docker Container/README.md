
## Step 06 - Build and Run the Docker Container

- Build the Docker image

```bash
docker build -t hello-world-jupyter .
```
- Run the container

```bash
docker run -p 8888:8888 hello-world-jupyter
```

This will launch Jupyter Notebook inside the Docker container, which will be accessible on your local machine at http://localhost:8888.