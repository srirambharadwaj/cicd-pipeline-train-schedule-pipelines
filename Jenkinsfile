piipeline {
 agent any
 stages {
 stage('Build'){
 steps{
 
 echo 'Running Build automation'
 sh './gradlew build --no-daemon'
 archiveArtifacts artifacts: 'dist/trainschedule.zip'
}
}
}
 }
