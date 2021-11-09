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
                    if (params.value1) {
                        echo "Hit the second jenkins job from value1"
                    }
                    else {
                        echo "Hit the second jenkins job from value2"
                    }
                }
            }
        }
    }
}