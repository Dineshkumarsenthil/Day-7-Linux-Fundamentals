# Day-7 (Linux)
---
### Tree Command Installation

#### Update Package List

```
sudo apt update	Update 
sudo apt install tree 
tree --version 
tree /
tail -f /var/log/syslog	
```
---

### Directories & Files

```
mkdir -p ~/linux_practice/permissions
cd ~/linux_practice
mkdir projects config logs
touch projects/app.py 
echo "Hello World" > projects/readme.txt
mv projects/readme.txt docs_readme.txt 
mv docs_readme.txt config/ 
rm config/docs_readme.txt
rmdir logs
```
---

### Ownership & Permissions Management

####  Ownership & Permissions

```
ls -l projects/app.py 
sudo chown root projects/app.py 
sudo chgrp sudo projects/app.py 
chmod u+rwx projects/app.py	
chmod g+rw projects/app.py 
chmod o+r projects/app.py
chmod 764 projects/app.py 
```
---
### Logging And Monitoring

#### Code
```
mkdir python
cd python
touch app.py
vim app.py
```
#### Output Code
```
python3 start app.py
```
---
