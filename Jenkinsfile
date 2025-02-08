pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                checkout([
                    $class: 'GitSCM',
                    branches: [[name: '*/master']], // Use master branch
                    extensions: [[$class: 'RelativeTargetDirectory', relativeTargetDir: 'your-folder']],
                    userRemoteConfigs: [[url: 'https://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@github.com/falguni092001/NutanWani.git']]
                ])
            }
        }
        // Add more stages as needed
    }
}
