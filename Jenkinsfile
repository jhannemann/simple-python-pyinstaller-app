pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
               
            }
            steps {
                sh 'python -m py_compile sources/add2vals.py sources/calc.py' 
            }
        }
    }
}
