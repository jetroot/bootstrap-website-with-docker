# Containernized Bootstrap Website with Docker
Running a simple bootstrap website with docker

### Build the image
```bash
docker build -t website:1.0.0 .
```

### Run the image
```bash
docker run --name website1 -p 8080:8080 -d website:1.0.0
```

### Check running
```bash
visit url: http://127.0.0.1:8080/
```
