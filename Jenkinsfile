node
{
stage('read')
{
git "https://github.com/madhuri1127/trial"
 
}
 stage('package')
{
 when {
    
    expression { return false }
}
steps {
    /* step */
 sh "mvn clean install"
}

}

stage('test')
{
sh "mvn test"
 
}
 
 stage('deploy')
 {
 
  "sh /root/sam.sh "
  
 }
 





}
