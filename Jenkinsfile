pipeline {
    agent any 
    stages {
        stage ("pull"){
            steps {
                git branch: 'main', url: 'https://github.com/prathamnandgirwar/student-app-k8s.git'
            }
        }
         stage ("build"){
            steps {
                echo "code build success"
            }
        }
         stage ("test"){
            steps {
                echo "code test success"
            }
        }
         stage ("deploy"){
            steps {
                echo "code deploy success"
            }
        }
    }
}
