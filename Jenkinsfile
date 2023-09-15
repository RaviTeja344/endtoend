pipeline{

agent any

stages{
stage('Git Checkout'){
steps{
git branch: 'develop' , url: 'https://github.com/RaviTeja344/endtoend.git'
}
}
stage('Maven Clean'){
steps{
sh 'mvn clean install'
}
}
}
}