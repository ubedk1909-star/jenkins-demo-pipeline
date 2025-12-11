cat > Jenkinsfile << 'EOF'
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application (demo only)..."
            }
        }
    }
}
EOF

