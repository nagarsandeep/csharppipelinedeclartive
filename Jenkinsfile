pipeline {
	agent any
	tools {
		msbuild 'MSBUILD1'
	}

	stages{
	    stage('build'){
            steps{
		        echo "building ..."
		        bat \"${Msbuild2019}\" "C:\\Users\\sandnaga\\.jenkins\\csharppipelinedeclarativepipeline\\MsBuild\HelloWorld\\HelloWorld.sln"
	        }
		}
	}
}
	
	
