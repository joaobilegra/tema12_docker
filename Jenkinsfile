pipeline{
    agent any
    stages{
        stage('run job1'){
            steps{
                build job: '/deploy/Jenkinsfile', parameters: [string(name: 'deploy', value: '')]
                
            }
        }
    stage('Run job2'){
        steps{
            build job: '/bake/Jenkinsfile', parameters: [string(name: 'bake', value: '')]
        }
     }    
   }
    
}