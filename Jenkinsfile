//@library("checkingRepo") _

pipeline {
    agent any
    stages {
        stage('gitCheckoutRepo') {
            steps {
                gitcheckout.call()
                {
                    branch: "main"
                    //credentialsID: ""
                    url: "https://github.com/abhijeetatmindstix/sharedlibrary.git"
                }
            }
        }
    }
}
