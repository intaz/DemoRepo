node('master'){ 
  stage('1st stage'){
  echo 'hello world'
  }
  stage('Run Project'){
    tool name: 'MAVEN_3.6.1', type: 'maven'
    sh 'mvn test'
  }

}
