pipeline {
    // Use any available agent (node) to run the pipeline
    agent any

    // Define the stages of the pipeline
    stages {
        stage('Build') {
            steps {
                echo "Building the project..."
                // For a real project, replace the next line with your build command.
                // For example: sh 'mvn clean package' for a Maven project.
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
                // Insert your test commands here.
                // For example: sh 'mvn test' or your unit test runner.
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project..."
                // Insert deployment commands or scripts here.
            }
        }
    }
}
