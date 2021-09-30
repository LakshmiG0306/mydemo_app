pipeline {
  agent any
  parameters {
  choice choices: ['main', 'dev'], description: '''choose branch for deployment''', name: 'branch'
}
  stages{
    stage ('demo') {
      steps {
        echo "this is demo for dev branch"
      }
    }
  }
}
