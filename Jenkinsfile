node {
    
    stage('scm') {
    // some block
    git credentialsId: '708054d1-5926-426a-b16e-98a956a78cf3', url: 'https://github.com/ugreddy/spring-petclinic.git'
    }
    stage('scm') {
   
     bat 'mvn clean'
    }
    
    stage('scm') {
   
     bat 'mvn test'
    }
    
    
    stage('scm') {
   
     bat 'mvn package'
    }
    
 

}
