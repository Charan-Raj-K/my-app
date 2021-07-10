node{
  stage('SCM Checkout')
  {
  git 'https://github.com/Prathi-07/my-app.git',branch: 'master'
  }
  stage('compile-package'){
  //get maven home path
    def mvnhome = tool name: 'prathi_Maven', type: 'maven'
     sh "${mvnhome}/bin/mvn package"
  }
  
}
