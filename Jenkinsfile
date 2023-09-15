pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "build the code and using Maven"
            }
            
        }
        stage('Integration Test'){
            steps{
                echo "run unit tests to ensure execution of functionalities by using selenium"
            }
        }
        stage('Code Analysis'){
            steps{
                echo "analyse the code to ensure it meets industry standards. Tool is Jenkins!"
            }
        }
        stage('Security Scan'){
            steps{
                echo "Performed a security scan and identifies vulnarabilities. Tool is Nmap"
            }
        }
        stage('Deploy to staging'){
            steps{
                echo "Deploy the application to a staging server. Tool is AWS EC2"
            }
        }
         stage('Integration Testints on staging'){
            steps{
                    echo "Run integration tests on the staging enviornment to ensure the applications functions s expected! enviornment is production"
                }
            }
        stage('Deploy to production'){
            steps{
                echo "Deployment of the application to a production server. Tool is AWS EC2!"
            }
        }
		
    }
    
}