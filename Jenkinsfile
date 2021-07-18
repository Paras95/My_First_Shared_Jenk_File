//@Library('utils') _
library 'utils@paras'
pipeline{
  agent any
  stages{
    stage('lib_from_vars'){
      steps{
        script{
            paras()
            paras.beta()
            paras.class1()
        }
      }
    }
  }
}
