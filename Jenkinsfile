node {
    
    stage('Cloning') { 
        git url:' https://github.com/contentful/the-example-app.nodejs.git'
    }
    stage('build') {      
       sh 'npm install'
    }
    stage('deploy') {
        sh 'npm start'
    }
    
     stage('test') {
     echo 'testing app'
    }
}
