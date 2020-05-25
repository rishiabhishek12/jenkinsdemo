pipeline {
    agent any
        stages{
            stage("Git-checkout"){
                steps{
               git branch: 'azure3', credentialsId: 'Github-cred', url: 'https://github.com/vnc-digital/BeaconUserService.git'
            }
            }
        
        }
}
