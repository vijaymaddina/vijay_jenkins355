node('built-in') 
{
    stage('Continuous Download_develop') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_develop') 
	{
    sh label: '', script: 'mvn package'
	}
}
