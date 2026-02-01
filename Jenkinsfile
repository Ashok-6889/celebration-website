pipeline {
  agent any

  stages {
    stage('Clone Repo') {
      steps {
        git 'https://github.com/your-username/celebration-website.git'
      }
    }

    stage('Deploy') {
      steps {
        sh '''
        sudo cp -r * /var/www/html/
        '''
      }
    }
  }
}
