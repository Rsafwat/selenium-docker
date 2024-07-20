    pipeline{
    agent any
    stages{
       stage('build jar'){
          steps{
         sh "mvn clean package -DskipTests"
         }}
       stage('build image'){
          steps{
           sh "docker build -it  rokaya1525/selenium ."
                    } }
       stage('push image'){
            steps{
             sh "docker push rokaya1525/selenium"
             } }

    }   
              }