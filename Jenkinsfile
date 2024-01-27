pipeline {
  agent any
  stages {
    stage('builld') {
      steps {
        echo 'loja'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'adsa'
          }
        }

        stage('t2') {
          steps {
            echo 'asdads'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'hahahah'
        waitUntil(initialRecurrencePeriod: 1)
      }
    }

  }
}