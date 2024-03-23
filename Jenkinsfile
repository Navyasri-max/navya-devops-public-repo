	pipeline {
    agent {
        label 'tests'
    }

    stages {
       // stage('Checkout') {
        //    steps {
        //        checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Navyasri-max/navya-devops-public-repo.git']])
        //    }
       // }
        stage('Printit') {
            steps {
                echo 'this is an example pipeline job to illustrate pipeline from SCM'
            }
        }
    }
}
