### Git clone

```
git clone https://github.com/merajaprasad/aws-devops-pipeline.git
```
```
cd aws-devops-pipeline
```
### Step 2 - Build and run docker container

```
docker build -t webapp .
```

```
docker run -dp 3000:3000 webapp
```
