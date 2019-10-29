### Ansible scripts to deploy OCS4 on OCP4.2

Connect first to your OpenShift Cluster
```bash
oc login --token=<replace with your token> --server=<replace with your server's API address>
```

Launch with:
```bash
ansible-playbook ocs-deploy.yaml
```

