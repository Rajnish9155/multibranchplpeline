pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch.."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch. editing in this. now updated."'
            }
        }

        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch, now updated"'
            }
        }  
    }
}
