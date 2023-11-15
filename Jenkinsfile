//new jenkinsfile
@Library('my-shared-library-1') _
pipeline{

    agent any

    stages{
        stage('Git Checkout'){

            steps{
            script(
                branch: "main", url: 'https://github.com/asingh824/java-app.git'
                    )   
            }
        }

    /*
    stage('Unit Test maven'){
            steps{
                    script{
                        mvnTest()
                    }   
                }
            }
            */
    }
}


//git branch: 'main', url: 'https://github.com/asingh824/java-app.git'