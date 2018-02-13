##### Create a virtual environment:
```
virtualenv venv -p python3.6
source venv/bin/activate
```

##### Install the required packages:
```
pip install -r requirements.txt
```

##### Enter your credentials in ```hosts.ini``` file

##### Run ansible playbook
```
cd ansible/
ansible-playbook -i hosts.ini playbook.yaml
```
