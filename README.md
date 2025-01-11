# SRE Course

`postgresql_cluster` -- ansible playbook

`sre-course` -- helm chart

## Deploy

Ansible playbook:
```bash
cd postgresql_cluster/automation
ansible-playbook deploy_pgcluster.yml
```

Helm chart:
```bash
helm upgrade -i sre-course sre-course/ --namespace=sre-cource-student-4 --kubeconfig=student_4.yaml
```
