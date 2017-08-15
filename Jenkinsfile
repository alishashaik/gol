pipeline {
  agent {
   label "Windows_Slave"
  }
   tools {
   
    jdk "JDK 1.8.0_05"
    maven "Maven 3.5.0"
  }
  stages {
    stage ('build') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}
