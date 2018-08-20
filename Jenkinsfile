node{
   stage('SCM Checkout'){
     git 'https://github.com/amarroy87/firstpractice'
   }
 		stage('ContinuousBuild') {
            steps {
                sh 'mvn package'
            }
        }
}
