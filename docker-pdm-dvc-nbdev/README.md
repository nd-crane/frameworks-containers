
```
# Copy project files into the image
COPY . /app
```

```
docker build -t my-pipeline .
```

```
docker run --rm -it -v $(pwd):/app my-pipeline pdm run my_pipeline
```

