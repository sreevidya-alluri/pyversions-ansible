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
     sh 'ansible-playbook -i inventory.ini playbook.yml'
}
}
}
}
