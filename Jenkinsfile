pipeline{
  stages{
     stage('Build Maven artifact') {
        steps{
          sh 'mvn clean install -B -U -Dmaven.local.repo=/Users/Shared/Jenkins/Home/insideWorkspace/.repository'
          }
      }
  }
}
