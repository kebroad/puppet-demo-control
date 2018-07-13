node {
  //agent any

  //stages {
    //stage('Unit Tests'){
      //steps {
        checkout scm
        puppet.credentials 'pe-access-token'
        puppet.job 'production'
        echo 'trying code deploy...'
        puppet.codeDeploy 'production'
        //echo 'code deploy works! trying puppet job!'
        puppetJob credentialsId: 'pe-access-token'
      //}
    //}
  //}
}
