pipeline {
           agent any
           stages {
                    stage ("pull the code from SCM"){
                        steps {
                        sh 'sleep 30'
                        git branch: 'main', url: 'https://github.com/devsharma1401/python-projects.git'
                        }
                    }
                    stage ("build the code"){
                        steps {
                            echo "stage 2 is running"
                            sh 'sleep 30'
                        }
                    }
                    stage ("test the code"){
                        steps {
                            echo "stage 3 is running"
                            sh 'sleep 30'
                        }
                    }
                    stage ("deploy the code") {
                        steps {
                            echo "stage 4 is running"
                            sh 'sleep 30'
                        }
                    }
           }
}
