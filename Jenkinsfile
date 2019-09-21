node {
  stage('SCM checkout'){
    git 'https://github.com/Teja982/my-app'
  }
  stage('Compile-Package'){
    sh 'mvn clean package'
   }
}
