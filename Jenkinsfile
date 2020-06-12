pipeline {
    agent any
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages {
        stage('Example') {
            steps {
                echo "${params.Greeting} World!"
            }
        }
        
        stage('Example2') {
            steps {
                echo "${params.Greeting} World!!!"
            }
        }
    }
}
