pipeline {
    agent {
        docker {
            image 'instrumentisto/flutter'
        
        }
    }
    stages {
        stage('Test') {
            steps {
               git 'https://github.com/alidaoud7/Jenkins-Test.git '
               
                // sh 'git clone https://github.com/alidaoud7/Jenkins-Test.git new'
                 //dir ("new"){
                   //  sh "pwd"
                // }

            }
        }
    }
}
