pipeline {
agent any

```
stages {

    stage('Checkout') {
        steps {
            checkout scm
        }
    }

    stage('Show Files') {
        steps {
            bat 'dir'
        }
    }

    stage('Node Check') {
        steps {
            bat 'node -v'
            bat 'npm -v'
        }
    }

    stage('Docker Check') {
        steps {
            bat 'docker --version'
        }
    }

}
```

}

