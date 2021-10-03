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
        echo 'npm run start:production'
    }
  
    stage('test') {
    
      echo 'npm test'
    }
    
   
    
   
}
