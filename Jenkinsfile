pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               /* withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean compile'
                }*/
                echo "Compile"
                mvn --version
            }
        }

        stage ('Testing Stage') {

            steps {
                /*withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
                }*/
                echo "Test"
                mvn --version
            }
        }


        stage ('Deployment Stage') {
            steps {
                /*withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn deploy'
                
                }*/
            echo "deploy"
            mvn --version
            }
        }
    }
}
