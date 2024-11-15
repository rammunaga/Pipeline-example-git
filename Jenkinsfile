pipeline{
    agent any

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