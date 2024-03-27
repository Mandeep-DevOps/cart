pipeline {
  agent {
    node {
      label 'workstation'
    }
  }
  stages {

    stage('Unit Tests') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

    stage('Integration Tests') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
        sh 'env'
      }
    }

    stage('Code Quality') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

    stage('SAST') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

    stage('SCA') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

    stage('SECRET Detection') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

    stage('Artifact Produce') {
      when { not { branch 'main' } }
      steps {
        echo 'OK'
      }
    }

  }
}

// 1