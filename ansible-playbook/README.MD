Init git

ansible-playbook ~/workspace/zookeeper-scripts/ansible-playbook/new-project/spring-boot-project.yml -e workspace=/Users/jichen/workspace -e gitAccount=chenyu530324 -e private=false -e projectName=showcase -vvv

Init AWS and jenkins

ansible-playbook ~/workspace/zookeeper-scripts/ansible-playbook/jenkins/create-instance-for-jenkins.yml --private-key ~/zookeeper.pem --extra-vars "id=Access key ID secret=Secret access key url=https://github.com/chenyu530324/test.git branch=master pipe_name=zookeeper" -vvv