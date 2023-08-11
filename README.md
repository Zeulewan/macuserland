```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
python3 -m pip install ansible
ansible-pull --ask-become-pass -U https://github.com/Zeulewan/macuserland.git playbook.yaml
```
