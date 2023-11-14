# CDC-Branch-Testing

## Here's a step-by-step guide for Git commands to clone a repository, create three branches (master, main, feature), and add a tag

### Steps:
-  Clone a Repository:<br/>
```
git clone <repository_url>
```
-  Navigate to the Cloned Repository:
```
cd <repository_directory>
```
-  Create Branches:
```
git branch master
git branch main
git branch feature
```
- Switch to the Branches :
```
git checkout master
git checkout main
git checkout feature

```
-  Add and Commit Changes (Optional):
```
git add .
git commit -m "Commit message"

```
-  Create a Tag:
```
git tag -a v1.0 -m "Version 1.0"
```
- Note: If you want to push the branches and tags to the remote repository, you can use the following commands:
```
git push origin master
git push origin main
git push origin feature
git push --tags
```
