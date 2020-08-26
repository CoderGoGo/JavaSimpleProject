node('master') {
    stage('SCM Checkout') {
          git 'https://github.com/CoderGoGo/JavaSimpleProject'    
    }
    stage('Build java') {
          sh 'mvn package'    
    }
    }
