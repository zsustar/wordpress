pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/zsustar/wordpress/tree/master/twentysixteen', branch: 'master', credentialsId: 'star_key')
      }
    }
  }
}