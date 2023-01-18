peline {
    agent any

    stages{
        stage("create zip file"){
            steps{
                script(
        zip middlewareScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md  
                )
             
            }
        }
        
    }
}