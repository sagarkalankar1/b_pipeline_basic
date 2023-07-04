pipeline{
    agent any
    stages {
        stage('Compile') {
            steps {
                echo "Compiled Successfully!!";
            }
        }
        
        stage('JUnit') {
            steps {
                echo "JUnit Passed Successfully";
            }
        }
        
        stage('Quality-Gate') {
            steps {
                echo "SonarQube Quality Gate passed successfully";
               
            }
        }
        
        stage('Deploy') {
            steps {
                echo "Pass";
            }
        }
    }
}    
