pipeline {
    agent none

    stages {
        stage('CHECKOUT') {
            
            agent {
                label 'slave2'
            } 

            steps {
                echo "This is Checkout stage"
                sleep 5
            }
        }

        stage('BUILD') {

            agent any

            steps {
                echo "This is Build stage"
                sleep 5
            }
        }
    }
}
