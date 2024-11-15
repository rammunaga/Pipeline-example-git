pipeline{
    agent any

    tools{
        maven "Maven"
    }

    environment{
        VERSION_NAME="1.34"
    }

    stages{
    stage("complie"){
        steps{
            bat 'javac Test.java'
            bat 'echo "${VERSION_NAME}"'
        }

    }

    stage("run"){
         steps{
            bat 'java Test'
        }  

    }
    }

    post{

        always{
            bat 'echo "always"'
        }

        success{
            bat 'echo "success"'
        }

        failure{
            bat 'echo "failure"'
        }
    }

}