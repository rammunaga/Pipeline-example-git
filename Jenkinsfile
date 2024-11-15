pipeline{
    agent any

    stages{
    stage("complie"){
        steps{
            bat 'javac Test.java'
        }

    }

    stage("run"){
         steps{
            bat 'java Test'
        }  

    }
    }

}