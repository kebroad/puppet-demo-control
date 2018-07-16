node {
  //agent any

  //stages {
    //stage('Unit Tests'){
      //steps {
        checkout scm
        echo 'test1'
        puppet.credentials 'puppet-jenkins2'
        echo 'test21'
        puppet.job 'production'
        echo 'trying code deploy...'
        puppet.codeDeploy 'production'
        //echo 'code deploy works! trying puppet job!'
        puppetJob credentialsId: 'pe-access-token'
      //}
    //}
  //}
}
