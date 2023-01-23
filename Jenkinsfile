pipeline {
    agent any
      stages{
        stage('parallel-1'){
            parallel {
                stage('sub-job1'){
                    steps{
                        sh 'echo "I am devops"'
                    }
                }
                stage('sub-job2'){
                    steps{
                        sh 'echo "on my way"'
                    }
                }
            }
        }
        stage('parallel-2'){
            steps{
                sh 'echo "On the carrer like wild fire"'
            }
        }
      }
}