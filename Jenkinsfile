pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello word!'
        chef_cookbook_lint(installation: 'ChefDK Local')
      }
    }
  }
}