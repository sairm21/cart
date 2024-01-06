pipeline {

    agent {
        node { label 'Workstation' }
    }


    stages {
        stage('Build') {
            steps {
                echo "code build"
             }
        }

        stage('unit tests') {
            steps {
                echo "unit tests"
             }
        }

        stage('code analasys') {
            steps {
                echo "code analasys"
             }
        }

        stage('security scans') {
            steps {
                echo "security scans"
             }
        }

        stage('publish artifacts') {
            steps {
                echo "publish artifacts"
             }
        }
    }
}