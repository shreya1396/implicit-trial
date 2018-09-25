@Library("trial-library") _
    standardPipeline {
        projectName = "Project1"
        serverDomain = "Project1 Server Domain"
    }
pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        echo 'try loading library implicitly'
      }
    }
  }
}
