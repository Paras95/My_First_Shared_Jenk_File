@Library('utils') _

pipeline{
  agent any
  stages{
    stage('lib_from_vars'){
      steps{
        script{
            paras()
            paras.beta()
            paras.class1(this, this)
        }
      }
    }
  }
}
