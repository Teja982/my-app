node {
  stage('SCM checkout'){
    git 'https://github.com/Teja982/my-app'
  }
  stage('Compile-Package'){
    sh 'mvn clean package'
   }
  stage('Email Notification'){
    mail bcc: '', body: 'Welcome', cc: '', from: '', replyTo: '', subject: 'jenkins', to: 'teja.nunugonda@gmail.com'
  }
}
