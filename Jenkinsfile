pipeline{
    agent any
    stages {
        stage ("git scm checkout")
        steps{
           git 'https://github.com/kumargaurav039/maven-project.git'
        }
    }
    stages{
        stage("L2")
        steps{
            echo 'MI'
        }
    }
    stages{
        stage("L3")
        steps{
            echo 'Pune'
        } 
    }
}
