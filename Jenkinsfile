node{
  stagw('SCM Checkout'){
    git 'https://github.com/naveenchacko1/example-voting-app'
  }
  stage('Compile-Package'){
   def mvnHome =  tool name: 'MAVEN_HOME', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
