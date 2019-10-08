pipeline{
  stages{
    stage('Checkout') {
      gitClean()
      checkout scm
     }
      stage('Build Maven artifact') {
        steps{
          sh '/Users/Shared/Jenkins/Home/insideWorkspace'
          }
      }
  }
}
