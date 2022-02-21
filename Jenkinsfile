pipeline {
    agent any

    // Install the Jenkins tools you need for your project / environment
    tools {
        snyk 'Snyk' // Refers to a global tool configuration for Snyk called 'Snyk'
    }

    stages {
        
        stage('Git Clone') {
            steps {
                git url: 'https://github.com/gregmichaels/SimpleReactNativeTodoList'
            }
        }
        
        stage('Run Snyk Scan') {
            steps {
                snykSecurity monitorProjectOnBuild: true, snykInstallation: 'Snyk', snykTokenId: 'snyk_api_token'
            }
        }
    }
}
