# cheatsheet
Cheatsheet for frequently used commands
---
## Linux
---
## NVIDIA Jetson Nano
---
## Python
### Manage Python Versions
Label one of the version as "1"
```
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1  
```
Label other version as "2"
```
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.8 2
```
Choose which version to set as default
```
sudo update-alternatives --config python3
```

### Virtual Environment
Install Library
```
pip3 install virtualenv 
```
Create Environment
```
python3 -m venv <virtual-environment-name>
```
Activate Environment
```
source <virtual-environment-name>/bin/activate
```
Deactivate Environment
```
deactivate
```
Delete Environment
```
sudo rm -rf <virtual-environment-name>
```
---
## Docker
---
## GitHub
---
Cloning latest release
```
git clone <reporsity-link>
```
Cloning specific release/branch
```
git -b <relase-tag> clone <reporsity-link>
```
Cloning specific commit
```
git clone <reporsity-link>
```
```
cd <reporsity>
```
```
git reset --hard <commit-id>
```
Commit Log
```
git log
```
