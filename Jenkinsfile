node {
    
    stage('scm') {
    // some block
    git credentialsId: '708054d1-5926-426a-b16e-98a956a78cf3', url: 'https://github.com/ugreddy/spring-petclinic.git'
    }
    stage('--clean--') {
   
     bat 'mvn clean'
    }
    
    stage('--test--') {
   
     bat 'mvn test'
    }
    
    
    stage('--package--') {
   
     bat 'mvn package'
    }
    
 

}
