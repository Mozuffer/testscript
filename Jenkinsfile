pipeline {
   agent any

   stages {
      stage('Preperation') {
         steps {
            sh 'chmod +x testscript.sh'
         }
      }
      stage('Run') {
	 steps {
	    sh './testscript.sh >>output.txt'	
	 }
     }
   }
}
