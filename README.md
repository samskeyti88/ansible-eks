# ansible-aws

## Requirements
* Ansible
* boto
* boto3
* botocore
* Python 3
* AWS CLI
* kubectl

## Build EKS
To build EKS, run command below.

```
$ ansible-playbook playbooks/build_eks.yaml
```

## Destroy EKS
To destroy EKS, run command below.

```
$ ansible-playbook playbooks/destroy_eks.yaml
```