node {
  //agent any

  //stages {
    //stage('Unit Tests'){
      //steps {
        checkout scm
        echo 'this works!!'
        puppet.credentials 'pe-access-token'
        echo 'trying code deploy'
        puppet.codeDeploy 'production'
        //echo 'code deploy works! trying puppet job!'
        puppetJob credentialsId: 'pe-access-token'
      //}
    //}
  //}
}
