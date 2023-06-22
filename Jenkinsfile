pipeline {
    agent {
        docker {
            image 'instrumentisto/flutter'
                args '-u root'
        }
    }
    stages {
        stage('Test') {
            steps {
               sh 'git clone https://github.com/alidaoud7/Jenkins-Test.gi'
               
                // sh 'git clone https://github.com/alidaoud7/Jenkins-Test.git new'
                 //dir ("new"){
                   //  sh "pwd"
                // }

            }
        }
    }
}
