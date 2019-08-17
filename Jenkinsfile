pipeline{
agent any
stages{
stage('build'){
      steps{
            echo 'running build'
            sh './gradlebuild --no-daemon'
            archiveArtifacts : 'dist/train.zip'
            }
            }
            }
            }
