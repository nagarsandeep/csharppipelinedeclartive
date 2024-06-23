pipeline {
	agent any
	tools {
		msbuild 'MSBUILD1'
	}

	stages{
	 stage('build'){
	   steps{
		echo 'building ...'
		bat 'C:\Users\sandnaga\.jenkins\csharppipelinedeclarativepipeline\MsBuild\HelloWorld\HelloWorld.sln'
	   }
		
	 }
	}
}
	
	
