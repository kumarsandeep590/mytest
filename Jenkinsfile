node {
   
   stage('SCM Checkout'){
    // Clone repo from Github
        git branch: 'master',
        credentialsId: 'github',
        url: 'https://github.com/kumarsandeep590/mytest'
        }
   
   stage('Complie-Package'){
      //Get maven home path OK
      //def mvnHome = tool name: 'maven', type: 'maven'
      sh 'mvn package'
    }
   
}

