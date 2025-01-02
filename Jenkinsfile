pipeline {
	agent any
	    stages {
              stage('SourceCode') {
                 steps {
 		      git 'https://github.com/Jenkins-Course/game-of-life.git'
                 }
              }
	     stage('Build the code') {
                 steps {
                      sh 'mvn clean package'
                 }
              }
           }
}


