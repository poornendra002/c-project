pipeline {
    agent none
    stages {
        
        stage ('clone') {
            agent { label 'poorna' }
            when {
  branch 'master'
}
            steps {
            git branch: 'main', url: 'https://github.com/poornendra002/c-project.git'
}
        }
        stage ('build') {
            agent { label 'poorna' }
            

            steps {
                echo "this is master branch"
                
            }
        }
    }
}
