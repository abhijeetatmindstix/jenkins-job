//@Library("checkingRepo") _

pipeline {
    agent any
    stages {
        stage("Checkout Repo") {
            steps {
                script{
                    
                    gitcheckout.checkout("https://github.com/SumeetBandgar/Java.git", "hello-world-spring-boot")
                }
            }
        }
    }
} 
