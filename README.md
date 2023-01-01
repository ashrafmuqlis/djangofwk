# djangofwk
Notes on Django Framework stacked on ubuntuless. How to's, etc.


### Default django project folder newoproject/

### Obtain "vagrant-vm-ip"
$ip a | grep -w inet | grep -v 127.0.0.1 | awk '{print $2}' | awk -F/ '{print $1}'

### Start django server with the "vagrant-vm-ip"
$python3 newoproject/manage.py runserver "vagrant-vm-ip":8000
