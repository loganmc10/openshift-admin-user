# Usage
The username is ```admin```. admin_password defaults to ```admin```.
```
export KUBECONFIG=~/path/to/kubeconfig
ansible-playbook admin-playbook.yaml -e "admin_password=Pa$$word"
```

You can pass ```-e "force=true"``` in order to force a password update

You can pass ```-e "remove_kubeadmin=false"``` in order to keep the kubeadmin user
