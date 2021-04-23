### Git LFS
###### The below guide aims to list of Steps used to upload heavy files (upto 2GB) on GitHub, using GitLFS.

#### STEP#1: [Download](https://git-lfs.github.com/) and install GitLFS.
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
###### Copy-Paste any .zip folder (DataSets.zip) into the current Repository Folder: </br>
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

How to clone Git lfs

```bash
$ git lfs install
```

```bash
$ git lfs clone git@github.com:shootercheng/GitLFS.git
```

