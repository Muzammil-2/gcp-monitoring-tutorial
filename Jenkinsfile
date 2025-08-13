pipeline {
    node any
    environment {
        tag =
        image =
        app=
        BUILDNUMBER = buildNumber
        SONAR_SCANNER = 
    }
    tools {
        maven 'maven3'
        node 'node4'
    }

    stages{
        stage('Checkout_Code'){
            steps{
                git clone
            }
        }
    stage('test'){
            steps{
                script{
                    trivy fs --format=report.html .
                }
            }
        }
    
    }
}