pipeline {
   agent any

   stages {
      stage('Preperation') {
         steps {
            echo 'Preparing...'
         }
      }
      stage('Run') {
	 steps {
	    sh 'make'	
	 }
     }
   }
}
