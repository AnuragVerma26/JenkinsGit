pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
               echo "Buildong the code using a build automation tool to compile and pacakaging the code"
               echo "The tool that will be used to build an automation is Maven,Docker,Gradle"
            }
        }
        stage("Unit and Integration Tests") {
            steps {
                echo "Running unit tests to make sure that code function as expected further performing integration tests to make sure that various components are working as expected"
                echo "Test automation tools that can be used to perform unit and integration testing include Selenium,JUnit,cucumber"
            }
        }
        stage("Code Analysis"){
            steps {
                echo "To perform code analysis the tools that cab be used are SonarQube,Checkstyle,FindBugs"
            }
        }
        stage("Security Scan"){
            steps{
                echo "peforming security scan on the code to identify the vulnerabilities for that we are using OWASP dependency check,OWASP ZAP,Fortify"
            }
        }
        stage("Deploy to staging"){
            steps{
                echo "Deploying the application to staging server AWS EC2"
                
            }
        }
        stage("Integration Tests on Staging"){
            steps{
                echo "Running integration tests on staging environment to make sure applications are running properly using Selenium,SoapUI"
            }
        }
        stage("Deploy to production"){
            steps{
                echo "Deploying the application to production server AWS EC2"
            }
        }
    }
}

    
