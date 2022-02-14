pipeline {
  agent any
  stages {
    stage('Execute Velocity Script') {
      steps {
        echo 'Pipeline Starting'
        sh'''
            python3 /var/jenkins/execute/velocity.py 10.75.236.3 ${user} ${password} TS_Demos/ai_Jenkins_Demo/test_cases/JenkinsFileCheck.fftc Standard_Jenkins_Demo $WORKSPACE/test.txt
         '''
        
      }
    }
  stage('Pull Helm Chart from GitHub') {
    
    
  }
    
    
  }
}

