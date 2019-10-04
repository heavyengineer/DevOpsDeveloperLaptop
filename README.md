Install the latest version of ansible on your laptop. 
```
sudo apt install ansible
```

Check you have the latest version here: https://github.com/ansible/ansible/releases
```
ansible --version
```

## How to run
```
sudo ansible-pull -U https://github.com/heavyengineer/DevOpsDeveloperLaptop.git
```

Get the dependencies from the requirements file
This will download required roles from ansible galaxy
```
ansible-galaxy -vvv install -r requirements.yml
```
Sometimes the remote api is flakey. If you see timeout errors, try again. 