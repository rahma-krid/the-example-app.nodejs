node {
  
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
       bat 'npm install'
    }
  
    stage('test') {
     bat 'npm test'
    }
    
    stage('deploy') {
        bat 'npm start'
    }
    
   
}
