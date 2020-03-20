node {
  
      stage('Postman CI Demo') {
      git 'https://github.com/MChodap1/postman-CI-demo'
      }
      stage('Install Node Dependencies'){
      bat 'npm install'
      }
      stage('Run Tests'){
      bat 'npm run api-tests'
      }
}
