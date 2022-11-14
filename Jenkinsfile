@library("checkingRepo") _

pipeline {
    agent any
    stages {
        stage('gitCheckoutRepo') {
            steps {
                gitcheckout.checkout
                {
                    branch: "hello-world-spring-boot" 
                    //credentialsID: ""
                    url: "https://github.com/SumeetBandgar/Java.git"
                }
            }
        }
    }
}
