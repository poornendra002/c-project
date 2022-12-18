pipeline {
    agent none
    stages {
        
        stage ('clone') {
            agent { label 'poorna' }
            when {
  expression {env.GIT_BRANCH == 'origin/main'}
}
            steps {
            git branch: 'master', url: 'https://github.com/poornendra002/c-project.git'
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
