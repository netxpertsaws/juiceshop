pipeline {
        agent any
        stages {
           stage ( "run frondend") {
               steps {
                          echo 'Executing Yarn'
                          nodejs('Node-10.17.0'){
                            sh 'yarn install'
                             sh 'sh test'
                            }
                   }
             }
}
