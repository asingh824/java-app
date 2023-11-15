@Library ('my-shared-library-2') _
pipeline{

    agent any

    stages{
        stage('Git Checkout'){
            steps{
                    gitCheckout(
                        branch: "main",
                        url: "https://github.com/asingh824/java-app.git"
                    )
                    }
            }
    }
}