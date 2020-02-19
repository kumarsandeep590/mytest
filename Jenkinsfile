node {
   
   stage('SCM Checkout'){
    // Clone repo
        git branch: 'master',
        credentialsId: 'github',
        url: 'https://github.com/kumarsandeep590/mytest'
        }
   
   stage('Complie-Package'){
      //Get maven home path
      def mvnHome = tool name: 'maven', type: 'maven'
      sh '${mvnHome}/bin/mvn package'
    }
   
}

