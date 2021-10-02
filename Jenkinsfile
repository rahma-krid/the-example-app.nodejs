node {
     environment {
        HOME = '.'
    }
    stages{
    stage('Cloning') { 
        git url:' https://github.com/rahma-krid/the-example-app.nodejs.git'
    }
    stage('build') {  
       sh 'npm install'
    }
    stage('deploy') {
        echo 'npm start'
    }
    
     stage('test') {
     echo 'testing app'
    }
    }
}
