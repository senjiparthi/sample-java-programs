pipeline {
    agent any

    stages {
        stage ('Source Code Checkout'){
            steps {
                checkout scm
            }
        }
        stage ( 'Build' ) {
            steps {
                sh 'mvn clean install'
            }
    }

}
}
