pipeline {
  agent {
    docker {
      image "node:8-apline"
    }
  } 
  stages {
    stage("Build") {
      steps {
       sh "npm install"
      }
    }
  }
}
