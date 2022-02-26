pipeline {
    
agent { node { label 'master' } } 

stages {
   stage('Read demo file') {
            steps {
                sh 'cat demo.txt'
            }
        }
    stage('Read Readme.md file') {
            steps {
                sh 'README.md'
            }
        }

}

}
