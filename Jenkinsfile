node {
    stage('Test') {
      checkout scm
      echo "In Branch ${env.BRANCH_NAME}"
      sh 'git fetch'
      sh 'printenv'
    }
}
