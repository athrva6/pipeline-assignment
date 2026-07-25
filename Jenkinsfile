pipeline {
    agent any

    parameters {
        choice(
            name: 'ENVIRONMENT',
            choices: ['staging', 'production'],
            description: 'Target Environment'
        )
    }

    stages {
        stage('Build') {
            steps {
                echo "Building for ${params.ENVIRONMENT}"
            }
        }
    }
}
