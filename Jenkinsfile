pipeline {
       agent any
       stages {
        stage('git commit') {
            steps {
               git  'https://github.com/Tushar7899/studentapp-ui.git'           
            }
        }
        stage('build') {
            steps {
                sh '''
                mkdir github_directory1
                echo "successfully copied file"
                '''
            }
        }
        stage('test') {
            steps {
                echo "successfully test"
            }
        }
        stage('deploy') {
            steps {
              echo "successfully deployed"
            }
        }
        stage('run script') {
            steps {
            script {
                def name = "cloudblitz"
                def gender = "male"
                if(gender == "male") {
                    echo "Mr. $name"    
                } else {
                    echo "Mrs. $name"
                }
            }
        }
        }
    }
}
