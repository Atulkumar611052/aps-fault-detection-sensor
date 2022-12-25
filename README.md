# neurolab-mongo-python

![image](https://user-images.githubusercontent.com/57321948/196933065-4b16c235-f3b9-4391-9cfe-4affcec87c35.png)

### Step 1 - Install the requirements

```bash
pip install -r requirements.txt
```

### Step 2 - Run main.py file

```bash
python main.py
```




git version
``` 
git --version
```

To download dataset
```
wget https://raw.githubusercontent.com/avnyadav/sensor-fault-detection/main/aps_failure_training_set1.csv 
```
This is changes made in neurolab

Git commands
If you are starting your project and want to use git in youyr project
```
git init
```
This is going to initialize git in youyr source code
OR
You can clone existing git repo
```
git clone <github_url>
```
Note: clone/download github repo in your system

Add your changes made in file to git stagging are

git add file_name
Note: You can given file_name to add specific file or use "." to add everything to staging are

Create commits

git commit -m "message"
git push origin main
Note: origin--> contains url to your github repo main--> is your branch name

To push your changes forcefully.

git push origin main -f
To pull changes from github repo

git pull origin main
Note: origin--> contains url to your github repo main--> is your branch name

.env file has

MONGO_DB_URL="mongodb://localhost:27017"
AWS_ACCESS_KEY_ID="aagswdiquyawvdiu"
AWS_SECRET_ACCESS_KEY="sadoiuabnswodihabosdbn"
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo usermod -aG docker ubuntu
newgrp docker

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
AWS_ECR_LOGIN_URI=
ECR_REPOSITORY_NAME=
BUCKET_NAME=
MONGO_DB_URL=