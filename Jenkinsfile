pipeline {
    agent any;
    stages {
        stage("A"){
            steps{
                echo "====++++executing A++++===="
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++A executed successfully++++===="
                }
                failure{
                    echo "====++++A execution failed++++===="
                }
        
            }
        }
        stage("B"){
            steps{
                echo "====++++executing B++++===="
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++B executed successfully++++===="
                }
                failure{
                    echo "====++++B execution failed++++===="
                }
        
            }
        }
    }
}