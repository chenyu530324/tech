参数：
id: aws secret id
secret: aws private secret
url: git repo url
branch: jenkins branch
pipe_name: pipeline name

参考用法：
ansible-playbook create-instance-for-jenkins.yml --private-key ~/zookeeper.pem --extra-vars "id=XXXXX secret=XXXXXXXXXX url=https://github.com/chenyu530324/test.git branch=master pipe_name=test"