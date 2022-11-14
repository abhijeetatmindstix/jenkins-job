@Library("checkingRepo") _

pipeline {
    agent any
    stages {
        stage("Checkout Repo") {
            steps {
                script{
                    properties([
                        parameters([
                            string(
                                defaultValue: 'https://github.com/SumeetBandgar/Java.git', 
                                name: 'REPO_URL', 
                                trim: true
                            ),
                            string(
                                defaultValue: 'hello-world-spring-boot', 
                                name: 'BRANCH_NAME', 
                                trim: true
                            )
                        ])
                    ])
                    gitcheckout.checkout(params.REPO_URL, params.BRANCH_NAME)
                }
            }
        }
    }
} 
