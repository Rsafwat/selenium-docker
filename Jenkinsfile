    /*
    Note:

    Windows users use "bat" instead of "sh"
    For ex: bat 'docker build -t=vinsdocker/selenium .'

    Do not use "vinsdocker" to push. Use your dockerhub account
*/
    pipeline{
    agent any
    stages{
       stage('build jar'){
          steps{
         bat "mvn clean package -DskipTests"
         }}


    }
      }