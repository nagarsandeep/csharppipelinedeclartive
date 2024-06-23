pipeline {
	agent any
	tools {
		msbuild 'MSBUILD1'
	}

	stages{
	    stage('build'){
            steps{
		        echo "building ..."
		        bat "\"${msbuild}\" csharppipelinedeclarativepipeline\\MsBuild\HelloWorld\\HelloWorld.sln"
	        }
		}
	}
}
	
	
