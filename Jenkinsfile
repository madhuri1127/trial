node
{
stage('Checkout')
{
git "https://github.com/madhuri1127/trial"
 
}
 stage('Compile')
{
if(true)
	{
 sh "mvn clean install"

	}
	else
	{
		echo 'hellooooo'
	}
}

stage('Test')
{
sh "mvn test"
 
}
 
 stage('deploy')
 {
 
echo 'cat sam.sh'
  
 }
 





}
