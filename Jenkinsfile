pipeline {   
    agent any

    stages {   
        stage('Master1') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1branch1 code') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
