pipeline{

agent { node { label 'master' } }
options { skipDefaultCheckout() }

parameters {
    string(name: 'suiteFile', defaultValue: '', description: 'Suite File')
}
stages{

    stage('Initialize'){

        steps{

          echo "${params.suiteFile}"

        }
    }
 }
 }
