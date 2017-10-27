pipeline {
  agent any
  stages {
    stage('Lint') {
      steps {
        echo 'hello world!'
      }
    }
    stage('Functional') {
      steps {
        chef_cookbook_functional(installation: 'ChefDK Local')
      }
    }
  }
}
