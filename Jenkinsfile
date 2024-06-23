pipeline {
	agent any
	 environment{
              Msbuild2019 = "C:\\Program Files (x86)\\Microsoft Visual Studio\\2019\\Professional\\MSBuild\\Current\\Bin\\MsBuild.exe"
            }
	tools{
	    msbuild 'MSBUILD1'
	}

	stages{
	    stage('build'){
            steps{
		        echo "building ..."
		        bat "msbuild.exe HelloWorld\\HelloWorld.sln"
	        }
		}
	}
}
	
	
