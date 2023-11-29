with Ansible:
in directory hello
ansible -m ping cute (Для проверки, где "cute", имя хоста)
ansible-playbook deploy.yaml

with docker
docker build -t diman035/hello:1.0 .
