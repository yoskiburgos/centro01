pipeline {
    agent any
    /*triggers {
        pollSCM('* * * * *')
    }*/
    stages {
        stage("Compile") {
            steps {
               // sh "mvn -f pom.xml clean install -Dmaven.test.skip=true"
               // sh "tree"
			   
			   sh 'mvn -B -DskipTests clean package'
            }
        }
        
        /*
        stage('SonarQube analysis') {
        steps {
            script{
            def scannerHome = tool 'sonarscan';
            withSonarQubeEnv('sonarqube') {
                sh "${tool("sonarscan")}/bin/sonar-scanner \
                    -Dsonar.projectKey=reactapp \
                    -Dsonar.projectName=reactapp"
            }
            }
        }
	} */
		
		
		
		
		
		
    }
}
