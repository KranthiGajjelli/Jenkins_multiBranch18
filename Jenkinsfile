node('built-in') 
{
    stage('Continuous Download_products') 
	{
    git 'https://github.com/KranthiGajjelli/Maven.git'
	}
    stage('Continuous Build_products') 
	{
    sh label: '', script: 'mvn package'
	}
    }
