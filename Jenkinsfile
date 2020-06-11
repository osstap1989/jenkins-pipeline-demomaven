
node {
   // This is to demo github action	
   stage('SCM Checkout'){
    
    git 'https://github.com/osstap1989/jenkins-pipeline-demomaven'
   
   }
   stage('Compile-Package'){
    def mvnHome = tool name: '', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
    }
    
}
