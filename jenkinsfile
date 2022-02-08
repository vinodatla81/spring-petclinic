pipeline{
    agent any
    stages {
        /* "Build" and "Test" stages omitted */
        stage('Deploy-Dev'){
            steps{
                echo 'hello'
                
            }
        }
        stage('Deploy-QA'){
            steps {
                echo'QA'
                input "Does the String Environment look ok?"
            }
        }
        stage ('Deploy-Production'){
            steps{
                echo 'Production'
            }
        }
    }
}
