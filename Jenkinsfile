pipeline{
    agent any
    stages{
        stage('run job1'){
            steps{
                build job: dir('deploy/Jenkinsfile'), parameters: [string(name: 'deploy', value: '')]
                
            }
        }
    stage('Run job2'){
        steps{
            build job: dir('bake/Jenkinsfile'), parameters: [string(name: 'bake', value: '')]
        }
     }    
   }
    
}