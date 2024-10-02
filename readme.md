create project file and cd
source /venv/bin/activate
cd venv
pip3 install boto3 botocore
ansible pip3 install boto3 botocore

ansible-playbook -i /Users/jade/devops/teachings/ansible-test/inventory/aws_ec2.yml -u ubuntu /Users/jade/devops/teachings/ansible-test/Basic_Concepts_of_Ansible_PlayBooks/ansible_datacollection.yml

OR

ansible-playbook -i inventory/aws_ec2.yml -u ubuntu site.yml
