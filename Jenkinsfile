//@Library("checkingRepo") _

pipeline {
    agent any
    stages {
        stage("Checkout Repo") {
            steps {
                script{
                    
                    gitcheckout.checkout(params.REPO_URL, params.BRANCH_NAME)
                }
            }
        }
    }
} 
