node {
    
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
         sleep 10
       sh 'npm install'
    }
    stage('deploy') {
        sh 'npm start'
    }
    
     stage('test') {
     echo 'testing app'
    }
}
