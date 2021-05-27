pipeline {
    agent any
    stages {
        stage ("cloning from git")
        {
            steps {
                git branch: 'main', url: 'https://github.com/biswa777/myDevops.git'
            }
        }
        stage ("build"){
            steps{
                echo "build stage"
            }
        }
        stage ("deploy"){
            steps{
                echo "deploy stage"
            }
        }
    }
}
