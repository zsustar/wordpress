pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/zsustar/wordpress/tree/master/twentysixteen', branch: 'master', credentialsId: 'star_key', poll: true)
      }
    }
  }
}