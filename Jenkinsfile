node {
  
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
       //install dependencies 
       bat 'npm install'
    }
  
   stage('deploy') {
     //start the app 
     bat 'start /b npm run start:dev'
    }
  
    stage('test') {
    
      bat 'npm test'
    }
    
   
    
   
}
