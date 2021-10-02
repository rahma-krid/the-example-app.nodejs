node {
  
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
       bat 'npm install'
    }
  
   stage('deploy') {
        bat 'npm run start:dev'
    }
  
    stage('test') {
     echo 'npm test'
    }
    
   
    
   
}
