node('built-in') 
{
    stage('Continuous_Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous_Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
