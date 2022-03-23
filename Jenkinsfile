pipeline{
    agent any
    stages{
        stage('run job1'){
            steps{
                build job: 'Jenkinsfile1', parameters: [string(name: 'Jenkinsfile1', value: '')]
                
            }
        }
    stage('Run job2'){
        steps{
            build job: 'bake', parameters: [string(name: 'bake', value: '')]
        }
     }    
   }
    
}