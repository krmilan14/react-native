pipeline {
    agent any

    environment {
        JAVA_HOME = "/usr/lib/jvm/java-17-openjdk-amd64"
        ANDROID_HOME = "/home/milan-kumar/Android/Sdk"
        PATH = "$JAVA_HOME/bin:$ANDROID_HOME/emulator:$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH"
    }

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm  // This checks out the code from your repository
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        
    }

    
}
