pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
               /* withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean compile'
                }*/
                echo "Compile"
            }
        }

        stage ('Testing Stage') {

            steps {
                /*withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn test'
                }*/
                echo "Test"
            }
        }


        stage ('Deployment Stage') {
            steps {
                /*withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn deploy'
                
                }*/
            echo "deploy"
            }
        }
    }
}
