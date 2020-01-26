node {
   def mvnHome
   stage('Preparation') { // for display purposes
      git 'https://github.com/bhathiyabasnayake/fleetman-webapp'
    }
   stage('Build') {
            sh "mvn package"
   }
   stage('Results') {
      archiveArtifacts 'target/*.jar'
   }
}
