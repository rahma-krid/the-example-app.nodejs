node {
  
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
       bat 'npm install'
    }
    stage('deploy') {
        bat 'npm start'
    }
    
     stage('test') {
     echo 'testing app'
    }
    
}
