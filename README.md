# faithfulword-deploy


## clone repo
```
git clone faithfulword-deploy.git
```

## install python
```
asdf install python 3.7.4
asdf local python 3.7.4
```

## make pyvenv
```
cd ..
python -m venv pyvenv374
source pyvenv374/bin/activate
cd faithfulword-deploy
pip install --upgrade pip
```

## install ansible
```
pip install ansible
```

## install ansible deps
```
cd roles
ansible-galaxy init mmannerm.bash_it
cd ..
```

## copy pem to local dir
```
cp /path/to/fw.pem .
chmod 600 fw.pem
```

## append pub key to your public ssh keys
```
ssh-keygen -f fw.pem -y >> /path/to/.ssh/id_rsa.pub
```

## run playbook
```
ansible-playbook site.yml -i hosts-edge.yml -vvvv
```
