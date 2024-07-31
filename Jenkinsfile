node('built-in') 
{
    stage('continuous_download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('continuous_build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
