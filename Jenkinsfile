pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'Building...'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'printing req. data..' 
               sh 'python solution.py'
            }
        }
   
}
    }