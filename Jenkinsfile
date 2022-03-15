pipeline{
  agent any
  stages{
    stages('checkout'){
      steps{
        git credentialsId: 'github-credenitals', url: 'https://github.com/sravanthi883/ide-new.git'
      }
    }
  }
}
