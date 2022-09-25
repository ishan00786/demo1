pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
            sh 'touch abcd.txt'
            sh 'touch xyz.txt'    
            }
        }
        stage('Test'){
            steps{
                sh'''
                if [ -f abcd.txt ]
                then
                echo "file created"
                fi
                '''
            }
        }
    }

}

