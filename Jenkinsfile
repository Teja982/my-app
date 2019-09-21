node {
  stage('SCM checkout'){
    git 'https://github.com/Teja982/myapp'
  }
  stage('Compile-Package'){
    sh 'mvn clean package'
   }
 }

