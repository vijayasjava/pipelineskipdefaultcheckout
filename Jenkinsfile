pipeline {
  agent any 
  stages {
    stage("first") {
      options{
	skipDefaultCheckout()
      }	    
      steps {
        echo "first build"
      }
    }
    stage("second") {
      steps {
        echo "second build"
      }
    }
    stage("develop addition") {
    	steps {
	  echo "develop branch addition"
	}
    }
  }
}
