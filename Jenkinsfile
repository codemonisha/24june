@Library('javahome-demo1') _

pipeline{
    agent any
    stages{
        stage('demo'){
            steps{
                hello ("monisha")
                script{
                calculator.add(10,20)
                calculator.mult(10,20)
                }
            }
        }
    }
    
    
}
