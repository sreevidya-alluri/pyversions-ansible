pipeline{
agent any

stages{
stage('checkout the source code repository'){
steps{
 checkout scm
}
}

stage('run the playbook'){
   steps{
     sh 'ansible-playbook -i /home/sree-vidya/ansible-task/inventory.ini /home/sree-vidya/ansible-task/playbook.yml'
}
}
}
}
