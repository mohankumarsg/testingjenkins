pipeline {
  agent any
  parameters {
  choice choices: ['PROD', 'DEV', 'QA'], description: 'My_env', name: 'ENV'
}

  stages {
    stage ('Initialize') {
      steps ('run the script') { 
        script {
          echo "welcome to jenkins new pipelineSC"
          var1="mohan"
          echo "hi welcome to ${var1}"
          echo "select the environament is ${params.ENV}"
        }
      }
    }
  }
}
