### Git LFS
###### Way to upload heavy files (upto 2GB on GitHub)

#### STEP#1: [Download](https://git-lfs.github.com/) and Install GitLFS.
#### STEP#2: Follow the below Steps: </br>
```
$  git clone https://github.com/rahulvaish/LFS/
```
```
$  cd LFS
```
```
$  git lfs install
```
```
$  git lfs track "*.zip"
```
```
$  git add .gitattributes
```
```
$ git add -f DataSets.zip
```
```
$ git commit -m "Adding 113 MB Data"
```
```
$ git push
```

![image](https://user-images.githubusercontent.com/689226/73557905-1c502480-4478-11ea-8ded-b51b559ad64c.png)
