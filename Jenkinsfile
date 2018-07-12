node {
  //agent any

  //stages {
    //stage('Unit Tests'){
      //steps {
        echo 'this works!!'
        puppet.credentials '04aaec0d-d5f3-4410-916d-98bf9f74a4d8'
        echo 'trying code deploy'
        puppet.codeDeploy 'production'
        //echo 'code deploy works! trying puppet job!'
        puppetJob credentialsId: '04aaec0d-d5f3-4410-916d-98bf9f74a4d8'
      //}
    //}
  //}
}
