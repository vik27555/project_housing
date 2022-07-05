# project_housing

first main ml project
```
conda create -p venv python==3.7 -y
```
conda activate venv/
```
or
```
```
conda activate venv
```
pip install -r requirements.txt
```

to add files to git
```
git add
```

or
``` 
git add <file_name>
```

```
to ignore file or folder from git we can write name of file /folder in.gitignore file
```
to check the git status
```
git status
```

to check all version maintained by  git
```
git log
```
to create version/commit all changes by git
```
git commit -m "message"
```

```
to send version/changes to github
```
git push origin main
```

to check remote url
```
git remote -v
```

```
to setup ci/cd pipeline in heroku we need 3 information
1. HEROKU_EMAIL = vikashsingh5151@gmail.com
2. HEROKU_API_KEY = ddf52241-20e0-46e5-b9a4-09a59e48d383
3. HEROKU_APP_NAME = ml-regression-app-vikash1

BUILD DOCKER IMAGE
```
docker build -t <image_name>: .
```
NOTE : image name for docker must be lowercase
```

to list docker images
```

docker images
```
Run docker image
```

docker run -p 5000:5000 -e PORT=5000
``` 
To check the running container in docker
```

docker ps
``` 
tos stop docker container
```

docker stop <container_id>
``` 

```
python setup.py install

```
python setup.py install
```

install ipykernel

```
pip install ipykernel
```

data drift:
when your dataset starts gets change we will call it as data drift


## write a function to get training file path from artifact dirs