pipeline{
    agent any
    stages{
        stage('run job1'){
            steps{
                build job: 'deploy', parameters: [string(name: 'deploy', value: 'Jenkinsfile')]
                
            }
        }
    stage('Run job2'){
        steps{
            build job: 'bake', parameters: [string(name: 'bake', value: 'Jenkinsfile')]
        }
     }    
   }
    
}