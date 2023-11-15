
pipeline{

    agent any

    stages{
        stage('Git Checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/asingh824/java-app.git'
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
}