pipeline {
  agent any
  parameters {
  choice choices: ['PROD', 'DEV', 'QA'], description: 'My_env', name: 'ENV'
}
environment {
  Java_home = "/usr/bin/java"
}


  stages {
    stage ('Initialize') {
      steps ('run the script') { 
        script {
          echo "welcome to jenkins new pipelineSC"
          var1="mohan"
          echo "hi welcome to ${var1}"
          echo "select the parameters is ${params.ENV}"
          echo "my environament is ${env.Java_home}"
          echo "my git commit ${GIT_COMMIT}"
          echo "my workspace ${WORKSPACE}"
          echo \"The environment parameter in shell is: \${params.ENV}\"
        }
      }
    }
  }
}
