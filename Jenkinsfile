node {
   
   stage('SCM Checkout'){
    // Clone repo
        git branch: 'master',
        credentialsId: 'github',
        url: 'https://github.com/kumarsandeep590/mytest'
        }
   
   stage('Complie-Package'){
    sh 'mvn package'
    }
   
}

