pipeline {
	    agent any 
	    stages {
	        stage('one') { 
	            steps {
	                echo 'Hi, this is chhaya'
	            }
	        }
	        stage('Two') { 
	            steps {
	              input('Do you want to proceed?')
	            }
	        }
	        stage('Three') { 
	        when{
	        not{
	            branch "master"
	          }
	        }
	            steps {
	            echo "Hello testing when"
	            }
	        }
	    }
	}
