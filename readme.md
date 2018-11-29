# Hello:

Spring boot, Gradle and Docker.

# Build and Run:

## Step 1: Build jar file and Docker image:

```
gradle build && docker build -t hello .
```

## Step 2: run container:

```
docker run -d --name my-hello -p 8080:8080 hello

```
