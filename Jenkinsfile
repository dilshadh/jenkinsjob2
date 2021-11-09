pipeline {
    agent any 
    parameters {
        booleanParam(name: 'value1',defaultValue: false, description: 'value1')
        booleanParam(name: 'value2',defaultValue: false, description: 'value2')
    }
    stages {
        stage('parameters_check') {
            steps {
                script {

                    echo "Hit the second jenkins job"
                }
            }
        }
    }
}